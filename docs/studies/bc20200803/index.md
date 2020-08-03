## August 3, 2020 Analysis of BC regional data

The following shows graphs of daily cases and cumulative cases.
A reporting anomaly is added to account for the change in testing policy in mid April.
Table shows the estimates for growth parameters, followed by graphical summaries.
Due to the low number of cases, there are large uncertainties for the current growth rates.
An outbreak in Kelowna has generated a spike in cases ine the Interior health region.

Cases from the Northern Health region are
not shown because there are very few cases reported.

### [BC total](img/bc_2_3_0803.pdf)

There has been two localized outbreaks since day 100: Coastal and Interior (see below). These cases are
not treated as localized outbreaks in the overall BC fit. The estimated daily growth rate is larger
than would be found if the localized outbreaks were modelled as such.

![bc](img/bc_2_3_0803.png)

### [Fraser](img/fraser_2_3_0803.pdf)

![fraser](img/fraser_2_3_0803.png)

### [Interior](img/interior_2_3_0803.pdf)

The spike in cases fit to have occured on day 121, is due to the Kelowna outbreak (attributed to Canada Day events).
It is difficult to estimate the size of the outbreak until the case numbers are seen to fall again.

![interior](img/interior_2_3_0803.png)

### [Island](img/island_2_3_0803.pdf)

The small number of cases make it difficult to measure the growth rate.

![island](img/island_2_3_0803.png)

### [Coastal](img/coastal_2_3_0803.png)

A small localized outbreak appeared in mid June.

![coastal](img/coastal_2_3_0803.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

HA| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub> 
---|---|---|---|---|---
bc|0.102 +/- 0.017|18|-0.028 +/- 0.005|85|0.023 +/- 0.010
fraser|0.131 +/- 0.037|18|-0.012 +/- 0.010|108|0.024 +/- 0.033
interior|0.195|18|-0.064|70|-0.045
island|0.127 +/- 0.016|15|-0.062 +/- 0.020|80|0.027 +/- 0.018
coastal|0.086 +/- 0.016|18|-0.056 +/- 0.015|104|-0.003 +/- 0.023

* &delta;<sub>0</sub>: initial daily fractional growth parameter
* day 1: days after March 1, 2020 when transmission rate changed


## Infection status

The following plots summarize the infection history.
The upper plot shows the daily growth/decline from the fit. Bands show approximate 95% CL intervals.
The lower plot shows the size of the infection: the uncorrected circulating contagious population per
million.

### [BC total](img/bc-summary.pdf)

![bc](img/bc-summary.png)

### [Fraser](img/fraser-summary.pdf)

![fraser](img/fraser-summary.png)

### [Coastal](img/coastal-summary.pdf)

![coastal](img/coastal-summary.png)

### [Vancouver Island](img/island-summary.pdf)

![island](img/island-summary.png)


## [return to case studies](../index.md)
