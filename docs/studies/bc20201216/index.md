## December 16, 2020 Analysis of BC regional data

The following shows graphs of daily cases and cumulative cases. Data through December 15 are used,
with the plots starting on June 1.
In early November, new restrictions came into force for the Fraser and Vancouver Coastal health regions.

This analysis lets the fit determine the transition date from the data.
The uncertain effective transition date results in additional uncertainty in estimating the transmission rate.
To account for this, the transition date is adjusted by +/- 2 days around the best fit date.
This process increases the interval quoted for the final growth rate substantially.

Growth continues in the Interior and Northern regions.

The points are daily cases, and the stars show weekly average, to help guide the eye.

At the bottom, forecasts (with forecast intervals) for the coming 4 weeks are shown. 

### [BC total](img/bc_2_3_1216.pdf)

![bc](img/bc_2_3_1216.png)

### [Fraser](img/fraser_2_3_1216.pdf)

![fraser](img/fraser_2_3_1216.png)

### [Interior](img/interior_2_3_1216.pdf)

![interior](img/interior_2_3_1216.png)

### [Island](img/island_2_3_1216.pdf)

![island](img/island_2_3_1216.png)

### [Coastal](img/coastal_2_3_1216.pdf)

![coastal](img/coastal_2_3_1216.png)

### [Northern](img/northern_2_3_1216.pdf)

![northern](img/northern_2_3_1216.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

HA| &delta | day | &delta; | day | &delta; | day | &delta;
---|---|---|---|---|---|---|---
bc| 3.0 +/-  0.5|Aug 28| 0.4 +/-  0.3|Oct 04| 4.7 +/-  0.2|Nov 13|-0.3 +/-  0.9
fraser| 3.6 +/-  0.6|Aug 23|-1.8 +/-  0.9|Sep 13| 4.4 +/-  0.2|Nov 14|-0.6 +/-  1.1
interior|-4.5 +/-  0.9|Aug 28| 4.6 +/-  0.2
island| 0.6 +/-  0.4|Oct 21| 10.6 +/-  1.5|Nov 14|-3.2 +/-  2.3
coastal| 2.1 +/-  0.5|Sep 07|-0.6 +/-  0.3|Oct 15| 6.1 +/-  0.4|Nov 09|-1.3 +/-  0.9
northern|-2.9 +/-  0.5|Jul 19| 3.8 +/-  0.9|Sep 09|-3.6 +/-  1.4|Oct 07| 5.3 +/-  0.4

* &delta;: daily fractional growth parameter (in percent)
* day: dates when transmission rate changed

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

### [Interior](img/interior-summary.pdf)

![interior](img/interior-summary.png)

### [Northern](img/northern-summary.pdf)

![northern](img/northern-summary.png)

### [Vancouver Island](img/island-summary.pdf)

![island](img/island-summary.png)

## Forecasts

The procedure used here to produce the BC forecast intervals has
been used in US forecasts for the past several months and coverage of those intervals have been reasonable.
The forecasts assume that no dramtic changes in policy or behaviour occur over the next several weeks.
With the holiday period this may not be a valid assumption.

In the figures below, the stars represent the weekly data,
the curves represent the model summary and forecast,
with the bands showing the 50%, 80%, and 95% intervals.

### [BC total](img/bc-forecast.pdf)

![bc](img/bc-forecast.png)

### [Fraser](img/fraser-forecast.pdf)

![fraser](img/fraser-forecast.png)

### [Coastal](img/coastal-forecast.pdf)

![coastal](img/coastal-forecast.png)

### [Interior](img/interior-forecast.pdf)

![interior](img/interior-forecast.png)

### [Northern](img/northern-forecast.pdf)

![northern](img/northern-forecast.png)

### [Vancouver Island](img/island-forecast.pdf)

![island](img/island-forecast.png)

## [return to case studies](../index.md)

