## December 2, 2020 Analysis of Canadian provincial data

All provinces except PEI (which has very few cases) are fit to the reference model 2.3.

The following shows graphs followed by tables.
To download a pdf version of a plot, click on the title.
The models and data used to produce these
are available through the [ipypm](../../ipypm) user interface.

Most plots start on August 1 and run through mid-December.

### BC

The trajectory in BC appears to have turned over recently, requiring accurate recent data.
A better analysis [here](../bc20201201) uses corrected data (including Saturday and Sunday numbers) and shows
the breakdowns by health region and age groups.

### [Alberta](img/ab_2_3_1202.pdf)

The data is fit with a model that includes 3 outbreaks in March/April (meat packing plants).
Only two parameters are used to characterize each outbreak: date and number of infections.
The data is consistent with each outbreaks taking place over a very short period of time.
The growth and decline in June/July is modelled by transitions in transmission rates.
The current growth rate is estimated to be about 4.2% per day.

The growth/decline trends in hospitalization show transitions that follow somewhat the rises
and falls predicted by the model (hospitalization parameters not adjusted).

![ab](img/ab_2_3_1202.png)

### [Saskatchewan](img/sk_2_3_1202.pdf)

Following initial rapid growth in mid-March and decline after lockdown measures,
there have been several outbreaks (some of these being in the far northern communities).
Peaks in hospitalization occur at roughly the expected times from the model (no adjustment of hospitalization parameters).
Throughout the period the general community transmission rate appears was low, until last few weeks where it has increased.
Current growth rate is about 5.1% per day.

![sk](img/sk_2_3_1202.png)

### [Manitoba](img/mb_2_3_1202.pdf)

Following initial rapid growth in mid-March and decline after lockdown measures,
community transmission appears to have remained low, until July.
The daily case rates grew in July at 5+/3 % per day, followed by decline in August and
rapid growth starting in mid-September, at about 6% per day.
The growth rate appears to have reduced significantly recently.

![mb](img/mb_2_3_1202.png)

### [Ontario](img/on_2_3_1202.pdf)

Community transmission declined enough by mid April to allow the infection rate to decline.
A reporting anomaly is added to the model for the broad bump in daily cases in May.
Transmission increased again starting in mid-August,
leading to growth in infections of about 5% per day.
The growth spurt subsided to its current level of about 2.0% per day.

![on](img/on_2_3_1202.png)

### [Quebec](img/qc_2_5_1202.pdf)

Seven changes in transmission rate are necessary to fit the data.
A large backlog of case reports were released on May 3.
A significant reduction in transmission was seen starting on May 18.
Growth followed by decline was seen mid-June through mid-August.
Just as in Ontario, transmission starting in mid-August has led to growth in infections, but at 7% per day.
The growth spurt has recently subsided, and is currently consistent with being constant.

![qc](img/qc_2_5_1202.png)

### [New Brunswick](img/nb_2_5_1202.pdf)

The data is consistent with two changes in transmission rates and
several outbreaks.

![nb](img/nb_2_5_1202.png)

### [Newfoundland](img/nl_2_3_1202.pdf)

The data is consistent with two changes in transmission rate.

![nl](img/nl_2_3_1202.png)

### [Nova Scotia](img/ns_2_3_1202.pdf)

The data is consistent with three changes in transmission rates. Currently undergrowing significant growth in cases.


![ns](img/ns_2_3_1202.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

prov| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub> | day 3 | &delta;<sub>3</sub> | day 4 | &delta;<sub>4</sub> | day 5 | &delta;<sub>5</sub> | day 6 | &delta;<sub>6</sub> | day 7 | &delta;<sub>7</sub> 
---|---|---|---|---|---|---|---|---|---|---|---|---
ab|15.8 +/- 1.4|20|-7.0 +/- 0.4|83|3.4 +/- 0.4|142|-2.8 +/- 0.6|157|1.9 +/- 0.2|217|4.2 +/- 0.1
sk|22.5 +/- 2.9|19|-5.7 +/- 10.7|26|-4.6 +/- 1.2|180|5.1 +/- 0.3
mb|14.2 +/- 2.8|24|-9.3 +/- 0.9|59|2.0 +/- 0.4|130|8.3 +/- 0.6|168|-3.3 +/- 0.5|194|6.2 +/- 0.1|245|0.8 +/- 0.1
on|17.6 +/- 1.0|26|2.6 +/- 0.3|44|-1.8 +/- 0.2|80|-1.2 +/- 0.2|170|6.0 +/- 0.3|202|2.0 +/- 0.1
qc|27.4|23|1.2 +/- 0.1|55|-1.1 +/- 0.1|79|-7.2 +/- 0.2|106|2.3 +/- 0.2|143|-3.0 +/- 0.5|170|7.1 +/- 0.2|210|0.1 +/- 0.1
ns|23.0 +/- 1.0|21|3.6 +/- 2.1|44|-9.0 +/- 1.3|97|0.3 +/- 0.5|225|8.9 +/- 2.6

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

