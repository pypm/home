## January 2, 2022 Omicron projections for US states

Omicron infections are spreading rapidly around the globe.
Doubling times of 2-3 days are found in many jurisdictions.

For several US states, omicron has been dominant for weeks, resulting in
significant increases in case growth rates.
For these states, projections for omicron can be made from population level data.

Using hospital data, model fits are performed 
to estimate severity of omicron infections, an omicron scaling 
parameter is fit. The hospitalization probability for omicron infections is given by
the product of tha parameter and the probability for hospitalization for delta infections.
The reduction in duration of hospital stays is not estimated from data, instead the
value is fixed to be 0.4 times the duration for delta infections, which yields
reasonable agreement with data, as shown below.

The mean severity is 0.30 and the standard deviation is 0.21, giving an estimated severity of
0.30 +/- 0.05 (one standard deviation error in the mean).
It appears that omicron infections that lead to cases are 
significantly less severe than delta infections that lead to cases.

## Individual state projections

For this analysis, the case and death data source is the New York Times, since it has
has more regular updates and fewer irregularities than the JHU data.

The plots for each state below show the case, hospitalization, and deaths data since
August 2021 (left) and since November 15 2021 (right).
The maximum vertical axis values for cases are 500/100k (left) and 200/100k (right), and
for the hospital occupancy are 200/100k (left) and 100/100k (right).
Daily hospital admissions and deaths are scaled up by 10 and 20 respectively.

The infection model is defined by fitting the model to the case data, and the
hospitalization and deaths models are derived from the infection model.

The omicron variant is assumed to have a much larger susceptible population, due to its
ability to evade immunity (natural and vaccination immunity). 
For this study, those immunized against earlier strains only have 20% effective immunity
against omicron.

The green points are the daily cases, the grey points the daily hospitalizations, 
the teal points are hospital occupancy, and the indigo points are the daily deaths. 
The larger circles are weekly averages to help guide the eye.

The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
If the susceptibe fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline.
With immunity growing, the curves bend downwards due to the herd effect.
Interpretting the growth of omicron with changing delta rates growth rates leads to additional
uncertainty in the interpretations.

The curves are the model expectations for cases, hospitalizations, and deaths, and
all three are determined from the case data.

There are several challenges arising from data issues, in particular Thanksgiving closures and
possible infection outbreaks, and Christmas closures.
The fits to case data do not include data collected after December 23, since data after that date
may be affected by the holidays and by testing capacity limits.
All hospitalization data are used to estimate omicron severity, since those data may
be less affected by holiday and capacity limits.

The numerical value indicate in the plot legend is the fit value for the omicron severity parameter.

### [Alabama](img/al_4_1_0102_linear_omicron.pdf)

![al](img/al_4_1_0102_linear_omicron.png)

### [Arizona](img/az_4_1_0102_linear_omicron.pdf)

![az](img/az_4_1_0102_linear_omicron.png)

### [California](img/ca_4_1_0102_linear_omicron.pdf)

![ca](img/ca_4_1_0102_linear_omicron.png)

### [Colorado](img/co_4_1_0102_linear_omicron.pdf)

![co](img/co_4_1_0102_linear_omicron.png)

### [Connecticut](img/ct_4_1_0102_linear_omicron.pdf)

![ct](img/ct_4_1_0102_linear_omicron.png)

### [District Of Columbia](img/dc_4_1_0102_linear_omicron.pdf)

![dc](img/dc_4_1_0102_linear_omicron.png)

### [Delaware](img/de_4_1_0102_linear_omicron.pdf)

![de](img/de_4_1_0102_linear_omicron.png)

### [Florida](img/fl_4_1_0102_linear_omicron.pdf)

![fl](img/fl_4_1_0102_linear_omicron.png)

### [Georgia](img/ga_4_1_0102_linear_omicron.pdf)

![ga](img/ga_4_1_0102_linear_omicron.png)

### [Hawaii](img/hi_4_1_0102_linear_omicron.pdf)

![hi](img/hi_4_1_0102_linear_omicron.png)

### [Louisiana](img/la_4_1_0102_linear_omicron.pdf)

![la](img/la_4_1_0102_linear_omicron.png)

### [Massachusetts](img/ma_4_1_0102_linear_omicron.pdf)

![ma](img/ma_4_1_0102_linear_omicron.png)

### [New Jersey](img/nj_4_1_0102_linear_omicron.pdf)

![nj](img/nj_4_1_0102_linear_omicron.png)

### [New York](img/ny_4_1_0102_linear_omicron.pdf)

![ny](img/ny_4_1_0102_linear_omicron.png)

### [Pennsylvania](img/pa_4_1_0102_linear_omicron.pdf)

![pa](img/pa_4_1_0102_linear_omicron.png)

### [Puerto Rico](img/pr_4_1_0102_linear_omicron.pdf)

![pr](img/pr_4_1_0102_linear_omicron.png)

### [Texas](img/tx_4_1_0102_linear_omicron.pdf)

![tx](img/tx_4_1_0102_linear_omicron.png)

### [Virginia](img/va_4_1_0102_linear_omicron.pdf)

![va](img/va_4_1_0102_linear_omicron.png)

## [return to case studies](../index.md)

