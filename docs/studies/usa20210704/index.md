## July 4, 2021 Analysis of USA state data

## Studies of variant prevalence and growth advantage

### Genomic analysis using GISAID data from outbreak.info

Many states submit whole genomic sequencing data to GISAID that can be used to track the growth of VoC state by state.
The ratios of delta (B.1.617.2), gamma (P.1), and iota (B.1.526) to alpha (B.1.1.7)
cases are shown in the plots below, where it is evident that
both delta and gamma have higher transmission than alpha, with delta significantly larger.
All other strains are combined in the group designated 'other'.
For states with insufficient data to estimate the selection coefficient,
they are fixed at 0.07 (0.02) for delta (gamma), in order to estimate the current
delta prevalence, and the lines are shown as dashed in the figures below.

![var_rat](img/us_variant_ratios_20210702.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/us_selection_coefficients_20210702.png)

Most states have a significant fraction of cases due to the delta variant as shown in the table below.
For those states with sufficient data, the selection coefficients are also shown.
Errors shown are 68% (assuming binomial properties).

#### delta prevalence for epi-week starting 2021-07-04

State | delta fraction | sel coeff (/day)
---|---|---
Alaska|0.73 +/- 0.17|0.07
Alabama|0.77 +/- 0.18|0.07
Arkansas|0.85 +/- 0.81|0.064 +/- 0.011
Arizona|0.59 +/- 0.22|0.075 +/- 0.009
California|0.65 +/- 0.07|0.059 +/- 0.002
Colorado|0.89 +/- 0.02|0.086 +/- 0.001
Connecticut|0.36 +/- 0.24|0.051 +/- 0.013
Delaware|0.61 +/- 0.14|0.07
Florida|0.41 +/- 0.08|0.073 +/- 0.004
Georgia|0.36 +/- 0.07|0.07
Hawaii|0.46 +/- 0.17|0.07
Iowa|0.72 +/- 0.36|0.07
Illinois|0.46 +/- 0.13|0.065 +/- 0.005
Indiana|0.86 +/- 0.16|0.094 +/- 0.002
Kansas|0.85 +/- 0.01|0.081 +/- 0.002
Kentucky|0.41 +/- 0.11|0.07
Louisiana|0.22 +/- 0.09|0.07
Massachusetts|0.63 +/- 0.22|0.074 +/- 0.006
Maryland|0.49 +/- 0.16|0.063 +/- 0.006
Michigan|0.40 +/- 0.07|0.07
Minnesota|0.42 +/- 0.13|0.083 +/- 0.006
Missouri|0.90 +/- 0.01|0.065 +/- 0.002
Mississippi|0.80 +/- 0.15|0.07
Montana|0.64 +/- 0.11|0.07
North Carolina|0.31 +/- 0.06|0.07
Nebraska|0.70 +/- 0.05|0.097 +/- 0.004
New Hampshire|0.39 +/- 0.13|0.07
New Jersey|0.80 +/- 0.18|0.072 +/- 0.004
New Mexico|0.53 +/- 0.10|0.07
Nevada|0.86 +/- 0.03|0.090 +/- 0.004
New York|0.78 +/- 0.20|0.085 +/- 0.005
Ohio|0.16 +/- 0.07|0.048 +/- 0.009
Oklahoma|0.85 +/- 0.72|0.07
Oregon|0.14 +/- 0.04|0.07
Pennsylvania|0.29 +/- 0.07|0.07
Rhode Island|0.29 +/- 0.11|0.07
South Carolina|0.23 +/- 0.10|0.07
Tennessee|0.41 +/- 0.08|0.07
Texas|0.75 +/- 0.11|0.079 +/- 0.003
Utah|0.89 +/- 0.06|0.074 +/- 0.002
Virginia|0.42 +/- 0.16|0.058 +/- 0.007
Washington|0.65 +/- 0.08|0.068 +/- 0.003
Wisconsin|0.77 +/- 0.32|0.091 +/- 0.009
Wyoming|0.89 +/- 0.13|0.092 +/- 0.003

In the state fits below, it appears that the current upswing in cases in Missouri is due to delta and the
rapid growth will continue in the coming weeks if no action is taken.

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until July 3, 2021.

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
The growth advantage is assumed to be 7% per day compared to the alpha variant (or higher if
genomic data is sufficient to measure).

At the bottom of this page, plots showing the combined forecast for the US is shown.

### [Alaska](img/ak_2_9_0704.pdf)

![ak](img/ak_2_9_0704.png)

### [Alabama](img/al_2_9_0704.pdf)

![al](img/al_2_9_0704.png)

### [Arkansas](img/ar_2_9_0704.pdf)

![ar](img/ar_2_9_0704.png)

### [Arizona](img/az_2_9_0704.pdf)

![az](img/az_2_9_0704.png)

### [California](img/ca_2_9_0704.pdf)

![ca](img/ca_2_9_0704.png)

### [Colorado](img/co_2_9_0704.pdf)

![co](img/co_2_9_0704.png)

