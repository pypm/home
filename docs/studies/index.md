## Case studies

Click on the links in the titles below to see detailed reults from the studies.

### May 18, 2020: [9 provinces](prov20200518/index.md)

The most sensitive indicator to detect changes in the spread of the virus is the daily number cases.
As relaxation of social distancing rules start to take effect, there will be great interest in
determining whether the changes has significantly altered the transmission rate, and whether the
new transmission rate is large enough to lead to exponential growth again.
The ``pyPM.ca`` framework can help answer these questions.

The ``pyPM.ca`` reference model 2.1 is able to characterize the case histories in each Canadian province
from mid-March - May 18 with relatively few tuned parameters.
During the first part of March, testing policies were being developed
and fits do not include case numbers from that period.
Subsequent to that, there is no evidence in the case data that changes to test policies have
significantly changed the fraction of infected individuals getting a positive test result, at
least in the districts that are responsible for the majority of cases.
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

### May 18, 2020: [BC health region](bc20200518/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.

The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case.

All jusidictions see the same reporting anomaly the occured late April, all characterized by additional
cases reports spread over a period centered on around April 21 with the spread having standard
deviation of about 6 days.

### Forthcoming studies

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
transmission rates (corresponding to a fraction of R_0, or a multiple of R_now), and show
the expectations. Consider the effect of contact tracing (included in reference model 2.)

## [return to pyPM.ca documentation home page](../..)
