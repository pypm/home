## July 25, 2021 Analysis of EU national data

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

![var_rat](img/eu_variant_ratios_20210725.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/eu_selection_coefficients_20210725.png)

The mean selection coefficient for delta is 0.09 (with respect to alpha).
There is large variance in the estimates from each country.

For most countries the delta variant is responsible for most cases.
For those with sufficient data, the selection coefficients are also shown.
Errors shown are 68% (assuming binomial properties).

## Fits to case data

The plots below show the case and death data for 29 EU nations.
The data fits were done using data up until July 24, 2021.

The large green (indigo) circles are the daily cases (deaths) averaged over each week.
The smaller points show the daily values.
The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
If the susceptible fraction is roughly constant, constant transmission rates
lead to steady exponential growth or decline during, which appear as straight lines on
these log-scale plots.
With immunity growing, these lines are no longer straight - bending downwards due to the herd effect.
The solid curves show the model expectations for cases and deaths, as determined from
the case data.
Since this analysis started in July, fine tuning of the model for May date was not done, resulting in
some discrepency with data.

The dashed curves separately show the reported cases interpretted as coming
from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).
The very rapid growth of cases is a combination of relaxing restrictions and the introduction of the delta variant.

### [Austria](img/at_2_9_0725.pdf)

![at](img/at_2_9_0725.png)

### [Belgium](img/be_2_9_0725.pdf)

![be](img/be_2_9_0725.png)

### [Bulgaria](img/bg_2_9_0725.pdf)

![bg](img/bg_2_9_0725.png)

### [Croatia](img/hr_2_9_0725.pdf)

![hr](img/hr_2_9_0725.png)

### [Cyprus](img/cy_2_9_0725.pdf)

![cy](img/cy_2_9_0725.png)

### [Czechia](img/cz_2_9_0725.pdf)

![cz](img/cz_2_9_0725.png)

### [Denmark](img/dk_2_9_0725.pdf)

![dk](img/dk_2_9_0725.png)

### [Estonia](img/ee_2_9_0725.pdf)

![ee](img/ee_2_9_0725.png)

### [Finland](img/fi_2_9_0725.pdf)

![fi](img/fi_2_9_0725.png)

### [France](img/fr_2_9_0725.pdf)

![fr](img/fr_2_9_0725.png)

### [Germany](img/de_2_9_0725.pdf)

![de](img/de_2_9_0725.png)

### [Greece](img/gr_2_9_0725.pdf)

![gr](img/gr_2_9_0725.png)

### [Hungary](img/hu_2_9_0725.pdf)

![hu](img/hu_2_9_0725.png)

### [Ireland](img/ie_2_9_0725.pdf)

![ie](img/ie_2_9_0725.png)

### [Italy](img/it_2_9_0725.pdf)

![it](img/it_2_9_0725.png)

### [Latvia](img/lv_2_9_0725.pdf)

![lv](img/lv_2_9_0725.png)

### [Lithuania](img/lt_2_9_0725.pdf)

![lt](img/lt_2_9_0725.png)

### [Luxembourg](img/lu_2_9_0725.pdf)

![lu](img/lu_2_9_0725.png)

### [Netherlands](img/nl_2_9_0725.pdf)

![nl](img/nl_2_9_0725.png)

### [Norway](img/no_2_9_0725.pdf)

![no](img/no_2_9_0725.png)

### [Poland](img/pl_2_9_0725.pdf)

![pl](img/pl_2_9_0725.png)

### [Portugal](img/pt_2_9_0725.pdf)

![pt](img/pt_2_9_0725.png)

### [Romania](img/ro_2_9_0725.pdf)

![ro](img/ro_2_9_0725.png)

### [Slovakia](img/sk_2_9_0725.pdf)

![sk](img/sk_2_9_0725.png)

### [Slovenia](img/si_2_9_0725.pdf)

![si](img/si_2_9_0725.png)

### [Spain](img/es_2_9_0725.pdf)

![es](img/es_2_9_0725.png)

### [Sweden](img/se_2_9_0725.pdf)

![se](img/se_2_9_0725.png)

### [Switzerland](img/ch_2_9_0725.pdf)

![ch](img/ch_2_9_0725.png)

### [United Kingdom](img/gb_2_9_0725.pdf)

![gb](img/gb_2_9_0725.png)


## [return to case studies](../index.md)

