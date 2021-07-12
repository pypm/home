## July 1, 2021 Analysis of USA state data

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

![var_rat](img/us_variant_ratios_20210711.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/us_selection_coefficients_20210711.png)

The mean selection coefficient for delta is 0.090. There is large variance in the estimates from each state.

For most states the delta variant is responsible for most cases.
For those states with sufficient data, the selection coefficients are also shown.
Errors shown are 68% (assuming binomial properties).

#### delta prevalence for epi-week starting 2021-07-04

State | delta fraction | sel coeff (/day)
---|---|---
Alaska|0.77 +/- 0.03|0.08
Alabama|0.69 +/- 0.07|0.076 +/- 0.016
Arkansas|0.82 +/- 0.04|0.061 +/- 0.009
Arizona|0.70 +/- 0.05|0.087 +/- 0.007
California|0.85 +/- 0.01|0.101 +/- 0.005
Colorado|0.92 +/- 0.01|0.097 +/- 0.003
Connecticut|0.86 +/- 0.05|0.110 +/- 0.017
Delaware|0.67 +/- 0.04|0.08
Florida|0.52 +/- 0.03|0.079 +/- 0.003
Georgia|0.79 +/- 0.07|0.136 +/- 0.023
Hawaii|0.51 +/- 0.07|0.08
Iowa|0.80 +/- 0.05|0.08
Illinois|0.88 +/- 0.03|0.124 +/- 0.009
Indiana|0.93 +/- 0.02|0.122 +/- 0.009
Kansas|0.94 +/- 0.01|0.108 +/- 0.005
Kentucky|0.49 +/- 0.06|0.08
Louisiana|0.31 +/- 0.05|0.08
Massachusetts|0.63 +/- 0.06|0.075 +/- 0.006
Maryland|0.53 +/- 0.06|0.067 +/- 0.005
Michigan|0.52 +/- 0.04|0.08
Minnesota|0.91 +/- 0.02|0.159 +/- 0.011
Missouri|0.99 +/- 0.00|0.116 +/- 0.002
Mississippi|0.98 +/- 0.01|0.144 +/- 0.019
Montana|0.67 +/- 0.03|0.08
North Carolina|0.84 +/- 0.04|0.141 +/- 0.016
North Dakota|0.48 +/- 0.06|0.08
Nebraska|0.92 +/- 0.02|0.133 +/- 0.011
New Hampshire|0.50 +/- 0.07|0.08
New Jersey|0.83 +/- 0.03|0.083 +/- 0.009
New Mexico|0.58 +/- 0.04|0.08
Nevada|0.96 +/- 0.01|0.123 +/- 0.010
New York|0.75 +/- 0.03|0.083 +/- 0.004
Ohio|0.43 +/- 0.10|0.089 +/- 0.016
Oklahoma|0.90 +/- 0.02|0.08
Oregon|0.17 +/- 0.03|0.08
Pennsylvania|0.52 +/- 0.11|0.090 +/- 0.015
Rhode Island|0.40 +/- 0.07|0.08
South Carolina|0.41 +/- 0.06|0.08
Tennessee|0.50 +/- 0.04|0.08
Texas|0.75 +/- 0.02|0.078 +/- 0.002
Utah|0.97 +/- 0.00|0.104 +/- 0.003
Virginia|0.46 +/- 0.07|0.061 +/- 0.007
Washington|0.69 +/- 0.02|0.072 +/- 0.002
Wisconsin|0.77 +/- 0.05|0.093 +/- 0.008
Wyoming|0.91 +/- 0.02|0.100 +/- 0.010

In the state fits below, it appears that the current upswing in cases in Missouri is due to delta and the
rapid growth will continue in the coming weeks if no action is taken.

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until July 10, 2021.

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
have the prevalence is estimated from the fit.
The growth advantage is assumed to be 8% per day compared to the alpha variant (or the estimated value if
genomic data is sufficient to measure).

At the bottom of this page, plots showing the combined forecast for the US is shown.

### [Alaska](img/ak_2_9_0711.pdf)

![ak](img/ak_2_9_0711.png)

### [Alabama](img/al_2_9_0711.pdf)

![al](img/al_2_9_0711.png)

### [Arkansas](img/ar_2_9_0711.pdf)

![ar](img/ar_2_9_0711.png)

### [Arizona](img/az_2_9_0711.pdf)

![az](img/az_2_9_0711.png)

### [California](img/ca_2_9_0711.pdf)

![ca](img/ca_2_9_0711.png)

### [Colorado](img/co_2_9_0711.pdf)

![co](img/co_2_9_0711.png)

### [Connecticut](img/ct_2_9_0711.pdf)

![ct](img/ct_2_9_0711.png)

### [District Of Columbia](img/dc_2_9_0711.pdf)

