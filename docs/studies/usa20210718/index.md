## July 18, 2021 Analysis of USA state data

## Studies of variant prevalence and growth advantage

### Genomic analysis using GISAID data from outbreak.info

Many states submit whole genomic sequencing data to GISAID that can be used to track the growth of VoC state by state.
The ratios of delta (B.1.617.2), gamma (P.1), and iota (B.1.526) to alpha (B.1.1.7)
cases are shown in the plots below, where it is evident that
both delta and gamma have higher transmission than alpha, with delta significantly larger.
Also shown are B.1.621 and C.37.
Sub lineages have been included in the main lineages (so AY.1, AY.2, and AY.3 are included in delta, for example).
All other strains are combined in the group designated 'nota' (none of the above).
For states with insufficient data to estimate the selection coefficient,
they are fixed at 0.08 (0.02) for delta (gamma), in order to estimate the current
delta prevalence, and the lines are shown as dashed in the figures below.

![var_rat](img/us_variant_ratios_20210718.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/us_selection_coefficients_20210718.png)

The mean selection coefficient for delta is 0.092. There is large variance in the estimates from each state.

For almost all states, the delta variant is responsible for most cases.
For those states with sufficient data, the selection coefficients are also shown.
Errors shown are 68% (assuming binomial properties).

#### delta prevalence for epi-week starting 2021-07-11

State | delta fraction | sel coeff (/day)
---|---|---
Alaska|0.63 +/- 0.08|0.069 +/- 0.016
Alabama|0.81 +/- 0.04|0.081 +/- 0.010
Arkansas|0.92 +/- 0.01|0.066 +/- 0.005
Arizona|0.85 +/- 0.02|0.095 +/- 0.006
California|0.92 +/- 0.01|0.093 +/- 0.003
Colorado|0.96 +/- 0.00|0.096 +/- 0.003
Connecticut|0.88 +/- 0.04|0.101 +/- 0.012
Delaware|0.77 +/- 0.03|0.08
Florida|0.76 +/- 0.02|0.089 +/- 0.002
Georgia|0.96 +/- 0.01|0.156 +/- 0.016
Hawaii|0.73 +/- 0.04|0.08
Iowa|0.87 +/- 0.03|0.08
Idaho|0.77 +/- 0.04|0.08
Illinois|0.93 +/- 0.01|0.121 +/- 0.007
Indiana|0.96 +/- 0.01|0.116 +/- 0.007
Kansas|0.97 +/- 0.00|0.110 +/- 0.005
Kentucky|0.67 +/- 0.03|0.08
Louisiana|0.92 +/- 0.03|0.166 +/- 0.020
Massachusetts|0.72 +/- 0.05|0.074 +/- 0.005
Maryland|0.70 +/- 0.04|0.072 +/- 0.004
Michigan|0.65 +/- 0.03|0.08
Minnesota|0.96 +/- 0.01|0.150 +/- 0.009
Missouri|0.99 +/- 0.00|0.098 +/- 0.002
Mississippi|0.97 +/- 0.01|0.108 +/- 0.010
Montana|0.73 +/- 0.05|0.073 +/- 0.012
North Carolina|0.94 +/- 0.01|0.140 +/- 0.011
North Dakota|0.59 +/- 0.04|0.08
Nebraska|0.95 +/- 0.02|0.128 +/- 0.010
New Hampshire|0.62 +/- 0.06|0.08
New Jersey|0.94 +/- 0.01|0.097 +/- 0.006
New Mexico|0.45 +/- 0.07|0.051 +/- 0.008
Nevada|0.98 +/- 0.01|0.129 +/- 0.007
New York|0.82 +/- 0.02|0.084 +/- 0.003
Ohio|0.80 +/- 0.05|0.112 +/- 0.012
Oklahoma|0.92 +/- 0.01|0.08
Oregon|0.37 +/- 0.06|0.070 +/- 0.007
Pennsylvania|0.83 +/- 0.05|0.108 +/- 0.011
Rhode Island|0.46 +/- 0.06|0.08
South Carolina|0.65 +/- 0.04|0.08
Tennessee|0.75 +/- 0.05|0.086 +/- 0.007
Texas|0.86 +/- 0.01|0.082 +/- 0.002
Utah|0.98 +/- 0.01|0.104 +/- 0.001
Virginia|0.75 +/- 0.04|0.075 +/- 0.005
Washington|0.81 +/- 0.01|0.072 +/- 0.002
Wisconsin|0.88 +/- 0.03|0.097 +/- 0.007
Wyoming|0.96 +/- 0.01|0.106 +/- 0.008

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until July 17, 2021.

The green points are the daily cases, the grey points the daily hospitalizations, and
indigo points are the daily deaths (each averaged over a week).
The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
If the susceptibe fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline during, which appear as straight lines on
these log-scale plots.
With immunity growing, these lines are no longer straight - bending downwards due to the herd effect.
The curves are the model expectations for cases, hospitalizations, and deaths, and for most states
all three are determined from the case data. These states: MA, MD, MN, NC, NM, NY, PA were found to
have hospitalization growth significantly less than case growth, and therefore hospitalization data was used to
define the most recent trajectories for hospitalizations and deaths.

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).
For states with published genomic data for delta the current prevalence is assigned, while other states
have the prevalence is estimated from the fit.
The growth advantage is assumed to be 8% per day compared to the alpha variant (or the estimated value if
genomic data is sufficient to measure).

At the bottom of this page, plots showing the combined forecast for the US is shown.

### [Alaska](img/ak_2_9_0718.pdf)

![ak](img/ak_2_9_0718.png)

