## January 23, 2022 Analysis of US state data

The characteristic signature of recent rapid growth due to Omicron is
visible in all US state case history data.
For this analysis, the case and death data source is the New York Times, since it has
has more regular updates and fewer irregularities than the JHU data.

For some states, testing capacity limits have changed the fraction of
infections that are reported as cases, making interpretation of cases
much more difficult.
Further complicating matters is the usual effect of holiday periods
disrupting testing and reporting.
Hospital admission data can be used when cases are no longer reliable.

The report has two sections, the first showing the rapid decline
in growth rates for Omicron infections and the second showing studies of
hospital demands for Omicron infections.

## Rapid reduction in Omicron growth rates

As usual, the infection model is defined by fitting the model to the case data, and the
hospitalization and deaths models are derived from the infection model.
To estimate the recent transmission rate of Omicron, hospital admission data
is used.
For many states, case data appears to be reliable and yields similar transmission rate estimates.

The Omicron variant is assumed to have a much larger susceptible population, due to its
ability to evade immunity (natural and vaccination immunity). 
For this study, those immunized against earlier strains only have 20% effective immunity
against omicron.

Booster doses have been included in this analysis, and are assumed to raise the
vaccine effectiveness from 20% to 80% with a time delay given by a gamma distribution with
mean 10 days and standard deviation 5 days.

The Omicron variant is also assumed to produce more infections that go undetected as cases.
The reporting fraction of omicron infections is assumed to be 0.6 times that of Delta infections.
This has the effect of reducing peak infection and hospitalization rates.
The scaling of the reporting fraction had been 0.4 in previous analyses of US data, 
but is changed to 0.6, given the inclusion of boosters in the model, which increases
population immunity.

The green points are the daily cases, the grey points the daily hospitalizations, 
the teal points are hospital occupancy, and the indigo points are the daily deaths. 
The larger circles are weekly averages to help guide the eye.

The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
If the susceptibe fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline.
With immunity growing, the curves bend downwards due to the herd effect.
Interpretting the growth of Omicron with changing Delta rates growth rates leads to additional
uncertainty in the interpretations.

Note that for these analyses, hospital admission data were used to estimate the recent
infection trajectory, to avoid potential problems with case data no longer being reliable.

### Individual state hospitalization analyses

The plots for each state below show the case, hospital admisions, and deaths data since
October 15 2021, on a linear scale (left) and log scale (right).
Daily hospital admissions are scaled up by 5 to be able to see them on the linear scales.
The right figures show how the model attributes cases from Delta and Omicron infections,
and the hospital admissions from Omicron infections.
Omicron hospital admissions make a useful metric to compare 
the growth of Omicron across different states, removing
the widely variable Delta hospital admissions.

The model is able to describe data from the states by introducing a transition to lower
transmission rate near the end of December 2021.
This introduces a kink in the log scale plots (as constant transmission rate
corresponds to straight lines, if population immunity is roughly constant).

Following the individual state plots, summaries of all states are shown below.

### [Alaska](img/ak_4_2_0123.pdf)

![ak](img/ak_4_2_0123.png)

### [Alabama](img/al_4_2_0123.pdf)

![al](img/al_4_2_0123.png)

### [Arkansas](img/ar_4_2_0123.pdf)

![ar](img/ar_4_2_0123.png)

### [Arizona](img/az_4_2_0123.pdf)

![az](img/az_4_2_0123.png)

### [California](img/ca_4_2_0123.pdf)

![ca](img/ca_4_2_0123.png)

### [Colorado](img/co_4_2_0123.pdf)

![co](img/co_4_2_0123.png)

### [Connecticut](img/ct_4_2_0123.pdf)

![ct](img/ct_4_2_0123.png)

### [District Of Columbia](img/dc_4_2_0123.pdf)

![dc](img/dc_4_2_0123.png)

### [Delaware](img/de_4_2_0123.pdf)

![de](img/de_4_2_0123.png)

