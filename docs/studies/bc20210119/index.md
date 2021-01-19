## January 19, 2021 Analysis of BC regional data

The following shows graphs of daily cases and cumulative cases. Data through January 17 are used,
with the plots starting on October 1.

Changes in social behaviours and other factors cause transmission rates to change from time to time.
The analysis estimates transition dates from the data.
The uncertain effective transition date results in additional uncertainty in estimating the transmission rate in each
block of time.
To account for this, the transition date is adjusted by +/- 2 days around the best fit date.
This process increases the interval quoted for the final growth rate substantially when a transition has occured recently.

Since December, several changes have been seen:
 * There was a significant outbreak in Vancouver Coastal occuring near Christmas.
 * Vancouver Island, Interior, and Northern health authorities are now showing growth. The most significant growth is in
 Vancouver Island Health Authority, showing 4 +/- 1% growth per day since Dec 7.

The points are daily cases, and the stars show weekly averages, to help guide the eye.

At the bottom, forecasts (with forecast intervals) for the coming 4 weeks are shown. As a comparison, the Dec 24 forecasts are compared
to the recent observations.

### [BC total](img/bc_2_3_0119.pdf)

![bc](img/bc_2_3_0119.png)

### [Fraser](img/fraser_2_3_0119.pdf)

![fraser](img/fraser_2_3_0119.png)

### [Interior](img/interior_2_3_0119.pdf)

![interior](img/interior_2_3_0119.png)

### [Island](img/island_2_3_0119.pdf)

![island](img/island_2_3_0119.png)

### [Coastal](img/coastal_2_3_0119.pdf)

![coastal](img/coastal_2_3_0119.png)

### [Northern](img/northern_2_3_0119.pdf)

![northern](img/northern_2_3_0119.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

HA| &delta; | day | &delta; | day | &delta; | day | &delta;
---|---|---|---|---|---|---|---
bc| 0.3 +/-  0.3|Oct 04| 5.1 +/-  0.1|Nov 11|-0.6 +/-  0.3
fraser| 4.5 +/-  0.2|Nov 13|-1.0 +/-  0.4
interior| 4.9 +/-  0.3|Dec 03|-3.8 +/-  0.6|Dec 16| 2.0 +/-  0.7
island| 0.5 +/-  0.5|Oct 21| 11.4 +/-  1.3|Nov 14|-4.6 +/-  0.6|Dec 07| 3.6 +/-  0.9
coastal|-0.6 +/-  0.4|Oct 15| 6.5 +/-  0.3|Nov 08|-1.2 +/-  0.4
northern|-4.4 +/-  1.7|Oct 07| 6.0 +/-  0.6|Nov 24| 1.3 +/-  0.4

* &delta;: daily fractional growth rate (in percent per day)
* day: dates when transmission rate changed - resulting in a change in growth rate

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

## Forecasts (current and from Dec 24)

The procedure used here to produce the BC forecast intervals has
been used in US forecasts for the past several months and coverage of those intervals have been reasonable.
The forecasts assume that no dramtic changes in policy or behaviour occur over the next several weeks.

In the figures below, the stars represent the weekly data,
the curves represent the model summary and forecast,
with the bands showing the 50%, 80%, and 95% intervals.

Also shown are the forecasts made on Dec 24, 2020.
For those plots, the recent data (not available at the time of the forecast) are overlayed as black stars.
The recent dramatic changes in growth rate in Vancouver Island and Northen and Interior regions are apparent.

### [BC total](img/bc-forecast.pdf)

current

![bc](img/bc-forecast.png)

Dec 24 forecast

![bc](img/bc-forecast-x.png)

### [Fraser](img/fraser-forecast.pdf)

current

![fraser](img/fraser-forecast.png)

Dec 24 forecast

![fraser](img/fraser-forecast-x.png)

### [Coastal](img/coastal-forecast.pdf)

current

![coastal](img/coastal-forecast.png)

Dec 24 forecast

![coastal](img/coastal-forecast-x.png)

### [Interior](img/interior-forecast.pdf)

current

![interior](img/interior-forecast.png)

Dec 24 forecast

![interior](img/interior-forecast-x.png)

### [Northern](img/northern-forecast.pdf)

current

![northern](img/northern-forecast.png)

Dec 24 forecast

![northern](img/northern-forecast-x.png)

### [Vancouver Island](img/island-forecast.pdf)

current

![island](img/island-forecast.png)

Dec 24 forecast

![island](img/island-forecast-x.png)

## [return to case studies](../index.md)