### [Alabama](img/al_2_9_0718.pdf)

![al](img/al_2_9_0718.png)

### [Arkansas](img/ar_2_9_0718.pdf)

![ar](img/ar_2_9_0718.png)

### [Arizona](img/az_2_9_0718.pdf)

![az](img/az_2_9_0718.png)

### [California](img/ca_2_9_0718.pdf)

![ca](img/ca_2_9_0718.png)

### [Colorado](img/co_2_9_0718.pdf)

![co](img/co_2_9_0718.png)

### [Connecticut](img/ct_2_9_0718.pdf)

![ct](img/ct_2_9_0718.png)

### [District Of Columbia](img/dc_2_9_0718.pdf)

![dc](img/dc_2_9_0718.png)

### [Delaware](img/de_2_9_0718.pdf)

![de](img/de_2_9_0718.png)

### [Florida](img/fl_2_9_0718.pdf)

![fl](img/fl_2_9_0718.png)

### [Georgia](img/ga_2_9_0718.pdf)

![ga](img/ga_2_9_0718.png)

### [Hawaii](img/hi_2_9_0718.pdf)

![hi](img/hi_2_9_0718.png)

### [Iowa](img/ia_2_9_0718.pdf)

![ia](img/ia_2_9_0718.png)

### [Idaho](img/id_2_9_0718.pdf)

![id](img/id_2_9_0718.png)

### [Illinois](img/il_2_9_0718.pdf)

![il](img/il_2_9_0718.png)

### [Indiana](img/in_2_9_0718.pdf)

![in](img/in_2_9_0718.png)

### [Kansas](img/ks_2_9_0718.pdf)

![ks](img/ks_2_9_0718.png)

### [Kentucky](img/ky_2_9_0718.pdf)

![ky](img/ky_2_9_0718.png)

### [Louisiana](img/la_2_9_0718.pdf)

![la](img/la_2_9_0718.png)

### [Massachusetts](img/ma_2_9_0718.pdf)

![ma](img/ma_2_9_0718.png)

### [Maryland](img/md_2_9_0718.pdf)

![md](img/md_2_9_0718.png)

### [Maine](img/me_2_9_0718.pdf)

![me](img/me_2_9_0718.png)

### [Michigan](img/mi_2_9_0718.pdf)

![mi](img/mi_2_9_0718.png)

### [Minnesota](img/mn_2_9_0718.pdf)

![mn](img/mn_2_9_0718.png)

### [Missouri](img/mo_2_9_0718.pdf)

![mo](img/mo_2_9_0718.png)

### [Mississippi](img/ms_2_9_0718.pdf)

![ms](img/ms_2_9_0718.png)

### [Montana](img/mt_2_9_0718.pdf)

![mt](img/mt_2_9_0718.png)

### [North Carolina](img/nc_2_9_0718.pdf)

![nc](img/nc_2_9_0718.png)

### [North Dakota](img/nd_2_9_0718.pdf)

![nd](img/nd_2_9_0718.png)

### [Nebraska](img/ne_2_9_0718.pdf)

![ne](img/ne_2_9_0718.png)

### [New Hampshire](img/nh_2_9_0718.pdf)

![nh](img/nh_2_9_0718.png)

### [New Jersey](img/nj_2_9_0718.pdf)

![nj](img/nj_2_9_0718.png)

### [New Mexico](img/nm_2_9_0718.pdf)

![nm](img/nm_2_9_0718.png)

### [Nevada](img/nv_2_9_0718.pdf)

![nv](img/nv_2_9_0718.png)

### [New York](img/ny_2_9_0718.pdf)

![ny](img/ny_2_9_0718.png)

### [Ohio](img/oh_2_9_0718.pdf)

![oh](img/oh_2_9_0718.png)

### [Oklahoma](img/ok_2_9_0718.pdf)

![ok](img/ok_2_9_0718.png)

### [Oregon](img/or_2_9_0718.pdf)

![or](img/or_2_9_0718.png)

### [Pennsylvania](img/pa_2_9_0718.pdf)

![pa](img/pa_2_9_0718.png)

### [Puerto Rico](img/pr_2_9_0718.pdf)

![pr](img/pr_2_9_0718.png)

### [Rhode Island](img/ri_2_9_0718.pdf)

![ri](img/ri_2_9_0718.png)

### [South Carolina](img/sc_2_9_0718.pdf)

![sc](img/sc_2_9_0718.png)

### [South Dakota](img/sd_2_9_0718.pdf)

![sd](img/sd_2_9_0718.png)

### [Tennessee](img/tn_2_9_0718.pdf)

![tn](img/tn_2_9_0718.png)

### [Texas](img/tx_2_9_0718.pdf)

![tx](img/tx_2_9_0718.png)

### [Utah](img/ut_2_9_0718.pdf)

![ut](img/ut_2_9_0718.png)

### [Virginia](img/va_2_9_0718.pdf)

![va](img/va_2_9_0718.png)

### [Vermont](img/vt_2_9_0718.pdf)

![vt](img/vt_2_9_0718.png)

### [Washington](img/wa_2_9_0718.pdf)

![wa](img/wa_2_9_0718.png)

### [Wisconsin](img/wi_2_9_0718.pdf)

![wi](img/wi_2_9_0718.png)

### [West Virginia](img/wv_2_9_0718.pdf)

![wv](img/wv_2_9_0718.png)

### [Wyoming](img/wy_2_9_0718.pdf)

![wy](img/wy_2_9_0718.png)


## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, cases are forecast to grow at a rate of about 7% per day (doubling every 10 days).

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