### [Florida](img/fl_4_2_0123.pdf)

![fl](img/fl_4_2_0123.png)

### [Georgia](img/ga_4_2_0123.pdf)

![ga](img/ga_4_2_0123.png)

### [Hawaii](img/hi_4_2_0123.pdf)

![hi](img/hi_4_2_0123.png)

### [Iowa](img/ia_4_2_0123.pdf)

![ia](img/ia_4_2_0123.png)

### [Idaho](img/id_4_2_0123.pdf)

![id](img/id_4_2_0123.png)

### [Illinois](img/il_4_2_0123.pdf)

![il](img/il_4_2_0123.png)

### [Indiana](img/in_4_2_0123.pdf)

![in](img/in_4_2_0123.png)

### [Kansas](img/ks_4_2_0123.pdf)

![ks](img/ks_4_2_0123.png)

### [Kentucky](img/ky_4_2_0123.pdf)

![ky](img/ky_4_2_0123.png)

### [Louisiana](img/la_4_2_0123.pdf)

![la](img/la_4_2_0123.png)

### [Massachusetts](img/ma_4_2_0123.pdf)

![ma](img/ma_4_2_0123.png)

### [Maryland](img/md_4_2_0123.pdf)

![md](img/md_4_2_0123.png)

### [Maine](img/me_4_2_0123.pdf)

![me](img/me_4_2_0123.png)

### [Michigan](img/mi_4_2_0123.pdf)

![mi](img/mi_4_2_0123.png)

### [Minnesota](img/mn_4_2_0123.pdf)

![mn](img/mn_4_2_0123.png)

### [Missouri](img/mo_4_2_0123.pdf)

![mo](img/mo_4_2_0123.png)

### [Mississippi](img/ms_4_2_0123.pdf)

![ms](img/ms_4_2_0123.png)

### [Montana](img/mt_4_2_0123.pdf)

![mt](img/mt_4_2_0123.png)

### [North Carolina](img/nc_4_2_0123.pdf)

![nc](img/nc_4_2_0123.png)

### [North Dakota](img/nd_4_2_0123.pdf)

![nd](img/nd_4_2_0123.png)

### [Nebraska](img/ne_4_2_0123.pdf)

![ne](img/ne_4_2_0123.png)

### [New Hampshire](img/nh_4_2_0123.pdf)

![nh](img/nh_4_2_0123.png)

### [New Jersey](img/nj_4_2_0123.pdf)

![nj](img/nj_4_2_0123.png)

### [New Mexico](img/nm_4_2_0123.pdf)

![nm](img/nm_4_2_0123.png)

### [Nevada](img/nv_4_2_0123.pdf)

![nv](img/nv_4_2_0123.png)

### [New York](img/ny_4_2_0123.pdf)

![ny](img/ny_4_2_0123.png)

### [Ohio](img/oh_4_2_0123.pdf)

![oh](img/oh_4_2_0123.png)

### [Oklahoma](img/ok_4_2_0123.pdf)

![ok](img/ok_4_2_0123.png)

### [Oregon](img/or_4_2_0123.pdf)

![or](img/or_4_2_0123.png)

### [Pennsylvania](img/pa_4_2_0123.pdf)

![pa](img/pa_4_2_0123.png)

### [Puerto Rico](img/pr_4_2_0123.pdf)

![pr](img/pr_4_2_0123.png)

### [Rhode Island](img/ri_4_2_0123.pdf)

![ri](img/ri_4_2_0123.png)

### [South Carolina](img/sc_4_2_0123.pdf)

![sc](img/sc_4_2_0123.png)

### [South Dakota](img/sd_4_2_0123.pdf)

![sd](img/sd_4_2_0123.png)

### [Tennessee](img/tn_4_2_0123.pdf)

![tn](img/tn_4_2_0123.png)

### [Texas](img/tx_4_2_0123.pdf)

![tx](img/tx_4_2_0123.png)

### [Utah](img/ut_4_2_0123.pdf)

