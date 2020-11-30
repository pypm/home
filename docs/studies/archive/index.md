## Archived Case studies

Click on the links in the titles below to see detailed results from the studies.
Note that these studies have been superceded by newer studies of the regions. These are kept for comparison.

### November 15, 2020: [USA by state](usa20201115/index.md)

This is an analysis prepared for the [COVID-19 Forecast Hub](https://covid19forecasthub.org/), in coordination with the US CDC.

Most states are showing rapid growth in cases and hospitalizations.
A summary of total US cases and deaths is shown along with a forecast that assumes no change to current practice.
The hospitalization data shown here is from The Covid Tracking Project. Later studies used US HHS data.

### July 19, 2020: [BC by health region](bc20200719/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.

The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case. Sundays do not have zero cases in these data.

All jusidictions see the same reporting anomaly the occured late April, all characterized by additional
cases reports spread over a period centered on around April 21 with the spread having standard
deviation of about 6 days.

Due to low case numbers, the uncertainties on the current growth estimates remain large.
Neither positive or negative growth can be ruled out.
Localized outbreaks in Vancouver Coastal and the Interior further complicate the growth estimates.
A transition was forced on day 80 to measure the effect of relaxing social distancing rules on that date.

### July 11, 2020: [9 provinces](prov20200711/index.md)

This is an update of the previous provincial analysis, using data from March 1 - July 10.

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

### July 8, 2020: [USA by state](usa20200708/index.md)

Almost all states are showing growth. To measure the effect of relaxed social distancing, a transition in the transmission rate was fixed
to May 23, the Memorial long weekend.
States generally show an infection trajectory
in the hospitalizations with &delta; reduced by about 3% compared to the case growth rate.
This may be evidence for difference in spread for different age groups.

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

### May 28, 2020: [9 provinces](prov20200528/index.md)

The most sensitive indicator to detect changes in the spread of the virus is the daily number cases.
As relaxation of social distancing rules start to take effect, there will be great interest in
determining whether the changes has significantly altered the transmission rate, and whether the
new transmission rate is large enough to lead to exponential growth again.
The ``pyPM.ca`` framework can help answer these questions.

The ``pyPM.ca`` reference model 2.2 is able to characterize the case histories in each Canadian province
from mid-March - May 28 with relatively few tuned parameters.
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

### May 25, 2020: [USA by state](usa20200525/index.md)

The most sensitive indicator to detect changes in the spread of the virus is the daily number cases.
As relaxation of social distancing rules start to take effect, there will be great interest in
determining whether the changes has significantly altered the transmission rate, and whether the
new transmission rate is large enough to lead to exponential growth again.

Many US states are currently experiencing exponential growth, or very close to growth.
Some of these states may see even faster growth as social distancing rules are relaxed.

### May 18, 2020: [BC health region](bc20200518/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.

The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case.

All jusidictions see the same reporting anomaly the occured late April, all characterized by additional
cases reports spread over a period centered on around April 21 with the spread having standard
deviation of about 6 days.

## [return to pyPM.ca Case studies](../)

## [return to pyPM.ca documentation home page](../../..)
