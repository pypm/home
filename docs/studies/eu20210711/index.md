## July 11, 2021 Analysis of EU national data

## Studies of variant prevalence and growth advantage

### Genomic analysis using GISAID data

Many nations submit whole genomic sequencing data to GISAID that can be used to track the growth of VoC relative to each other.
The ratios of delta (B.1.617.2), gamma (P.1), and beta (B.1.351) to alpha (B.1.1.7)
cases are shown in the plots below, where it is evident that
both delta and gamma have higher transmission than alpha, with delta significantly larger.
All other strains are combined in the group designated 'other'.
For countries with insufficient data to estimate the selection coefficient,
they are fixed at 0.07 (0.02) for delta (gamma), in order to estimate the current
delta prevalence, and the lines are shown as dashed in the figures below.

![var_rat](img/eu_variant_ratios_20210711.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/eu_selection_coefficients_20210711.png)

The mean selection coefficient for delta is 0.085. There is large variance in the estimates from each country.

For most countries the delta variant is responsible for most cases.
For those with sufficient data, the selection coefficients are also shown.
Errors shown are 68% (assuming binomial properties).

#### delta prevalence for epi-week starting 2021-07-11

Country | delta fraction | sel coeff (/day)
---|---|---
Austria|0.98 +/- 0.00|0.123 +/- 0.013
Belgium|0.51 +/- 0.03|0.052 +/- 0.002
Croatia|0.83 +/- 0.03|0.07
Czechia|0.49 +/- 0.08|0.043 +/- 0.006
Denmark|0.83 +/- 0.02|0.122 +/- 0.004
Finland|0.99 +/- 0.00|0.094 +/- 0.002
France|0.78 +/- 0.02|0.085 +/- 0.003
Germany|0.82 +/- 0.01|0.085 +/- 0.001
Greece|0.12 +/- 0.04|0.07
Ireland|0.46 +/- 0.04|0.051 +/- 0.003
Italy|0.65 +/- 0.02|0.064 +/- 0.002
Latvia|0.62 +/- 0.05|0.07
Lithuania|0.20 +/- 0.05|0.07
Luxembourg|0.99 +/- 0.01|0.116 +/- 0.002
Netherlands|0.72 +/- 0.03|0.082 +/- 0.004
Norway|0.60 +/- 0.05|0.059 +/- 0.005
Poland|0.13 +/- 0.05|0.034 +/- 0.007
Portugal|0.98 +/- 0.00|0.091 +/- 0.003
Romania|0.85 +/- 0.02|0.07
Slovakia|0.26 +/- 0.06|0.07
Slovenia|0.16 +/- 0.05|0.07
Spain|0.87 +/- 0.01|0.083 +/- 0.003
Sweden|0.96 +/- 0.00|0.118 +/- 0.003

## Fits to case data

The plots below show the case and death data for 18 EU nations.
The data fits were done using data up until July 10, 2021.

The large green (indigo) circles are the daily cases (deaths) averaged over each week.
The smaller points show the daily values.
The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
In absence of immunity, constant transmission rates
lead to steady exponential growth or decline during, which appear as straight lines on
these log-scale plots.
With immunity growing, these lines are no longer straight - bending downwards due to the herd effect.
The curves are the model expectations for cases, hospitalizations, and deaths, as determined from
the case data.

The dashed curves separately show the reported cases interpretted as coming
from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).
The very rapid growth of cases is a combination of relaxing restrictions and the introduction of the delta variant.
Several of these are not sustainable, and will no doubt turn around.


### [Austria](img/at_2_9_0709.pdf)

![at](img/at_2_9_0709.png)

### [Belgium](img/be_2_9_0709.pdf)

![be](img/be_2_9_0709.png)

### [Bulgaria](img/bg_2_9_0709.pdf)

![bg](img/bg_2_9_0709.png)

### [Croatia](img/hr_2_9_0709.pdf)

![hr](img/hr_2_9_0709.png)

### [Cyprus](img/cy_2_9_0709.pdf)

![cy](img/cy_2_9_0709.png)

### [Czechia](img/cz_2_9_0709.pdf)

![cz](img/cz_2_9_0709.png)

### [Denmark](img/dk_2_9_0709.pdf)

![dk](img/dk_2_9_0709.png)

### [Estonia](img/ee_2_9_0709.pdf)

![ee](img/ee_2_9_0709.png)

### [France](img/fr_2_9_0709.pdf)

![fr](img/fr_2_9_0709.png)

### [Germany](img/de_2_9_0709.pdf)

![de](img/de_2_9_0709.png)

### [Greece](img/gr_2_9_0709.pdf)

![gr](img/gr_2_9_0709.png)

### [Ireland](img/ie_2_9_0709.pdf)

![ie](img/ie_2_9_0709.png)

### [Italy](img/it_2_9_0709.pdf)

![it](img/it_2_9_0709.png)

### [Netherlands](img/nl_2_9_0709.pdf)

![nl](img/nl_2_9_0709.png)

### [Norway](img/no_2_9_0709.pdf)

![no](img/no_2_9_0709.png)

### [Spain](img/es_2_9_0709.pdf)

![es](img/es_2_9_0709.png)

### [Switzerland](img/ch_2_9_0709.pdf)

![ch](img/ch_2_9_0709.png)

### [United Kingdom](img/gb_2_9_0709.pdf)

![gb](img/gb_2_9_0709.png)


## [return to case studies](../index.md)