![ut](img/ut_4_2_0123.png)

### [Virginia](img/va_4_2_0123.pdf)

![va](img/va_4_2_0123.png)

### [Vermont](img/vt_4_2_0123.pdf)

![vt](img/vt_4_2_0123.png)

### [Washington](img/wa_4_2_0123.pdf)

![wa](img/wa_4_2_0123.png)

### [Wisconsin](img/wi_4_2_0123.pdf)

![wi](img/wi_4_2_0123.png)

### [West Virginia](img/wv_4_2_0123.pdf)

![wv](img/wv_4_2_0123.png)

### [Wyoming](img/wy_4_2_0123.pdf)

![wy](img/wy_4_2_0123.png)


## Comparisons of Omicron daily hospital admissions

Hospital admissions can be used in a per-capita comparison of infections between states,
avoiding potential issues with test capacity.
Using Omicron hospital admissions removes the variability of the Delta hospital admissions taking
place during the emergence of Omicron.
This metric relies on a model to attribute hospital admissions during the phase when Delta contributes
a substantial fraction of hospital admissions.

The plot below shows this metric, aligned on the day that Omicron hospital 
admissions first exceeded 2 per day per 100,000.
The solid lines end on January 23, and the dashed lines show
model projections.

![hosp](img/USA_compare_omicron_hosp_aligned.png)

The same figure shown in log scale:

![hosplog](img/USA_log_compare_omicron_hosp_aligned_log.png)

The growth pattern is remarkably similar across the states, considering
the large variety of populations and environments.

The figure below shows the daily growth rate of Omicron hospital admissions
(as derived from the models).
A remarkable drop in Omicron infection rates is apparent.
The reason for the rather sudden and persistent change in transmission rate
is not understood.

![hospgrowth](img/USA_growth_omicron_hosp.png)

## Omicron and hospitalization

The analysis presented here, fits multi-strain models 
to case data in each state
and use hospital data to compare Omicron to Delta in terms of:

 * the relative severity of omicron infections 
 (odds ratio for hospital admission) and relative
 
 * duration of hospital stays (ratio of mean duration)

Case and hospital data broken down by variant(using genomic information) are not available.
Instead, the multi-strain model fit uses the characteristic
signature of rapidly growing cases to describe the transition from
Delta to Omicron cases.
Fits are illustrated for each state showing the resulting curves for
Delta and Omicron daily cases and their sum compared to overall cases.

Having the infection model defined for each variant separately allows for
parameters for their relative hospitalization rate and hospital treatment durations to be 
fit for each state.

The Omicron severity is defined as the fraction of symptomatic Omicron infections that lead to hospitalizations,
relative to the same fraction for Delta infections.
Assuming that both case and hospital admission data remain consistent indicators for infections, previous
analyses here have established the severity to be approximately 0.4,
indicating that Omicron infections are significantly less severe than Delta infections.

For these analyses, hospital admission data were primarily used to estimate the recent
infection trajectory, which could affect estimates of severity.

By using hospital admission and occupancy data, the duration of hospital stays can be estimated.
The figures below show the estimate mean durations for Omicron and Delta hospitalizations,
and their ratio.
The mean ratio of durations is 0.9 with a standard deviation of 0.2.
The duration of treatment does not appear to be significantly
shorter for Omicron hospitalizations.

![scatter](img/USA_4_2_0116_duration_scatter.png)
![ratio](img/USA_4_2_0116_duration_ratio.png)

### Individual state hospitalization analyses

The plots for each state below show the case, hospitalization, and deaths data since
August 2021 (left) and since November 15 2021 (right).
The maximum vertical axis values for cases are 500/100k (left) and 200/100k (right).
Daily hospital admissions and deaths are scaled up by 20 to be able to see them on a single plot.

The severity is estimated from the hospital admission data, and its value is shown in the legend.
The hospital durations (mean Omicron duration and mean Delta duration) are estimated from the
hospital occupancy data, and the ratio (Omicron divided by Delta) is shown in the legend.
Omicron and Delta hospital parameters can both be estimated from these data only
because of the different relative prevalence by date, as indicated by the
fits to the case data.

