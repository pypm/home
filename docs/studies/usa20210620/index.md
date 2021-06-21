## June 20, 2021 Analysis of USA state data

## Studies of variant prevalence and growth advantage

### Genomic analysis using GISAID data from outbreak.info

Many states submit whole genomic sequencing data to GISAID that can be used to track the growth of VoC state by state.
The ratios of delta (B.1.617.2), gamma (P.1), and iota (B.1.526) to alpha (B.1.1.7) cases are shown in the plots below, where it is evident that
both delta and gamma have higher transmission than alpha, with delta significantly larger.
All other strains are combined in the group designated 'other.
For states with insufficient data to estimate the selection coefficient, they are fixed at 0.07 (0.02) for delta (gamma), in order to estimate the
delta prevalence, and the lines are shown as dashed in the figures below.

![var_rat](img/us_variant_ratios_20210621.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/us_selection_coefficients_20210621.png)

Several states, have a significant fraction of cases due to the delta variant.
Using the data from above, the estimated fraction of cases due to delta are estimated as shown in the table below.
For those states with sufficient data, the selection coefficients are also show.
Errors shown are 68% (assuming binomial properties).

#### delta prevalence for epi-week starting 2021-06-06

State | delta fraction | sel coeff (/day)
---|---|---
AL|0.34 +/- 0.10|0.07
AR|0.53 +/- 0.10|0.07
AZ|0.16 +/- 0.06|0.058 +/- 0.019
CA|0.17 +/- 0.02|0.043 +/- 0.003
CO|0.52 +/- 0.09|0.104 +/- 0.006
CT|0.22 +/- 0.04|0.07
DE|0.23 +/- 0.08|0.07
FL|0.12 +/- 0.02|0.074 +/- 0.006
GA|0.07 +/- 0.02|0.07
IL|0.10 +/- 0.02|0.055 +/- 0.007
IN|0.25 +/- 0.06|0.079 +/- 0.008
KS|0.49 +/- 0.09|0.105 +/- 0.009
KY|0.09 +/- 0.03|0.07
LA|0.04 +/- 0.02|0.07
MA|0.19 +/- 0.04|0.071 +/- 0.006
MD|0.12 +/- 0.04|0.058 +/- 0.009
MI|0.09 +/- 0.02|0.07
MN|0.05 +/- 0.02|0.056 +/- 0.010
MO|0.79 +/- 0.19|0.126 +/- 0.011
MS|0.23 +/- 0.08|0.07
MT|0.21 +/- 0.06|0.07
NC|0.05 +/- 0.01|0.07
NE|0.23 +/- 0.05|0.07
NH|0.10 +/- 0.03|0.07
NJ|0.34 +/- 0.06|0.070 +/- 0.006
NM|0.15 +/- 0.04|0.07
NV|0.28 +/- 0.08|0.07
NY|0.20 +/- 0.05|0.068 +/- 0.008
OH|0.08 +/- 0.02|0.07
OK|0.47 +/- 0.20|0.07
OR|0.04 +/- 0.01|0.07
PA|0.09 +/- 0.01|0.07
SC|0.07 +/- 0.03|0.07
TN|0.08 +/- 0.02|0.07
TX|0.25 +/- 0.04|0.074 +/- 0.005
UT|0.65 +/- 0.20|0.088 +/- 0.010
VA|0.14 +/- 0.04|0.054 +/- 0.009
WA|0.20 +/- 0.02|0.063 +/- 0.004
WI|0.12 +/- 0.02|0.07
WY|0.31 +/- 0.05|0.07

In the state fits below, it appears that the current upswing in cases in Missouri is due to delta and the
rapid growth will continue in the coming weeks if no action is taken.

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until June 19, 2021.

The green points are the daily cases, the grey points the daily hospitalizations, and
indigo points are the daily deaths (each averaged over a week).
The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
In absence of immunity, constant transmission rates
lead to steady exponential growth or decline during, which appear as straight lines on
these log-scale plots.
With immunity growing, these lines are no longer straight - bending downwards due to the herd effect.
The curves are the model expectations for cases, hospitalizations, and deaths, as determined from
the case data.

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).
For states with published genomic data for delta the current prevalence is assigned, while other states
have the June 6 prevalence set to 10%.
The growth advantage is assumed to be 6% per day compared to the alpha variant (or higher if
genomic data is sufficient to measure).

At the bottom of this page, plots showing the combined forecast for the US is shown.

### [Alaska](img/ak_2_9_0620.pdf)

![ak](img/ak_2_9_0620.png)

### [Alabama](img/al_2_9_0620.pdf)

![al](img/al_2_9_0620.png)

### [Arkansas](img/ar_2_9_0620.pdf)

![ar](img/ar_2_9_0620.png)

### [Arizona](img/az_2_9_0620.pdf)

![az](img/az_2_9_0620.png)

### [California](img/ca_2_9_0620.pdf)

![ca](img/ca_2_9_0620.png)

### [Colorado](img/co_2_9_0620.pdf)

