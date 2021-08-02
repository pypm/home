# Case studies and reports

## Reports

* Paper: [Characterizing the spread of CoViD-19](reports/Characterizing_spread.pdf), D. Karlen, July 13, 2020.
    * introduces the pypm framework and describes methods to define comparitive statistics with weak model dependence
    and estimate their uncertainties

## Case studies

Click on the titles below to see detailed results from the studies.

### August 1, 2021: [USA by state](usa20210801/index.md)

#### July 25, 2021: [USA by state](usa20210725/index.md) - for comparison
#### April 18, 2021: [USA by state](usa20210418/index.md) - for comparison
#### March 21, 2021: [USA by state](usa20210321/index.md) - for comparison

These show results from analyses prepared for
the [COVID-19 Forecast Hub](https://covid19forecasthub.org/), in coordination with the US CDC.

The model fits include separate infection cycles for the B.1.1.7 and B.1.617.2 variants and
takes into account the vaccination rates in each state.

### July 29, 2021: [5 provinces](prov20210729/index.md)

Model fits to data from Alberta, Saskatchewan, Manitoba, Ontario and Quebec are shown.
Two additional infection cycles are included in the models to represent the variants of concern alpha and delta.
Case rates are no longer following a steady decline, possibly indicating a transition to rapid growth as
seen in Europe and US states (see EU and USA model analyses on this page)

### July 26, 2021: [BC by health region](bc20210726/index.md)

The first signs that the long period of declining cases is transitioning to potentially rapid growth are shown.
The pattern follows what has been seen in Europe and US states (see EU and USA model analyses on this page).

### July 25, 2021: [29 EU nations](eu20210725/index.md)

This study was prepared for inclusion in the [European forecast-hub](https://covid19forecasthub.eu/index.html),
coordinated by the European Centre for Disease Prevention and Control.

The model fits include separate infection cycles for the B.1.1.7 and B.1.617.2 variants and
takes into account the vaccination rates in each country.

### July 4, 2021: [16 German states](germany20210704/index.md)

This study was prepared for inclusion in the [German forecast-hub](https://kitmetricslab.github.io/forecasthub/forecast), led
by  researchers at the Karlsruhe Institute of Technology and the Heidelberg Institute for Theoretical Studies.

The model fits include separate infection cycles for the B.1.1.7 and B.1.617.2 variants and
takes into account the vaccination rates in each state.

### May 28, 2021: [BC by health region](bc20210528/index.md)

Variants of concern are responsible for most cases in BC, and following the "circuit breaker",
all regions of BC saw case rates decline.
Those restrictions were relaxed at the end of May.

This study includes, for the first time, the possible effects of B.1.617.2, a variant of concern that
has a significant growth advantage over the currently dominant strain, B.1.1.7.

### March 24, 2021: [BC by health region](bc20210324/index.md)

The B.1.1.7 variant is likely responsible for the recent growth in daily cases across BC.

The province does not make public the data necessary to estimate the critical parameters for B.1.1.7 in the province, so
useful forecasts cannot be provided at this time.

This study illustrates possible levels of B.1.1.7 and growth advantage, to give an indication how quickly the situation
could change.

### March 9, 2021: [BC by health region](bc20210309/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.
The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case.

In October the province saw COVID-19 growth in all regions with the strongest growth in the two Vancouver
health regons.
At the beginning of November, new restrictions came into force in Vancouver, which reduced the rate of growth.

The Fraser Health region had see declining daily cases, since mid-November, unlike the other regions
which had steady or growing case numbers.
Starting in January, cases started growing again in the Fraser HA, at about 2 % per day.
Only the Interior region is showing significant decline.

Forecasts for the next 4 weeks are provided. Comparisons of recent data
and a forecast from last month are shown.

### February 5, 2021: [Israel during vaccine deployment](https://nbviewer.jupyter.org/github/pypm/quickstart/blob/master/misc/israel_vaccination_study_20210204/israel_20210204.ipynb)

Israel currently has the highest rate of vaccinations per capita, with more than 40% of the population having received their first dose by early February.
The case and vaccination time-series data from Israel are analyzed and
amongst the older population, being nearly 90% vaccinated, the decline
in cases is consistent with expectations from vaccination immunity.

This represents the first quantitative demonstration of the herd-effect to COVID-19 at a national scale.

### November 22, 2020: [USA by state](usa_hhs_20201122/index.md)

This is a analysis that uses data on hospitalizations recently made available by the US HHS.
Prior to this analysis, hospitalization data from the Covid Tracking Project has been used.

### October 5, 2020: [California by age](california20201005/index.md)

California provides daily case, hospitalization, and death data by age group.
This provides useful data to study how to model a non-homogenous population.

### June 24, 2020: [Brazil states](brazil20200624/index.md)

An initial study of Brazil data: fitting to death data only.

## [Archive of older studies](archive/index.md)

## [return to pyPM.ca documentation home page](../..)
