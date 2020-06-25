# Case studies and reports

## Reports

* Paper: [Characterizing the spread of CoViD-19](reports/Characterizing_the_spread_of_CoViD_19_20200621.pdf), D. Karlen, June 21, 2020.
    * introduces the pypm framework and describes methods to define comparitive statistics with weak model dependence
    and estimate their uncertainties

* Presentation: [Characterizing the spread of CoViD-19](reports/pims_karlen20200622.pdf), D. Karlen, June 22, 2020.
    * presentation at the [CAIMS-PIMS Coronavirus Modelling Conference](https://www.pims.math.ca/scientific-event/200622-cpcmc)

## Case studies

Click on the links in the titles below to see detailed results from the studies.

### June 24, 2020: [Brazil states](brazil20200624/index.md)

An initial study of Brazil data: fitting to death data only.

### June 20, 2020: [9 provinces](prov20200620/index.md)

This is an update of the previous provincial analysis, now using data from March 1 - June 19.

The ``pyPM.ca`` reference model 2.3 is used.
For provinces with sufficient data, estimates are provided
of new growth rates after relaxation measures.

During the first part of March, testing policies were not yet fixed
and fits do not include case numbers from that period.
The [data](https://resources-covid19canada.hub.arcgis.com/datasets/provincial-daily-totals)
is collected from daily reports from provinces by ESRI,
and data prior to April 28 was collected by the now defunct virihealth.com.

To characterize the observed case histories, it is necessary to include the following transitory
effects:
* changes to transmission rate: most notably starting in mid-March. For most provinces this is described
sufficiently by a single transition
* outbreaks: in Alberta and Saskatchewan large outbreaks have occured. These are accounted for by
injecting batches of new infections, sufficient to account for the effect observed in the case data
* reporting anomalies: Quebec released a large number of cases due to a backlog, and BC
reported a change in test reporting policy on April 21. These are accounted for by
injecting batches of additional positive test results.

The agreement between the model and the provincial case data is quite good, considering
the relatively small number of parameters used. Click on the link above to see the results.

### June 20, 2020: [BC health region](bc20200620/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.

The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case. Sundays do not have zero cases in these data.

All jusidictions see the same reporting anomaly the occured late April, all characterized by additional
cases reports spread over a period centered on around April 21 with the spread having standard
deviation of about 6 days.

Vancouver Coastal has an increase in cases in early June.

### June 17, 2020: [16 German states](germany20200617/index.md)

There is remarkable consistency across the 16 German states for data between March 1 and June 10.
The lockdown measures came into force on March 22 and the relaxation on May 6.
A transition on May 6 was forced to measure the new transmission rate after that date.
The growth and decline are very similar in each state, and there is no significant
increase in spread following May 6.

**Update June 20:** By including data through June 19, it appears that Berlin is experiencing
exponential growth, transition date: May 23.
The state of Saxony-Anhalt has also recently seen a rapid rise in new cases.
It is possible that these recent rises in cases
are due to localized outbreaks.

### June 17, 2020: [USA by state](usa20200617/index.md)

There are many states in the US which have relaxed their social distancing rules even though
case numbers were constant or growing.

To measure the effect of relaxed social distancing, a transition in the transmission rate was fixed
to May 23, the Memorial long weekend.
States with exponential growth on that day (&delta>0;) in case number show an infection trajectory
in the hospitalizations with &delta; reduced by about 3%.
This may be evidence for difference in spread for different age groups.

### Possible future studies

* Reporting noise, due to the process by which reports are collected, greatly affect the
variation seen in daily case numbers. These have strong negative correlation between neighboring
days (as missed reports and included in the subsequent day's reports).
A simple model for reporting noise is included in ``pyPM.ca``, with a single parameter.
Tests of the reporting noise model will be shown.

* Negative binomial parameter: It is common to not treat infections as independent events (which
would lead to treating the number of cases on a day as an outcome of a Poisson random variable).
Instead, it is common to use a negative binomial distribution.
The choice of the single additional parameter is studied.

* Projections for growth resulting from relaxation of social distancing. Choose some
modified transmission rates, show the expectations, and consider how much time is required to
detect changes for a given significance.

* Consider the effect of contact tracing (included in reference model 2.)

## [Archive of older studies](archive/index.md)

## [return to pyPM.ca documentation home page](../..)
