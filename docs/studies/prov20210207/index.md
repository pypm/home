## February 7, 2021 Analysis of Canadian provincial data

All provinces except PEI (which has very few cases) are fit to the reference model 2.8.
The plots show the trajectory of the epidemic since October 1.
The plots on the left show the daily case numbers (green points) and deaths (purple points) along with
the weekly averages (stars) on a log scale.
The plots on the right show the number of people in hospital on a linear scale.

The trajectory of hospitalization in several provinces departed from the expected trends at the beginning of December. 
This is in stark contrast to
the behaviour seen in most German and US states (posted in this area).

Forecasts for the coming month are provided, assuming no general change in behaviour.
For example, Ontario brought in additional measures into force on Dec 26, and a major change in the infection trajectory
followed.
The shaded regions show the 50%, 80%, and 95% CL intervals.

Forecasts from a previous analysis in January is compared with the most recent data.

### [BC](img/bcc_2_8_0207.pdf)

A better analysis [here](../bc20210119) uses corrected data (including Saturday and Sunday numbers) and shows
the breakdowns by health region.

![bc](img/bcc_2_8_0207.png)

### [Alberta](img/ab_2_8_0207.pdf)

![ab](img/ab_2_8_0207.png)

### [Saskatchewan](img/sk_2_8_0207.pdf)

![sk](img/sk_2_8_0207.png)

### [Manitoba](img/mb_2_8_0207.pdf)

![mb](img/mb_2_8_0207.png)

### [Ontario](img/on_2_8_0207.pdf)

![on](img/on_2_8_0207.png)

### [Quebec](img/qc_2_8_0207.pdf)

![qc](img/qc_2_8_0207.png)

### [New Brunswick](img/nb_2_8_0207.pdf)

![nb](img/nb_2_8_0207.png)

### [Newfoundland](img/nl_2_8_0207.pdf)

![nl](img/nl_2_8_0207.png)

### [Nova Scotia](img/ns_2_8_0207.pdf)

![ns](img/ns_2_8_0207.png)

## Tables

The tables below are results from the fits to reference model 2.6.

### Recent growth rates (&delta; : percent per day)

prov| &delta; | day | &delta; | day | &delta; | day | &delta;  
---|---|---|---|---|---|---
bcc| 0.1 +/-  0.3|Oct 11| 4.3 +/-  0.2|Nov 16|-1.7 +/-  0.2
ab| 1.9 +/-  0.3|Oct 04| 4.1 +/-  0.0|Nov 28|-1.6 +/-  0.1|Jan 11|-2.9 +/-  0.8
sk| 5.2 +/-  0.3|Nov 20| 0.3 +/-  0.2
mb| 5.7 +/-  0.2|Nov 07|-1.1 +/-  0.3
on| 5.2 +/-  0.3|Sep 26| 1.9 +/-  0.0|Jan 09|-3.7 +/-  2.2
qc| 7.3 +/-  0.6|Sep 27|-0.1 +/-  0.2|Nov 16| 2.3 +/-  0.1|Dec 31|-2.6 +/-  1.0
ns| 0.4 +/-  0.7|Oct 12| 7.5 +/-  3.6|Nov 16|-2.9 +/-  0.9

* bcc: fit results using data from daily reporting (no weekend reports, no corrections)
* &delta; : daily fractional growth parameter (in percent)
* day: day of transition to new transmission rate

## Infection status

The following plots summarize the infection history.
The upper plot shows the daily growth/decline from the fit. Bands show approximate 95% CL intervals.
The lower plot shows the size of the infection: the uncorrected circulating contagious population per
million.
Only regions with sufficient statistics to properly analyze uncertainty in &delta; are shown.

### [BC](img/bcc-summary.pdf)

![bc](img/bcc-summary.png)

### [Alberta](img/ab-summary.pdf)

![ab](img/ab-summary.png)

### [Saskatchewan](img/sk-summary.pdf)

![sk](img/sk-summary.png)

### [Manitoba](img/mb-summary.pdf)

![mb](img/mb-summary.png)

### [Ontario](img/on-summary.pdf)

![on](img/on-summary.png)

### [Quebec](img/qc-summary.pdf)

![qc](img/qc-summary.png)

### [Nova Scotia](img/ns-summary.pdf)

![ns](img/ns-summary.png)


## Forecasts

The following plots show the forecasts for weekly cases and deaths. The shaded regions show the 50%, 80%, and 95% CL intervals.

Also shown are the forecasts made on Jan 19, 2021.
For those plots, the recent data (not available at the time of the forecast) are overlayed as black stars.

### [Canada](img/canada-forecast.pdf)

![canada](img/canada-forecast.png)

### [BC](img/bc-forecast.pdf)

current forecast

![bc](img/bc-forecast.png)

Jan 19 forecast

![bc](img/bc-forecast-x.png)

### [Alberta](img/ab-forecast.pdf)

current forecast

![ab](img/ab-forecast.png)

Jan 19 forecast

![ab](img/ab-forecast-x.png)

### [Saskatchewan](img/sk-forecast.pdf)

current forecast

![sk](img/sk-forecast.png)

Jan 19 forecast

![sk](img/sk-forecast-x.png)

### [Manitoba](img/mb-forecast.pdf)

current forecast

![mb](img/mb-forecast.png)

Jan 19 forecast

![mb](img/mb-forecast-x.png)

### [Ontario](img/on-forecast.pdf)

current forecast

![on](img/on-forecast.png)

Jan 19 forecast

![on](img/on-forecast-x.png)

### [Quebec](img/qc-forecast.pdf)

current forecast

![qc](img/qc-forecast.png)

Jan 19 forecast

![qc](img/qc-forecast-x.png)


## [return to case studies](../index.md)