![dc](img/dc_2_9_0711.png)

### [Delaware](img/de_2_9_0711.pdf)

![de](img/de_2_9_0711.png)

### [Florida](img/fl_2_9_0711.pdf)

![fl](img/fl_2_9_0711.png)

### [Georgia](img/ga_2_9_0711.pdf)

![ga](img/ga_2_9_0711.png)

### [Hawaii](img/hi_2_9_0711.pdf)

![hi](img/hi_2_9_0711.png)

### [Iowa](img/ia_2_9_0711.pdf)

![ia](img/ia_2_9_0711.png)

### [Idaho](img/id_2_9_0711.pdf)

![id](img/id_2_9_0711.png)

### [Illinois](img/il_2_9_0711.pdf)

![il](img/il_2_9_0711.png)

### [Indiana](img/in_2_9_0711.pdf)

![in](img/in_2_9_0711.png)

### [Kansas](img/ks_2_9_0711.pdf)

![ks](img/ks_2_9_0711.png)

### [Kentucky](img/ky_2_9_0711.pdf)

![ky](img/ky_2_9_0711.png)

### [Louisiana](img/la_2_9_0711.pdf)

![la](img/la_2_9_0711.png)

### [Massachusetts](img/ma_2_9_0711.pdf)

![ma](img/ma_2_9_0711.png)

### [Maryland](img/md_2_9_0711.pdf)

![md](img/md_2_9_0711.png)

### [Maine](img/me_2_9_0711.pdf)

![me](img/me_2_9_0711.png)

### [Michigan](img/mi_2_9_0711.pdf)

![mi](img/mi_2_9_0711.png)

### [Minnesota](img/mn_2_9_0711.pdf)

![mn](img/mn_2_9_0711.png)

### [Missouri](img/mo_2_9_0711.pdf)

![mo](img/mo_2_9_0711.png)

### [Mississippi](img/ms_2_9_0711.pdf)

![ms](img/ms_2_9_0711.png)

### [Montana](img/mt_2_9_0711.pdf)

![mt](img/mt_2_9_0711.png)

### [North Carolina](img/nc_2_9_0711.pdf)

![nc](img/nc_2_9_0711.png)

### [North Dakota](img/nd_2_9_0711.pdf)

![nd](img/nd_2_9_0711.png)

### [Nebraska](img/ne_2_9_0711.pdf)

![ne](img/ne_2_9_0711.png)

### [New Hampshire](img/nh_2_9_0711.pdf)

![nh](img/nh_2_9_0711.png)

### [New Jersey](img/nj_2_9_0711.pdf)

![nj](img/nj_2_9_0711.png)

### [New Mexico](img/nm_2_9_0711.pdf)

![nm](img/nm_2_9_0711.png)

### [Nevada](img/nv_2_9_0711.pdf)

![nv](img/nv_2_9_0711.png)

### [New York](img/ny_2_9_0711.pdf)

![ny](img/ny_2_9_0711.png)

### [Ohio](img/oh_2_9_0711.pdf)

![oh](img/oh_2_9_0711.png)

### [Oklahoma](img/ok_2_9_0711.pdf)

![ok](img/ok_2_9_0711.png)

### [Oregon](img/or_2_9_0711.pdf)

![or](img/or_2_9_0711.png)

### [Pennsylvania](img/pa_2_9_0711.pdf)

![pa](img/pa_2_9_0711.png)

### [Puerto Rico](img/pr_2_9_0711.pdf)

![pr](img/pr_2_9_0711.png)

### [Rhode Island](img/ri_2_9_0711.pdf)

![ri](img/ri_2_9_0711.png)

### [South Carolina](img/sc_2_9_0711.pdf)

![sc](img/sc_2_9_0711.png)

### [South Dakota](img/sd_2_9_0711.pdf)

![sd](img/sd_2_9_0711.png)

### [Tennessee](img/tn_2_9_0711.pdf)

![tn](img/tn_2_9_0711.png)

### [Texas](img/tx_2_9_0711.pdf)

![tx](img/tx_2_9_0711.png)

### [Utah](img/ut_2_9_0711.pdf)

![ut](img/ut_2_9_0711.png)

### [Virginia](img/va_2_9_0711.pdf)

![va](img/va_2_9_0711.png)

### [Vermont](img/vt_2_9_0711.pdf)

![vt](img/vt_2_9_0711.png)

### [Washington](img/wa_2_9_0711.pdf)

![wa](img/wa_2_9_0711.png)

### [Wisconsin](img/wi_2_9_0711.pdf)

![wi](img/wi_2_9_0711.png)

### [West Virginia](img/wv_2_9_0711.pdf)

![wv](img/wv_2_9_0711.png)

### [Wyoming](img/wy_2_9_0711.pdf)

![wy](img/wy_2_9_0711.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

