## June 13, 2021 Analysis of USA state data

## Studies of variant prevalence and growth advantage

### SGTF data from helix.com

For some staes, genomic screening [data](https://github.com/myhelix/helix-covid19db)
using the SGTF protocol, is available to estimate the growth advantage
(aka selection coefficient, s) of the B117 variant as well as the current fraction of cases dues to that variant.

Unlike in other countries, SGTF cases did not continue to gain an increasing fraction, but stabalized at a fixed fraction.
This is due to other variants of concern with a similar growth advantage but which are not tagged by SGTF.

Below is a figure showing fits to the ratio of the SGTF cases to non-SGTF cases which is used used to estimate the
selection coefficient (s), the ratio of other VoC to the B.1.1.7 (rpb),
and the current fraction of cases due to variants of concern (f_v).

The curves are the best fit, the shaded region indicates the 95% central interval of the ensemble of curves
(modifying the parameters according to their covariance) and the vertical bars are the central 95% intervals
for each binomial sampling.

![var_p](img/usa_variant_ratio_p.png)

region | s | rpb| w |f_b (June 13)
---|---|---|---|---
Arizona|0.092 +/- 0.006|0.695 +/- 0.058|0.001 +/- 0.000|0.592 +/- 0.020
California|0.073 +/- 0.002|0.695 +/- 0.033|0.002 +/- 0.000|0.590 +/- 0.011
Florida|0.079 +/- 0.001|0.475 +/- 0.009|0.007 +/- 0.000|0.678 +/- 0.004
Georgia|0.100 +/- 0.003|0.290 +/- 0.014|0.001 +/- 0.000|0.775 +/- 0.008
Illinois|0.080 +/- 0.006|0.563 +/- 0.060|0.000 +/- 0.001|0.641 +/- 0.025
Indiana|0.108 +/- 0.004|0.385 +/- 0.018|0.001 +/- 0.000|0.723 +/- 0.010
Louisiana|0.095 +/- 0.011|0.156 +/- 0.035|0.001 +/- 0.001|0.866 +/- 0.026
Massachusetts|0.126 +/- 0.009|1.025 +/- 0.043|0.031 +/- 0.002|0.494 +/- 0.010
Michigan|0.111 +/- 0.005|0.228 +/- 0.009|0.001 +/- 0.000|0.815 +/- 0.006
Minnesota|0.098 +/- 0.008|0.187 +/- 0.021|0.001 +/- 0.000|0.843 +/- 0.014
North Carolina|0.095 +/- 0.004|0.500 +/- 0.028|0.001 +/- 0.000|0.667 +/- 0.012
New Jersey|0.066 +/- 0.009|0.281 +/- 0.176|0.000 +/- 0.001|0.771 +/- 0.093
New York|0.088 +/- 0.018|1.122 +/- 0.221|0.004 +/- 0.004|0.469 +/- 0.049
Pennsylvania|0.088 +/- 0.003|0.572 +/- 0.020|0.003 +/- 0.000|0.636 +/- 0.008
Texas|0.102 +/- 0.003|0.459 +/- 0.022|0.000 +/- 0.000|0.685 +/- 0.010


 *   s: selection coefficient
 *   rpb: ratio of other VoC to B.1.1.7
 *   w: SGTF false identification of B.1.1.7 per sample
 *   f_v: fraction of cases due to variants of concern on June 13, 2021

### GISAID data from outbreak.info

Many states submit whole genomic sequencing data to GISAID that can be used to track the growth of VoC state by state.
The ratios of delta (B.1.617.2) and gamma (P.1) to alpha (B.1.1.7) cases are shown in the plots below, where it is evident that
both delta and gamma have higher transmission than alpha, with delta significantly larger.
Some states, such as Colorado and Utah, have a significant fraction of cases due to teh delta variant.

![var_rat](img/us_variant_ratios_2_good.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/us_selection_coefficients_2x.png)

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until June 12, 2021.

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
have the current prevalence set to 10%.
The growth advantage is assumed to be 5% per day compared to the alpha variant.

At the bottom of this page, plots showing the combined forecast for the US is shown.

### [Alaska](img/ak_2_9_0613.pdf)

![ak](img/ak_2_9_0613.png)

### [Alabama](img/al_2_9_0613.pdf)

![al](img/al_2_9_0613.png)

### [Arkansas](img/ar_2_9_0613.pdf)

![ar](img/ar_2_9_0613.png)

### [Arizona](img/az_2_9_0613.pdf)

![az](img/az_2_9_0613.png)

### [California](img/ca_2_9_0613.pdf)

![ca](img/ca_2_9_0613.png)

### [Colorado](img/co_2_9_0613.pdf)

![co](img/co_2_9_0613.png)

### [Connecticut](img/ct_2_9_0613.pdf)

![ct](img/ct_2_9_0613.png)

### [District Of Columbia](img/dc_2_9_0613.pdf)

![dc](img/dc_2_9_0613.png)

### [Delaware](img/de_2_9_0613.pdf)

![de](img/de_2_9_0613.png)

### [Florida](img/fl_2_9_0613.pdf)

![fl](img/fl_2_9_0613.png)

### [Georgia](img/ga_2_9_0613.pdf)

![ga](img/ga_2_9_0613.png)

### [Hawaii](img/hi_2_9_0613.pdf)

![hi](img/hi_2_9_0613.png)

### [Iowa](img/ia_2_9_0613.pdf)

![ia](img/ia_2_9_0613.png)

### [Idaho](img/id_2_9_0613.pdf)

![id](img/id_2_9_0613.png)

### [Illinois](img/il_2_9_0613.pdf)

![il](img/il_2_9_0613.png)

### [Indiana](img/in_2_9_0613.pdf)

![in](img/in_2_9_0613.png)

### [Kansas](img/ks_2_9_0613.pdf)

![ks](img/ks_2_9_0613.png)

### [Kentucky](img/ky_2_9_0613.pdf)

![ky](img/ky_2_9_0613.png)

### [Louisiana](img/la_2_9_0613.pdf)

![la](img/la_2_9_0613.png)

### [Massachusetts](img/ma_2_9_0613.pdf)

![ma](img/ma_2_9_0613.png)

### [Maryland](img/md_2_9_0613.pdf)

![md](img/md_2_9_0613.png)

### [Maine](img/me_2_9_0613.pdf)

![me](img/me_2_9_0613.png)

### [Michigan](img/mi_2_9_0613.pdf)

![mi](img/mi_2_9_0613.png)

### [Minnesota](img/mn_2_9_0613.pdf)

![mn](img/mn_2_9_0613.png)

### [Missouri](img/mo_2_9_0613.pdf)

![mo](img/mo_2_9_0613.png)

### [Mississippi](img/ms_2_9_0613.pdf)

![ms](img/ms_2_9_0613.png)

### [Montana](img/mt_2_9_0613.pdf)

![mt](img/mt_2_9_0613.png)

### [North Carolina](img/nc_2_9_0613.pdf)

![nc](img/nc_2_9_0613.png)

### [North Dakota](img/nd_2_9_0613.pdf)

![nd](img/nd_2_9_0613.png)

### [Nebraska](img/ne_2_9_0613.pdf)

![ne](img/ne_2_9_0613.png)

### [New Hampshire](img/nh_2_9_0613.pdf)

![nh](img/nh_2_9_0613.png)

### [New Jersey](img/nj_2_9_0613.pdf)

![nj](img/nj_2_9_0613.png)

### [New Mexico](img/nm_2_9_0613.pdf)

![nm](img/nm_2_9_0613.png)

### [Nevada](img/nv_2_9_0613.pdf)

![nv](img/nv_2_9_0613.png)

### [New York](img/ny_2_9_0613.pdf)

![ny](img/ny_2_9_0613.png)

### [Ohio](img/oh_2_9_0613.pdf)

![oh](img/oh_2_9_0613.png)

### [Oklahoma](img/ok_2_9_0613.pdf)

![ok](img/ok_2_9_0613.png)

### [Oregon](img/or_2_9_0613.pdf)

![or](img/or_2_9_0613.png)

### [Pennsylvania](img/pa_2_9_0613.pdf)

![pa](img/pa_2_9_0613.png)

### [Puerto Rico](img/pr_2_9_0613.pdf)

![pr](img/pr_2_9_0613.png)

### [Rhode Island](img/ri_2_9_0613.pdf)

![ri](img/ri_2_9_0613.png)

### [South Carolina](img/sc_2_9_0613.pdf)

![sc](img/sc_2_9_0613.png)

### [South Dakota](img/sd_2_9_0613.pdf)

![sd](img/sd_2_9_0613.png)

### [Tennessee](img/tn_2_9_0613.pdf)

![tn](img/tn_2_9_0613.png)

### [Texas](img/tx_2_9_0613.pdf)

![tx](img/tx_2_9_0613.png)

### [Utah](img/ut_2_9_0613.pdf)

![ut](img/ut_2_9_0613.png)

### [Virginia](img/va_2_9_0613.pdf)

![va](img/va_2_9_0613.png)

### [Vermont](img/vt_2_9_0613.pdf)

![vt](img/vt_2_9_0613.png)

### [Washington](img/wa_2_9_0613.pdf)

![wa](img/wa_2_9_0613.png)

### [Wisconsin](img/wi_2_9_0613.pdf)

![wi](img/wi_2_9_0613.png)

### [West Virginia](img/wv_2_9_0613.pdf)

![wv](img/wv_2_9_0613.png)

### [Wyoming](img/wy_2_9_0613.pdf)

![wy](img/wy_2_9_0613.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

