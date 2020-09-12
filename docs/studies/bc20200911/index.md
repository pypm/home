## September 11, 2020 Analysis of BC regional data

The following shows graphs of daily cases and cumulative cases.
A reporting anomaly is added to account for the change in testing policy in mid April.
Table shows the estimates for growth parameters, followed by graphical summaries.
Due to the low number of cases, there are large uncertainties for the current growth rates.
Outbreaks seen in Interior, Coastal, and Fraser regions and recently in age groups above 70 years.
Tables show the dates and numbers of infected individuals estimated from the model fits.

Cases from the Northern Health region are
not shown because there are very few cases reported.

### [BC total](img/bc_2_3_0911.pdf)

There has been localized outbreaks in Coastal, Interior, and Fraser regions (see below). A single outbreak is
included in the overall BC fit.

![bc](img/bc_2_3_0911.png)

### [Fraser](img/fraser_2_3_0911.pdf)

![fraser](img/fraser_2_3_0911.png)

### [Interior](img/interior_2_3_0911.pdf)

The spike in cases fit to have occured on day 121, is due to the Kelowna outbreak (attributed to Canada Day events).
A total of about 200 infections are injected in the model that day in order to fit the data.
A second, smaller, outbreak seen about 40 days later.

![interior](img/interior_2_3_0911.png)

### [Island](img/island_2_3_0911.pdf)

The small number of cases make it difficult to measure the growth rate.

![island](img/island_2_3_0911.png)

### [Coastal](img/coastal_2_3_0911.pdf)

Two outbreaks seen.

![coastal](img/coastal_2_3_0911.png)

## BC data broken down by age group

### [10-19](img/bc10_2_3_0911.pdf)

![10-19](img/bc10_2_3_0911.png)

### [20-29](img/bc20_2_3_0911.pdf)

![20-29](img/bc20_2_3_0911.png)

### [30-39](img/bc30_2_3_0911.pdf)

![30-19](img/bc30_2_3_0911.png)

### [40-49](img/bc40_2_3_0911.pdf)

![40-49](img/bc40_2_3_0911.png)

### [50-59](img/bc50_2_3_0911.pdf)

![50-59](img/bc50_2_3_0911.png)

### [60-69](img/bc60_2_3_0911.pdf)

![60-69](img/bc60_2_3_0911.png)

### [70-79](img/bc70_2_3_0911.pdf)

![70-79](img/bc70_2_3_0911.png)

### [80-89](img/bc80_2_3_0911.pdf)

![80-89](img/bc80_2_3_0911.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

HA| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub>
---|---|---|---|---|---
bc|0.106 +/- 0.011|18|-0.024 +/- 0.008|92|0.026 +/- 0.008
fraser|0.132 +/- 0.042|18|-0.012 +/- 0.016|106|0.020 +/- 0.011
coastal|0.086 +/- 0.013|18|-0.057 +/- 0.023|104|0.023 +/- 0.012
interior|0.195|18|-0.066
island|0.130 +/- 0.017|15|-0.065 +/- 0.028|80|0.030 +/- 0.011

* &delta;<sub>0</sub>: initial daily fractional growth parameter
* day 1: days after March 1, 2020 when transmission rate changed

Age| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub> 
---|---|---|---|---|---
10|0.106|18|0.003|92|0.027
20|0.106|18|-0.008|92|0.032
30|0.106|18|-0.027|92|0.036
40|0.106|18|-0.029|92|0.032
50|0.106|18|-0.032|92|0.026
60|0.106|18|-0.039|92|0.031
70|0.106|18|-0.032|92|0.009
80|0.106|18|-0.026|92|-0.003

* &delta;<sub>0</sub>, day 1: fixed to full BC fit

### Infection outbreaks

HA / age | day | number  | day | number  
---|---|---|---|---
bc|146|228.7
fraser|145|201.4
interior|127|193.3|168|41.5
coastal|92|53.5|152|247.6
70-79|159|26.5
80-89|159|12.2

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

