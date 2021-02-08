# Case studies and reports

## Reports

* Paper: [Characterizing the spread of CoViD-19](reports/Characterizing_spread.pdf), D. Karlen, July 13, 2020.
    * introduces the pypm framework and describes methods to define comparitive statistics with weak model dependence
    and estimate their uncertainties

* Presentation: [Characterizing the spread of CoViD-19](reports/pims_karlen20200622.pdf), D. Karlen, June 22, 2020.
    * presentation at the [CAIMS-PIMS Coronavirus Modelling Conference](https://www.pims.math.ca/scientific-event/200622-cpcmc)

## Case studies

Click on the titles below to see detailed results from the studies.

### February 7, 2021: [9 provinces](prov20210207/index.md)

This is an update of the previous Canadian provincial analyses,
now using data from March 1, 2020 - February 6, 2021.
The report includes forecasts for the upcoming 4 weeks.

### February 5, 2021: [Israel during vaccine deployment](https://github.com/pypm/quickstart/blob/master/misc/israel_vaccination_study_20210204/israel_20210204.ipynb)

Israel currently has the highest rate of vaccinations per capita, with more than 40% of the population having received their first dose by early February.
The case and vaccination time-series data from Israel are analyzed and
amongst the older population, being nearly 90% vaccinated, the decline
in cases is consistent with expectations from vaccination immunity.

This represents the first quantitative demonstration of herd-immunity to COVID-19 at a national scale.

### February 2, 2021: [BC by health region](bc20210202/index.md)

The BC government makes [available](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data)
the number of cases each day, divided into sex, age, and health region.
The data differs somewhat from that used in the Canada-wide studies, possibly due to corrections in
the dates assigned to each positive case.

In October the province saw COVID-19 growth in all regions with the strongest growth in the two Vancouver
health regons.
At the beginning of November, new restrictions came into force in Vancouver, which reduced growth rates.
The data currently show a steady decline in cases in the Fraser Health region but
show positive growth for all other, regions: Vancouver Island, Coastal, Interior, and Northern.

In the past, the two Vancouver health regions have had larger growth rates than the other regions.
Currently, Vancouver Island is the region with the highest growth rate.

Forecasts for the next 4 weeks are provided. Comparisons of observations and a forecast from last month are shown.

### January 24, 2021: [USA by state](usa20210124/index.md)

This is the latest analysis prepared for
the [COVID-19 Forecast Hub](https://covid19forecasthub.org/), in coordination with the US CDC.

Overall the US forecasts show decline. Vaccination and new variants are not included in these analyses.

[![uc](usa_uc_2020-11-15.png)](usa_uc_2020-11-15.gif)

Click on the above image to see a time lapse animation of how COVID-19 spread through the USA. The colors indicate the
fraction of the population in each state who are contagious. The scale is logrithmic: a difference of 1 unit
corresponds to a factor of 10 in the contagious fraction. The above still image is the snapshot for November 15.

### January 17, 2021: [16 German states](germany20210117/index.md)

This study was prepared for inclusion in the [German forecast-hub](https://kitmetricslab.github.io/forecasthub/forecast), led
by  researchers at the Karlsruhe Institute of Technology and the Heidelberg Institute for Theoretical Studies.

Data is provided by [Robert Koch Institut](https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/dd4580c810204019a7b8eb3e0b329dd6_0) and [DIVI Intensivregister](https://www.divi.de/register/tagesreport).
The analysis was made complicated by new lockdown measures instituted in mid-December along with reporting issues over the Christmas holiday
period.

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
