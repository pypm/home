## January 19, 2021 Analysis of Canadian provincial data

All provinces except PEI (which has very few cases) are fit to the reference model 2.6.
The plots show the trajectory of the epidemic since October 1.
The plots on the left show the daily case numbers (green points) and deaths (purple points) along with
the weekly averages (stars) on a log scale.
The plots on the right show the number of people in hospital on a linear scale.

The trajectory of hospitalization in Alberta continued to grow for several weekas after the daily cases started to diminish,
not following the typical behaviour seen in many US states.

Forecasts for the coming month are provided, assuming no general change in behaviour.
Ontario brought in additional measures into force on Dec 26, which may substantially change its trajectory.
A transition has not been added to account for that possibility.
The shaded regions show the 50%, 80%, and 95% CL intervals.

Forecasts from a previous analysis in December, is compared with the most recent data.

### [BC](img/bcc_2_6_0119.pdf)

A better analysis [here](../bc20210119) uses corrected data (including Saturday and Sunday numbers) and shows
the breakdowns by health region.

![bc](img/bcc_2_6_0119.png)

### [Alberta](img/ab_2_6_0119.pdf)

![ab](img/ab_2_6_0119.png)

### [Saskatchewan](img/sk_2_6_0119.pdf)

![sk](img/sk_2_6_0119.png)

### [Manitoba](img/mb_2_6_0119.pdf)

![mb](img/mb_2_6_0119.png)

### [Ontario](img/on_2_6_0119.pdf)

![on](img/on_2_6_0119.png)

### [Quebec](img/qc_2_6_0119.pdf)

![qc](img/qc_2_6_0119.png)

### [New Brunswick](img/nb_2_6_0119.pdf)

![nb](img/nb_2_6_0119.png)

### [Newfoundland](img/nl_2_6_0119.pdf)

![nl](img/nl_2_6_0119.png)

### [Nova Scotia](img/ns_2_6_0119.pdf)

![ns](img/ns_2_6_0119.png)

## Tables

The tables below are results from the fits to reference model 2.6.

### Recent growth rates (&delta; : percent per day)

prov| &delta; | day | &delta; | day | &delta; | day | &delta;  
---|---|---|---|---|---|---
bcc|-0.0 +/-  0.2|Oct 11| 4.5 +/-  0.2|Nov 16|-1.8 +/-  0.3
ab| 1.8 +/-  0.2|Oct 04| 4.2 +/-  0.1|Nov 26|-1.3 +/-  0.5
sk| 5.3 +/-  0.2|Nov 22|-1.6 +/-  0.2|Dec 19| 3.1 +/-  1.0
mb| 5.9 +/-  0.2|Nov 07|-1.4 +/-  0.3
on| 5.2 +/-  0.2|Sep 26| 1.9 +/-  0.1
qc| 7.1 +/-  0.4|Sep 27| 0.1 +/-  0.2|Nov 16| 2.1 +/-  0.4
ns| 0.4 +/-  0.7|Oct 12| 7.5 +/-  3.5|Nov 16|-3.3 +/-  0.9

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

Also shown are the forecasts made on Dec 24, 2020.
For those plots, the recent data (not available at the time of the forecast) are overlayed as black stars.

### [Canada](img/canada-forecast.pdf)

![canada](img/canada-forecast.png)

### [BC](img/bc-forecast.pdf)

current forecast

![bc](img/bc-forecast.png)

Dec 24 forecast

![bc](img/bc-forecast-x.png)

### [Alberta](img/ab-forecast.pdf)

current forecast

![ab](img/ab-forecast.png)

Dec 24 forecast

![ab](img/ab-forecast-x.png)

### [Saskatchewan](img/sk-forecast.pdf)

current forecast

![sk](img/sk-forecast.png)

Dec 24 forecast

![sk](img/sk-forecast-x.png)

### [Manitoba](img/mb-forecast.pdf)

current forecast

![mb](img/mb-forecast.png)

Dec 24 forecast

![mb](img/mb-forecast-x.png)

### [Ontario](img/on-forecast.pdf)

current forecast

![on](img/on-forecast.png)

Dec 24 forecast

![on](img/on-forecast-x.png)

### [Quebec](img/qc-forecast.pdf)

current forecast

![qc](img/qc-forecast.png)

Dec 24 forecast

![qc](img/qc-forecast-x.png)


## [return to case studies](../index.md)

