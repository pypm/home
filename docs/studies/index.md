# Case studies and reports

## Reports

* Paper: [Characterizing the spread of CoViD-19](reports/Characterizing_spread.pdf), D. Karlen, July 13, 2020.
    * introduces the pypm framework and describes methods to define comparitive statistics with weak model dependence
    and estimate their uncertainties

* Presentation: [Characterizing the spread of CoViD-19](reports/pims_karlen20200622.pdf), D. Karlen, June 22, 2020.
    * presentation at the [CAIMS-PIMS Coronavirus Modelling Conference](https://www.pims.math.ca/scientific-event/200622-cpcmc)

## Case studies

Click on the titles below to see detailed results from the studies.

### Devember 8, 2020: [BC by health region](bc20201208/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.
The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case.

The province saw COVID-19 growth in all regions, in October, with the strongest growth in the two Vancouver
health regons.
At the beginning of November, new restrictions came into force in Vancouver, and the data now shows
a decline in transmission rate for Vancouver Coastal and Fraser Health regions, as well as a reduction for
Vancouver Island. The data does not indicate a significant reduction in growth rate for the Interior.

### December 6, 2020: [16 German states](germany20201206/index.md)

This study was prepared for inclusion in the [German forecast-hub](https://kitmetricslab.github.io/forecasthub/forecast), led
by  researchers at the Karlsruhe Institute of Technology and the Heidelberg Institute for Theoretical Studies.

Data is provided by [Robert Koch Institut](https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/dd4580c810204019a7b8eb3e0b329dd6_0) and [DIVI Intensivregister](https://www.divi.de/register/tagesreport).
The data has much less reporting variance than those from USA, making it a good basis for developing and evaluating models.

### December 2, 2020: [9 provinces](prov20201202/index.md)

This is an update of the previous provincial analysis, now using data from March 1 - December 1.

To characterize the observed case histories, it is necessary to include the following transitory
effects:
* changes to transmission rate: most notably starting in mid-March. For most provinces this is described
sufficiently by a single transition
* outbreaks: in Alberta and Saskatchewan large outbreaks have occured. These are accounted for by
injecting batches of new infections, sufficient to account for the effect observed in the case data
* reporting anomalies: Quebec released a large number of cases due to a backlog, and BC
reported a change in test reporting policy on April 21. These are accounted for by
injecting batches of additional positive test results.

### November 29, 2020: [USA by state](usa20201129/index.md)

This is the latest analysis prepared for the [COVID-19 Forecast Hub](https://covid19forecasthub.org/), in coordination with the US CDC.

Most states have been experiencing rapid growth in cases and hospitalizations, but many are showing a turn around that began
on about November 12.
A summary of total US cases and deaths is shown along with a forecast that assumes no change to current practice.

[![uc](usa_uc_2020-11-15.png)](usa_uc_2020-11-15.gif)

Click on the above image to see a time lapse animation of how COVID-19 spread through the USA. The colors indicate the
fraction of the population in each state who are contagious. The scale is logrithmic: a difference of 1 unit
corresponds to a factor of 10 in the contagious fraction. The above still image is the snapshot for November 15.

### November 22, 2020: [USA by state](usa_hhs_20201122/index.md)

This is a analysis that uses data on hospitalizations recently made available by the US HHS.
Prior to this analysis, hospitalization data from the Covid Tracking Project has been used.

### October 5, 2020: [California by age](california20201005/index.md)

California provides daily case, hospitalization, and death data by age group.
This provides useful data to study how to model a non-homogenous population.

### June 24, 2020: [Brazil states](brazil20200624/index.md)

An initial study of Brazil data: fitting to death data only.

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
