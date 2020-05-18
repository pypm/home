Details of the MCMC likelihood calculation

The MCMC method requires calculating the data likelihood, the probability density for the data observed given a hypothesis.
The approach used in `pypmca` is optimized for a cumulative
indicator. For the CoViD-19 outbreak this was chosen to be reported cases.
A cumulative is used instead of daily values
because this indicator suffers from large reporting noise
on a daily basis - with large negative correlations between neighbouring days. The effect is smaller on the
cumulative. Still, reporting noise should be included in simulation samples (it is an optional parameter in pypmca
population models).

Because cumulative data is being used, it is essential to include the auto-covariance in the likelihood.
The shape and normalization of the cumulative indicator are separated so that the auto-covariance
does not include the very large effect from overall normalization. The separation is achieved when
calculating chi^2, by scaling the reference model so that its last point coincides with the simulated/real data.
The contribution from normalization is evaluated separately by using the values in the last point.
The autocovariance therefore does not include the last point: its rank is one less than the number of points being fit.

It is assumed that the model has an initial state parameter that scales all final state population sizes.
In the reference models 1&2, this is the cont_0 parameter (number contagious at day 0).
The simple scaling applied (to separate the shape from normalization) assumes that the initial (t_0)
value for the indicator is near zero.

The following steps are taken to define the likelihood for the MCMC analysis:

(1) The data is fit to find point estimates for the variable parameters. This is done in the analysis tab, and
must be done prior to starting the MCMC analysis. As a check, a naive goodness of fit (shape only) is calculated
and saved as self.chi2d. It is naive, in that it assumes that the data are outcomes of independent Poisson random variables.
The model with the parameters set to these point estimates is referred to as the reference model.

(2) The autocovariance is calculated by producing a set of many simulated datasets from this reference model.
The residuals from the reference model expectations are used to calculate the model auto-covariance. This may differ from the actual
autocovariance if reporting errors are not correctly included or if the model does not contain other important
sources of variance.

(3) An independent set of many simulated datasets from the reference model are produced and the goodness
of fit statistic for each simulated dataset is calculated using different methods to understand the importance of
autocorrelation and to detect any significant difference between noise in data and simulation:
  * chi2_m is the naive goodness of fit (shape only) calculated with respect to the reference model
  * chi2_n is the goodness of fit (normalization only): one degree of freedom - the last data value
  * chi2_f is the naive goodness of fit (shape only) calculated with respect to a reference model fitted to that data
  (this is time consuming and only calculated if self.calc_chi2_f is set to True)
  * chi2_s is the goodness of fit (shape only, with autocorrelation) calculated with respect to the reference model
The means and standard deviations of the gof distributions are saved (in self.chi2m, self.chi2m_sd etc) and the lists
of the values are also available for further study in self.chi2_lists dictionary with keys 'm', 'n', 'f', 's'

The chi2_n is calculated with only one degree of freedom (the last data point). This is far from being
well described by a Poisson random variable. Due to fluctuations early in an exponential growth period, the
fluctuations can be very large. Empirically it was found that the distribution for chi2_n/mean(chi2_n) does
follow a chi2 distribution for one degree of freedom. So the likelihood calculation includes, in addition to
the shape contribution, the normalization contribution as calculated by chi2_n/mean(chi2_n), adding one degree
of freedom.

Note: in checking this method with simulated samples, it was found that the chi2_s as calculated by
-2 log(delta likelihood), where likelihood is from the stats.multivariate_normal, follows the chi^2 distribution
much better when the definition is altered (empirically) such that chi2_s = - log(delta likelihood).
Also, the mean of the distribution is much closer to the expected number of degrees of freedom.
It is not understood why this is the case. Since the sampling distribution is better described
and it yields more conservative confidence intervals, the altered statistic is used.

(4) The likelihood is calculated using the probability density of the chi^2 distribution.
The number of degress of freedom can be specified. If the model included all sources of variation correctly,
the best estimate for dof would be the mean(chi2s). This value should be
increased to account for additional degrees of freedom that reflect the unaccounted for noise, coming from the study in part (3).