### [Connecticut](img/ct_2_9_0704.pdf)

![ct](img/ct_2_9_0704.png)

### [District Of Columbia](img/dc_2_9_0704.pdf)

![dc](img/dc_2_9_0704.png)

### [Delaware](img/de_2_9_0704.pdf)

![de](img/de_2_9_0704.png)

### [Florida](img/fl_2_9_0704.pdf)

![fl](img/fl_2_9_0704.png)

### [Georgia](img/ga_2_9_0704.pdf)

![ga](img/ga_2_9_0704.png)

### [Hawaii](img/hi_2_9_0704.pdf)

![hi](img/hi_2_9_0704.png)

### [Iowa](img/ia_2_9_0704.pdf)

![ia](img/ia_2_9_0704.png)

### [Idaho](img/id_2_9_0704.pdf)

![id](img/id_2_9_0704.png)

### [Illinois](img/il_2_9_0704.pdf)

![il](img/il_2_9_0704.png)

### [Indiana](img/in_2_9_0704.pdf)

![in](img/in_2_9_0704.png)

### [Kansas](img/ks_2_9_0704.pdf)

![ks](img/ks_2_9_0704.png)

### [Kentucky](img/ky_2_9_0704.pdf)

![ky](img/ky_2_9_0704.png)

### [Louisiana](img/la_2_9_0704.pdf)

![la](img/la_2_9_0704.png)

### [Massachusetts](img/ma_2_9_0704.pdf)

![ma](img/ma_2_9_0704.png)

### [Maryland](img/md_2_9_0704.pdf)

![md](img/md_2_9_0704.png)

### [Maine](img/me_2_9_0704.pdf)

![me](img/me_2_9_0704.png)

### [Michigan](img/mi_2_9_0704.pdf)

![mi](img/mi_2_9_0704.png)

### [Minnesota](img/mn_2_9_0704.pdf)

![mn](img/mn_2_9_0704.png)

### [Missouri](img/mo_2_9_0704.pdf)

![mo](img/mo_2_9_0704.png)

### [Mississippi](img/ms_2_9_0704.pdf)

![ms](img/ms_2_9_0704.png)

### [Montana](img/mt_2_9_0704.pdf)

![mt](img/mt_2_9_0704.png)

### [North Carolina](img/nc_2_9_0704.pdf)

![nc](img/nc_2_9_0704.png)

### [North Dakota](img/nd_2_9_0704.pdf)

![nd](img/nd_2_9_0704.png)

### [Nebraska](img/ne_2_9_0704.pdf)

![ne](img/ne_2_9_0704.png)

### [New Hampshire](img/nh_2_9_0704.pdf)

![nh](img/nh_2_9_0704.png)

### [New Jersey](img/nj_2_9_0704.pdf)

![nj](img/nj_2_9_0704.png)

### [New Mexico](img/nm_2_9_0704.pdf)

![nm](img/nm_2_9_0704.png)

### [Nevada](img/nv_2_9_0704.pdf)

![nv](img/nv_2_9_0704.png)

### [New York](img/ny_2_9_0704.pdf)

![ny](img/ny_2_9_0704.png)

### [Ohio](img/oh_2_9_0704.pdf)

![oh](img/oh_2_9_0704.png)

### [Oklahoma](img/ok_2_9_0704.pdf)

![ok](img/ok_2_9_0704.png)

### [Oregon](img/or_2_9_0704.pdf)

![or](img/or_2_9_0704.png)

### [Pennsylvania](img/pa_2_9_0704.pdf)

![pa](img/pa_2_9_0704.png)

### [Puerto Rico](img/pr_2_9_0704.pdf)

![pr](img/pr_2_9_0704.png)

### [Rhode Island](img/ri_2_9_0704.pdf)

![ri](img/ri_2_9_0704.png)

### [South Carolina](img/sc_2_9_0704.pdf)

![sc](img/sc_2_9_0704.png)

### [South Dakota](img/sd_2_9_0704.pdf)

![sd](img/sd_2_9_0704.png)

### [Tennessee](img/tn_2_9_0704.pdf)

![tn](img/tn_2_9_0704.png)

### [Texas](img/tx_2_9_0704.pdf)

![tx](img/tx_2_9_0704.png)

### [Utah](img/ut_2_9_0704.pdf)

![ut](img/ut_2_9_0704.png)

### [Virginia](img/va_2_9_0704.pdf)

![va](img/va_2_9_0704.png)

### [Vermont](img/vt_2_9_0704.pdf)

![vt](img/vt_2_9_0704.png)

### [Washington](img/wa_2_9_0704.pdf)

![wa](img/wa_2_9_0704.png)

### [Wisconsin](img/wi_2_9_0704.pdf)

![wi](img/wi_2_9_0704.png)

### [West Virginia](img/wv_2_9_0704.pdf)

![wv](img/wv_2_9_0704.png)

### [Wyoming](img/wy_2_9_0704.pdf)

![wy](img/wy_2_9_0704.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

