## September 29, 2020 Analysis of BC regional data

The following shows graphs of daily cases and cumulative cases.
A reporting anomaly is added to account for the change in testing policy in mid April.
Table shows the estimates for growth parameters, followed by graphical summaries.
Due to the low number of cases, there are large uncertainties for the current growth rates.
Outbreaks seen in Interior, Coastal, and Fraser regions and recently in age groups above 70 years.
Tables show the dates and numbers of infected individuals estimated from the model fits.

Cases from the Northern Health region are
not shown because there are very few cases reported.

### [BC total](img/bc_2_3_0929.pdf)

There has been localized outbreaks in Coastal, Interior, and Fraser regions (see below). A single outbreak is
included in the overall BC fit.

![bc](img/bc_2_3_0929.png)

### [Fraser](img/fraser_2_3_0929.pdf)

![fraser](img/fraser_2_3_0929.png)

### [Interior](img/interior_2_3_0929.pdf)

The spike in cases fit to have occured on day 121, is due to the Kelowna outbreak (attributed to Canada Day events).
A total of about 200 infections are injected in the model that day in order to fit the data.
A second, smaller, outbreak seen about 40 days later.

![interior](img/interior_2_3_0929.png)

### [Island](img/island_2_3_0929.pdf)

The small number of cases make it difficult to measure the growth rate.

![island](img/island_2_3_0929.png)

### [Coastal](img/coastal_2_3_0929.pdf)

Two outbreaks seen.

![coastal](img/coastal_2_3_0929.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

HA| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub>
---|---|---|---|---|---
bc|0.106 +/- 0.011|18|-0.025 +/- 0.007|92|0.030 +/- 0.005|180|0.002 +/- 0.010
fraser|0.132 +/- 0.042|18|-0.012 +/- 0.012|106|0.019 +/- 0.007|185|0.004 +/- 0.018
interior|0.195|18|-0.054
island|0.130 +/- 0.017|15|-0.054 +/- 0.015|80|0.008 +/- 0.007
coastal|0.086 +/- 0.024|18|-0.056 +/- 0.015|104|0.026 +/- 0.007|190|-0.024 +/- 0.018

* &delta;<sub>0</sub>: initial daily fractional growth parameter
* day 1: days after March 1, 2020 when transmission rate changed

### Infection outbreaks

HA / age | day | number  | day | number  
---|---|---|---|---
bc|156|125.2
fraser|145|210.6
interior|127|180.1|182|77.7
island|145|10.4
coastal|92|49.8|152|234.8

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

