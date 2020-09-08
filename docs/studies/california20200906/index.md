## September 6, 2020 Analysis of California data (in age groups)

Early in the pandemic, homogeneous models were able to describe US state cases, hospitalizations, and deaths by a
set of transmission rates and delays that applied to the entire population.
Starting in May, the trajectories for hospitalizations and deaths started to diverge from
model predicitions, in which transmission rates were estimated from case data alone.
Growth in hospitalizations and deaths were 1-3% lower than the growth in cases.
This was attributed to be due to the fact that case growth was primarily coming from younger people, while
the hospitalization and death growth were reflecting growth in older people.

COVID-19 daily case and death data broken down by age group is available from California.
A study was performed to understand how to account for this effect in all states.
Surprisingly, the death data suggests much longer times from infection to death that was
found in the study of data from German states.

The following shows graphs of daily cases and deaths, for different age groups, compared with model fits.
The first transition date is fixed to the day found from a fit to state-wide data.
The other transition dates were fit for each age group.

### [Under 18](img/caunder18_2_3_0906.pdf)

No deaths are reported in this group.
This group had the largest growth rate during the lockdown phase.

![under18](img/caunder18_2_3_0906.png)


### [18-49](img/ca18to49_2_3_0906.pdf)

This group had the largest growth rate (about 4% per day) following relaxation of social distancing rules.
The other groups grew at 2.5%-3% per day.

![18-49](img/ca18to49_2_3_0906.png)


### [50-64](img/ca50to64_2_3_0906.pdf)


![50-64](img/ca50to64_2_3_0906.png)


### [65+](img/ca65plus_2_3_0906.pdf)


![65+](img/ca65plus_2_3_0906.png)


## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

group| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub> | day 3 | &delta;<sub>3</sub>  
---|---|---|---|---|---|---
0-17|24.3|27|4.3|65|3.3|132|-0.8
18-49|25.0 +/- 0.6|27|0.6 +/- 0.2|72|3.6 +/- 0.1|130|-1.3 +/- 0.1
50-64|25.3 +/- 1.3|27|0.0 +/- 0.3|80|3.2 +/- 0.1|131|-1.1 +/- 0.2
65+|25.3 +/- 1.3|27|-0.2 +/- 0.2|92|3.0 +/- 0.3|130|-0.7 +/- 0.1

* &delta;<sub>0</sub>: initial daily fractional growth parameter (in percent)
* day 1: days after March 1, 2020 when transmission rate changed


### Death fraction and time to death

group| death fraction (%) | mean death delay | death delay sigma
---|---|---
18-49|0.1 +/- 0.0|16.6 +/- 2.0|10.8 +/- 5.3
50-64|1.3 +/- 0.3|23.6 +/- 2.0|13.3 +/- 3.7
65+|9.6 +/- 1.2|24.3 +/- 2.7|19.4 +/- 3.6

* death fraction: fraction of those infected in this group who die. Note that the total number infected is not
well known, so this is only useful as a relative indicator.
* mean death delay: mean time between becoming infectious and death (days). These are similar to
the delays estimated from German state data (18.4 days).
* death delay sigma: also similar to values estimate from German state data (8.4 days)

## Infection status

The following plots summarize the infection history.
The upper plot shows the daily growth/decline from the fit. Bands show approximate 95% CL intervals.
The lower plot shows the size of the infection: the uncorrected circulating contagious population per
million.


### [Under 18](img/caunder18-summary.pdf)


![under18](img/caunder18-summary.png)


### [18-49](img/ca18to49-summary.pdf)


![18-49](img/ca18to49-summary.png)


### [50-64](img/ca50to64-summary.pdf)


![50-64](img/ca50to64-summary.png)


### [65+](img/ca65plus-summary.pdf)


![65+](img/ca65plus-summary.png)


## [return to case studies](../index.md)