![co](img/co_2_9_0620.png)

### [Connecticut](img/ct_2_9_0620.pdf)

![ct](img/ct_2_9_0620.png)

### [District Of Columbia](img/dc_2_9_0620.pdf)

![dc](img/dc_2_9_0620.png)

### [Delaware](img/de_2_9_0620.pdf)

![de](img/de_2_9_0620.png)

### [Florida](img/fl_2_9_0620.pdf)

![fl](img/fl_2_9_0620.png)

### [Georgia](img/ga_2_9_0620.pdf)

![ga](img/ga_2_9_0620.png)

### [Hawaii](img/hi_2_9_0620.pdf)

![hi](img/hi_2_9_0620.png)

### [Iowa](img/ia_2_9_0620.pdf)

![ia](img/ia_2_9_0620.png)

### [Idaho](img/id_2_9_0620.pdf)

![id](img/id_2_9_0620.png)

### [Illinois](img/il_2_9_0620.pdf)

![il](img/il_2_9_0620.png)

### [Indiana](img/in_2_9_0620.pdf)

![in](img/in_2_9_0620.png)

### [Kansas](img/ks_2_9_0620.pdf)

![ks](img/ks_2_9_0620.png)

### [Kentucky](img/ky_2_9_0620.pdf)

![ky](img/ky_2_9_0620.png)

### [Louisiana](img/la_2_9_0620.pdf)

![la](img/la_2_9_0620.png)

### [Massachusetts](img/ma_2_9_0620.pdf)

![ma](img/ma_2_9_0620.png)

### [Maryland](img/md_2_9_0620.pdf)

![md](img/md_2_9_0620.png)

### [Maine](img/me_2_9_0620.pdf)

![me](img/me_2_9_0620.png)

### [Michigan](img/mi_2_9_0620.pdf)

![mi](img/mi_2_9_0620.png)

### [Minnesota](img/mn_2_9_0620.pdf)

![mn](img/mn_2_9_0620.png)

### [Missouri](img/mo_2_9_0620.pdf)

![mo](img/mo_2_9_0620.png)

### [Mississippi](img/ms_2_9_0620.pdf)

![ms](img/ms_2_9_0620.png)

### [Montana](img/mt_2_9_0620.pdf)

![mt](img/mt_2_9_0620.png)

### [North Carolina](img/nc_2_9_0620.pdf)

![nc](img/nc_2_9_0620.png)

### [North Dakota](img/nd_2_9_0620.pdf)

![nd](img/nd_2_9_0620.png)

### [Nebraska](img/ne_2_9_0620.pdf)

![ne](img/ne_2_9_0620.png)

### [New Hampshire](img/nh_2_9_0620.pdf)

![nh](img/nh_2_9_0620.png)

### [New Jersey](img/nj_2_9_0620.pdf)

![nj](img/nj_2_9_0620.png)

### [New Mexico](img/nm_2_9_0620.pdf)

![nm](img/nm_2_9_0620.png)

### [Nevada](img/nv_2_9_0620.pdf)

![nv](img/nv_2_9_0620.png)

### [New York](img/ny_2_9_0620.pdf)

![ny](img/ny_2_9_0620.png)

### [Ohio](img/oh_2_9_0620.pdf)

![oh](img/oh_2_9_0620.png)

### [Oklahoma](img/ok_2_9_0620.pdf)

![ok](img/ok_2_9_0620.png)

### [Oregon](img/or_2_9_0620.pdf)

![or](img/or_2_9_0620.png)

### [Pennsylvania](img/pa_2_9_0620.pdf)

![pa](img/pa_2_9_0620.png)

### [Puerto Rico](img/pr_2_9_0620.pdf)

![pr](img/pr_2_9_0620.png)

### [Rhode Island](img/ri_2_9_0620.pdf)

![ri](img/ri_2_9_0620.png)

### [South Carolina](img/sc_2_9_0620.pdf)

![sc](img/sc_2_9_0620.png)

### [South Dakota](img/sd_2_9_0620.pdf)

![sd](img/sd_2_9_0620.png)

### [Tennessee](img/tn_2_9_0620.pdf)

![tn](img/tn_2_9_0620.png)

### [Texas](img/tx_2_9_0620.pdf)

![tx](img/tx_2_9_0620.png)

### [Utah](img/ut_2_9_0620.pdf)

![ut](img/ut_2_9_0620.png)

### [Virginia](img/va_2_9_0620.pdf)

![va](img/va_2_9_0620.png)

### [Vermont](img/vt_2_9_0620.pdf)

![vt](img/vt_2_9_0620.png)

### [Washington](img/wa_2_9_0620.pdf)

![wa](img/wa_2_9_0620.png)

### [Wisconsin](img/wi_2_9_0620.pdf)

![wi](img/wi_2_9_0620.png)

### [West Virginia](img/wv_2_9_0620.pdf)

![wv](img/wv_2_9_0620.png)

### [Wyoming](img/wy_2_9_0620.pdf)

![wy](img/wy_2_9_0620.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

