## November 3, 2020 Analysis of Canadian provincial data

All provinces except PEI (which has very few cases) are fit to the reference model 2.3.
Reporting anomalies are included for BC and Quebec.

The following shows graphs followed by tables.
To download a pdf version of a plot, click on the title.
The models and data used to produce these
are available through the [ipypm](../../ipypm) user interface.

### [BC](img/bcc_2_3_1103.pdf)

Daily case counts currently are at the highest level of the epidemic. Growth is currently about 4.5% per day.

Note that this data are from the uncorrected weekday reports.
A better analysis [here](../bc20201103) uses corrected data (including Saturday and Sunday numbers) and shows
the breakdowns by health region and age groups.
That data more clearly shows localized outbreaks in some of the regions, and those outbreaks are
included in the models used to fit that data.

![bcc](img/bcc_2_3_1103.png)

### [Alberta](img/ab_2_3_1103.pdf)

The data is fit with a model that includes 3 outbreaks in March/April (meat packing plants).
Only two parameters are used to characterize each outbreak: date and number of infections.
The data is consistent with each outbreaks taking place over a very short period of time.
The growth and decline in June/July is modelled by transitions in transmission rates.
The current growth rate is estimated to be about 2.6% per day.

The growth/decline trends in hospitalization show transitions that follow somewhat the rises
and falls predicted by the model (hospitalization parameters not adjusted).

![ab](img/ab_2_3_1103.png)

### [Saskatchewan](img/sk_2_3_1103.pdf)

Following initial rapid growth in mid-March and decline after lockdown measures,
there have been several outbreaks (some of these being in the far northern communities).
Peaks in hospitalization occur at roughly the expected times from the model (no adjustment of hospitalization parameters).
Throughout the period the general community transmission rate appears was low, until last few weeks where it has increased.
Current growth rate is about 5.3% per day.

![sk](img/sk_2_3_1103.png)

### [Manitoba](img/mb_2_3_1103.pdf)

Following initial rapid growth in mid-March and decline after lockdown measures,
community transmission appears to have remained low, until July.
The daily case rates grew in July at 5+/3 % per day, followed by decline in August and
rapid growth starting in mid-September, now at about 6% per day.

![mb](img/mb_2_3_1103.png)

### [Ontario](img/on_2_3_1103.pdf)

Community transmission declined enough by mid April to allow the infection rate to decline.
A reporting anomaly is added to the model for the broad bump in daily cases in May.
Transmission increased again starting in mid-August,
leading to growth in infections of about 5% per day.
The growth spurt has recently subsided to about 1.6% per day.

![on](img/on_2_3_1103.png)

### [Quebec](img/qc_2_5_1103.pdf)

Seven changes in transmission rate are necessary to fit the data.
A large backlog of case reports were released on May 3.
A significant reduction in transmission was seen starting on May 18.
Growth followed by decline was seen mid-June through mid-August.
Just as in Ontario, transmission starting in mid-August has led to growth in infections, but at 7% per day.
The growth spurt has recently subsided, and is currently consistent with being constant.

![qc](img/qc_2_5_1103.png)

### [New Brunswick](img/nb_2_3_1103.pdf)

The data is consistent with two changes in transmission rates and
outbreaks in late May (in Campbellton region) and August (Moncton/Fredricton) and early October.

![nb](img/nb_2_3_1103.png)

### [Newfoundland](img/nl_2_3_1103.pdf)

The data is consistent with two changes in transmission rate.

![nl](img/nl_2_3_1103.png)

### [Nova Scotia](img/ns_2_3_1103.pdf)

The data is consistent with three changes in transmission rates.

![ns](img/ns_2_3_1103.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

prov| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub> | day 3 | &delta;<sub>3</sub> | day 4 | &delta;<sub>4</sub> | day 5 | &delta;<sub>5</sub> | day 6 | &delta;<sub>6</sub> | day 7 | &delta;<sub>7</sub> 
---|---|---|---|---|---|---|---|---|---|---|---|---
bcc|19.5 +/- 4.3|16|-4.6 +/- 0.6|88|2.5 +/- 0.2|185|-1.1 +/- 0.4|217|4.4 +/- 0.3
ab|15.8 +/- 1.4|20|-6.9 +/- 0.5|83|3.2 +/- 0.2|142|-0.7 +/- 0.3|175|2.6 +/- 0.2
sk|22.5 +/- 2.9|19|-4.3 +/- 6.7|26|-5.1 +/- 0.9|180|5.3 +/- 0.6
mb|14.2 +/- 2.8|24|-9.6 +/- 3.8|59|2.2 +/- 0.7|130|7.9 +/- 0.5|168|-2.8 +/- 0.5|194|6.0 +/- 0.4
on|17.6 +/- 1.0|26|2.7 +/- 0.3|44|-2.1 +/- 0.3|80|-1.0 +/- 0.2|170|5.3 +/- 0.2|209|1.6 +/- 0.1
qc|27.4|23|1.2 +/- 0.2|55|-1.1 +/- 0.2|79|-7.2 +/- 0.2|106|2.3 +/- 0.2|143|-3.1 +/- 0.3|170|7.2 +/- 0.1|210|0.0 +/- 0.1
ns|23.0 +/- 1.0|21|3.7 +/- 1.6|44|-9.0 +/- 2.2|97|0.4 +/- 1.5

* bcc: fit results using data from daily reporting (no weekend reports, no corrections)
* &delta;<sub>0</sub>: initial daily fractional growth parameter (in percent)
* day 1: days after March 1, 2020 for first transmission rate changed
* &delta;<sub>1</sub>: daily fractional growth parameter after day 1 (in percent)

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

### [Saskatchewan](img/sk-summary.pdf)

![ab](img/sk-summary.png)

### [Manitoba](img/mb-summary.pdf)

![ab](img/mb-summary.png)

### [Ontario](img/on-summary.pdf)

![on](img/on-summary.png)

### [Quebec](img/qc-summary.pdf)

![qc](img/qc-summary.png)

### [Nova Scotia](img/ns-summary.pdf)

![ns](img/ns-summary.png)


## [return to case studies](../index.md)

