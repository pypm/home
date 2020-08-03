## August 3, 2020 Analysis of provincial data

All provinces except PEI (which has very few cases) are fit to the reference model 2.3.
Reporting anomalies are included for BC and Quebec.

The following shows graphs followed by tables.
To download a pdf version of a plot, click on the title.
The models and data used to produce these
are available through the [ipypm](../../ipypm) user interface.

### [BC](img/bcc_2_3_0803.pdf)

The data is consistent with a single transition in the transmission rate and about 300 cases
added in late April. The anomalous cases are seen in all health regions and are
due to a change in test/reporting policy.

![bcc](img/bcc_2_3_0803.png)

### [Alberta](img/ab_2_3_0803.pdf)

The data is consistent with one change in transmission rate in mid March and 3 separate
large outbreaks. These have been reported in the media to be due to meat packing plants.
The data is consistent with each outbreaks taking place over a very short period of time.
Only two parameters are used to characterize each outbreak: date and number of infections.
The shapes of the case (and contagious populations) are outcomes of the other model parameters
which were not tuned.

The hospitalization and death rates from these outbreaks appear to be smaller than the
cases from March.

There is again growth in cases starting around May 20. The additional cases are from the
Edmonton health region.

![ab](img/ab_2_3_0803.png)

### [Saskatchewan](img/sk_2_3_0803.pdf)

The data is consistent with two transitions in transmission rates, three outbreaks
(the first two from far northern communities).
The data suggests that the first outbreak took place over a period of about 10 days.
The second outbreak seen in the previous study (../archive/prov20200620) is confirmed.

![sk](img/sk_2_3_0803.png)

### [Manitoba](img/mb_2_3_0803.pdf)

The data is consistent with one change to the transmission rate.
Small deviations from exponential decline seen - used a reporting anomaly and an outbreak as
examples.

![mb](img/mb_2_3_0803.png)

### [Ontario](img/on_2_3_0803.pdf)

The data is consistent with 2 changes in tranmission rate. A third transition is added for May 19
to measure the new transmission rate.

![on](img/on_2_3_0803.png)

### [Quebec](img/qc_2_3_0803.pdf)

Four changes in transmission rate are necessary to fit the data.
A large backlog of case reports were released on May 3.
A significant reduction in transmission in May.
The best fit for the transition date is May 18.
A fifth transition in transmission rate was added and
the growth parameter has increased significantly.

![qc](img/qc_2_3_0803.png)

### [New Brunswick](img/nb_2_3_0803.pdf)

The data is consistent with two changes in transmission rates and
outbreaks in late May (in Campbellton region).

![nb](img/nb_2_3_0803.png)

### [Newfoundland](img/nl_2_3_0803.pdf)

The data is consistent with one change in transmission rate.

![nl](img/nl_2_3_0803.png)

### [Nova Scotia](img/ns_2_3_0803.pdf)

The data is consistent with two changes in transmission rates.

![ns](img/ns_2_3_0803.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

prov| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub> | day 3 | &delta;<sub>3</sub> | day 4 | &delta;<sub>4</sub> | day 5 | &delta;<sub>5</sub> 
---|---|---|---|---|---|---|---|---|---|---|---
bcc|0.188 +/- 0.047|16|-0.041 +/- 0.006|80|-0.007 +/- 0.020
ab|0.158 +/- 0.014|20|-0.070 +/- 0.006|81|0.025 +/- 0.013
on|0.178 +/- 0.009|26|0.026 +/- 0.004|44|-0.019 +/- 0.003|80|-0.012 +/- 0.006
qc|0.275 +/- 0.010|22|0.035 +/- 0.010|30|0.011 +/- 0.002|55|-0.012 +/- 0.002|79|-0.069 +/- 0.003|106|0.009 +/- 0.008
ns|0.232 +/- 0.041|21|0.036 +/- 0.014|44|-0.090 +/- 0.023

* &delta;<sub>0</sub>: initial daily fractional growth parameter
* day 1: days after March 1, 2020 when transmission rate changed

## Infection status

The following plots summarize the infection history.
The upper plot shows the daily growth/decline from the fit. Bands show approximate 95% CL intervals.
The lower plot shows the size of the infection: the uncorrected circulating contagious population per
million.
Only regions with sufficient statistics to properly analyze uncertainty in &delta; are shown.


### [BC](img/bcc-summary.pdf)

![bcc](img/bcc-summary.png)

### [Alberta](img/ab-summary.pdf)

![ab](img/ab-summary.png)

### [Ontario](img/on-summary.pdf)

![on](img/on-summary.png)

### [Quebec](img/qc-summary.pdf)

![qc](img/qc-summary.png)

### [Nova Scotia](img/ns-summary.pdf)

![ns](img/ns-summary.png)


## [return to case studies](../index.md)

