## December 8, 2020 Analysis of BC regional data

The following shows graphs of daily cases and cumulative cases. Data through November 29 are used,
with the plots starting on August 1.
In early November, new restrictions came into force for the Fraser and Vancouver Coastal health regions.
The analysis fixes a transition to occur on Nov 8 for those to regions.

The transition in transmission rate for Vancouver Island is found to be around November 11.
Growth continues in the Interior.

The points are daily cases, and the stars show weekly average, to help guide the eye.

### [BC total](img/bc_2_3_1208.pdf)

![bc](img/bc_2_3_1208.png)

### [Fraser](img/fraser_2_3_1208.pdf)

![fraser](img/fraser_2_3_1208.png)

### [Interior](img/interior_2_3_1208.pdf)

![interior](img/interior_2_3_1208.png)

### [Island](img/island_2_3_1208.pdf)

The small number of cases make it difficult to measure the growth rate.
There was significant growth in October-November, but has diminished significantly
due to a reduced transmission rate starting around Nov 11.

![island](img/island_2_3_1208.png)

### [Coastal](img/coastal_2_3_1208.pdf)

![coastal](img/coastal_2_3_1208.png)

## Tables

The tables below are results from the fits to reference model 2.3.

### Daily fractional growth rates (&delta;)

HA| &delta;<sub>0</sub> | day 1 | &delta;<sub>1</sub> | day 2 | &delta;<sub>2</sub>
---|---|---|---|---|---
bc|10.6 +/- 1.1|18|-2.5 +/- 0.3|92|3.0 +/- 0.7|180|0.3 +/- 0.4|217|5.0 +/- 0.2|253|1.0 +/- 0.2
fraser|13.2 +/- 4.2|18|-1.5 +/- 0.3|106|3.7 +/- 0.5|175|-2.3 +/- 0.8|196|4.6 +/- 0.3|253|1.1 +/- 0.5
interior|19.6 +/- 3.6|18|-4.8 +/- 0.9|180|4.8 +/- 0.3
island|13.0 +/- 1.7|15|-5.3 +/- 1.1|80|0.5 +/- 0.8|234|11.3 +/- 2.3|256|-0.7 +/- 1.0
coastal|8.6 +/- 0.8|18|-5.6 +/- 0.4|104|2.1 +/- 0.5|190|-0.6 +/- 0.3|228|6.1 +/- 0.5|253|-1.2 +/- 0.4

* &delta;<sub>0</sub>: initial daily fractional growth parameter (in percent)
* day 1: days after March 1, 2020 when transmission rate changed
* Note: November 7 is day 252 in this scheme

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

### [Vancouver Island](img/island-summary.pdf)

![island](img/island-summary.png)


## [return to case studies](../index.md)