For many states there are now sufficent data to estimate the relative death rates for Omicron and Delta
infections, with values shows in the legend. 
For the remaining states, round estimates of 0.1 or 0.2 are shown.

### [Alaska](img/ak_4_2_0123_linear_omicron.pdf)

![ak](img/ak_4_2_0123_linear_omicron.png)

### [Alabama](img/al_4_2_0123_linear_omicron.pdf)

![al](img/al_4_2_0123_linear_omicron.png)

### [Arkansas](img/ar_4_2_0123_linear_omicron.pdf)

![ar](img/ar_4_2_0123_linear_omicron.png)

### [Arizona](img/az_4_2_0123_linear_omicron.pdf)

![az](img/az_4_2_0123_linear_omicron.png)

### [California](img/ca_4_2_0123_linear_omicron.pdf)

![ca](img/ca_4_2_0123_linear_omicron.png)

### [Colorado](img/co_4_2_0123_linear_omicron.pdf)

![co](img/co_4_2_0123_linear_omicron.png)

### [Connecticut](img/ct_4_2_0123_linear_omicron.pdf)

![ct](img/ct_4_2_0123_linear_omicron.png)

### [District Of Columbia](img/dc_4_2_0123_linear_omicron.pdf)

![dc](img/dc_4_2_0123_linear_omicron.png)

### [Delaware](img/de_4_2_0123_linear_omicron.pdf)

![de](img/de_4_2_0123_linear_omicron.png)

### [Florida](img/fl_4_2_0123_linear_omicron.pdf)

![fl](img/fl_4_2_0123_linear_omicron.png)

### [Georgia](img/ga_4_2_0123_linear_omicron.pdf)

![ga](img/ga_4_2_0123_linear_omicron.png)

### [Hawaii](img/hi_4_2_0123_linear_omicron.pdf)

![hi](img/hi_4_2_0123_linear_omicron.png)

### [Iowa](img/ia_4_2_0123_linear_omicron.pdf)

![ia](img/ia_4_2_0123_linear_omicron.png)

### [Idaho](img/id_4_2_0123_linear_omicron.pdf)

![id](img/id_4_2_0123_linear_omicron.png)

### [Illinois](img/il_4_2_0123_linear_omicron.pdf)

![il](img/il_4_2_0123_linear_omicron.png)

### [Indiana](img/in_4_2_0123_linear_omicron.pdf)

![in](img/in_4_2_0123_linear_omicron.png)

### [Kansas](img/ks_4_2_0123_linear_omicron.pdf)

![ks](img/ks_4_2_0123_linear_omicron.png)

### [Kentucky](img/ky_4_2_0123_linear_omicron.pdf)

![ky](img/ky_4_2_0123_linear_omicron.png)

### [Louisiana](img/la_4_2_0123_linear_omicron.pdf)

![la](img/la_4_2_0123_linear_omicron.png)

### [Massachusetts](img/ma_4_2_0123_linear_omicron.pdf)

![ma](img/ma_4_2_0123_linear_omicron.png)

### [Maryland](img/md_4_2_0123_linear_omicron.pdf)

![md](img/md_4_2_0123_linear_omicron.png)

### [Maine](img/me_4_2_0123_linear_omicron.pdf)

![me](img/me_4_2_0123_linear_omicron.png)

### [Michigan](img/mi_4_2_0123_linear_omicron.pdf)

![mi](img/mi_4_2_0123_linear_omicron.png)

### [Minnesota](img/mn_4_2_0123_linear_omicron.pdf)

![mn](img/mn_4_2_0123_linear_omicron.png)

### [Missouri](img/mo_4_2_0123_linear_omicron.pdf)

![mo](img/mo_4_2_0123_linear_omicron.png)

### [Mississippi](img/ms_4_2_0123_linear_omicron.pdf)

![ms](img/ms_4_2_0123_linear_omicron.png)

### [Montana](img/mt_4_2_0123_linear_omicron.pdf)

![mt](img/mt_4_2_0123_linear_omicron.png)

### [North Carolina](img/nc_4_2_0123_linear_omicron.pdf)

![nc](img/nc_4_2_0123_linear_omicron.png)

### [North Dakota](img/nd_4_2_0123_linear_omicron.pdf)

![nd](img/nd_4_2_0123_linear_omicron.png)

### [Nebraska](img/ne_4_2_0123_linear_omicron.pdf)

![ne](img/ne_4_2_0123_linear_omicron.png)

### [New Hampshire](img/nh_4_2_0123_linear_omicron.pdf)

![nh](img/nh_4_2_0123_linear_omicron.png)

### [New Jersey](img/nj_4_2_0123_linear_omicron.pdf)

![nj](img/nj_4_2_0123_linear_omicron.png)

### [New Mexico](img/nm_4_2_0123_linear_omicron.pdf)

![nm](img/nm_4_2_0123_linear_omicron.png)

### [Nevada](img/nv_4_2_0123_linear_omicron.pdf)

![nv](img/nv_4_2_0123_linear_omicron.png)

### [New York](img/ny_4_2_0123_linear_omicron.pdf)

![ny](img/ny_4_2_0123_linear_omicron.png)

### [Ohio](img/oh_4_2_0123_linear_omicron.pdf)

![oh](img/oh_4_2_0123_linear_omicron.png)

### [Oklahoma](img/ok_4_2_0123_linear_omicron.pdf)

![ok](img/ok_4_2_0123_linear_omicron.png)

### [Oregon](img/or_4_2_0123_linear_omicron.pdf)

![or](img/or_4_2_0123_linear_omicron.png)

### [Pennsylvania](img/pa_4_2_0123_linear_omicron.pdf)

![pa](img/pa_4_2_0123_linear_omicron.png)

### [Puerto Rico](img/pr_4_2_0123_linear_omicron.pdf)

![pr](img/pr_4_2_0123_linear_omicron.png)

### [Rhode Island](img/ri_4_2_0123_linear_omicron.pdf)

![ri](img/ri_4_2_0123_linear_omicron.png)

### [South Carolina](img/sc_4_2_0123_linear_omicron.pdf)

![sc](img/sc_4_2_0123_linear_omicron.png)

### [South Dakota](img/sd_4_2_0123_linear_omicron.pdf)

![sd](img/sd_4_2_0123_linear_omicron.png)

### [Tennessee](img/tn_4_2_0123_linear_omicron.pdf)

![tn](img/tn_4_2_0123_linear_omicron.png)

### [Texas](img/tx_4_2_0123_linear_omicron.pdf)

![tx](img/tx_4_2_0123_linear_omicron.png)

### [Utah](img/ut_4_2_0123_linear_omicron.pdf)

![ut](img/ut_4_2_0123_linear_omicron.png)

### [Virginia](img/va_4_2_0123_linear_omicron.pdf)

![va](img/va_4_2_0123_linear_omicron.png)

### [Vermont](img/vt_4_2_0123_linear_omicron.pdf)

![vt](img/vt_4_2_0123_linear_omicron.png)

### [Washington](img/wa_4_2_0123_linear_omicron.pdf)

![wa](img/wa_4_2_0123_linear_omicron.png)

### [Wisconsin](img/wi_4_2_0123_linear_omicron.pdf)

![wi](img/wi_4_2_0123_linear_omicron.png)

### [West Virginia](img/wv_4_2_0123_linear_omicron.pdf)

![wv](img/wv_4_2_0123_linear_omicron.png)

### [Wyoming](img/wy_4_2_0123_linear_omicron.pdf)

![wy](img/wy_4_2_0123_linear_omicron.png)

## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, case rates and hospitalizations are expected to begin declining while deaths are forecast to grow.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)

## [return to case studies](../index.md)

