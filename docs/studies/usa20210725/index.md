## July 25, 2021 Analysis of USA state data

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

![var_rat](img/us_variant_ratios_20210725.png)

A summary of the estimated selection coefficients for each state are below.

![sel_co](img/us_selection_coefficients_20210725.png)

The mean selection coefficient for delta (gamma) is 0.092 (0.020). There is large variance in the estimates from each state.

## Swing in growth rates due to delta and relaxation

The selection coefficient for delta (wrt alpha) indicates that the daily growth rate for delta is about 9% per day larger than
the daily growth rate for alpha (under the same circumstances.
The emergence of delta has occured at the same time as 

At the same that the delta variant has emerged, there has been general relaxation of health measures.
As a result, the swing in growth rate is much larger than 9% in the past several week.
The figure below shows the distribution of growth swing for the states, having a mean of 15% and standard deviation of 3%.

![usa_swing](img/usa_swing_20210725.png)

The growth of delta in the US is now on average 9% per day with a standardard deviation of 3%.

![usa_swing](img/usa_delta_growth_20210725.png)

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until July 24, 2021.

The green points are the daily cases, the grey points the daily hospitalizations, and
indigo points are the daily deaths (each averaged over a week).
The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
If the susceptibe fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline during, which appear as straight lines on
these log-scale plots.
With immunity growing, these lines are no longer straight - bending downwards due to the herd effect.
The curves are the model expectations for cases, hospitalizations, and deaths, and for most states
all three are determined from the case data. These states:
AR, CA, FL, IL, KY, LA, MA, MD, MI, MN, MS,NJ,NY,OH,OK, VA
were found to
have hospitalization growth rates significantly less than their case growth rates, and therefore hospitalization data was used to
define the most recent trajectories for hospitalizations and deaths.

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).

At the bottom of this page, plots showing the combined forecast for the US are shown.

### [Alaska](img/ak_2_9_0725.pdf)

![ak](img/ak_2_9_0725.png)

### [Alabama](img/al_2_9_0725.pdf)

![al](img/al_2_9_0725.png)

### [Arkansas](img/ar_2_9_0725.pdf)

![ar](img/ar_2_9_0725.png)

### [Arizona](img/az_2_9_0725.pdf)

![az](img/az_2_9_0725.png)

### [California](img/ca_2_9_0725.pdf)

![ca](img/ca_2_9_0725.png)

### [Colorado](img/co_2_9_0725.pdf)

![co](img/co_2_9_0725.png)

### [Connecticut](img/ct_2_9_0725.pdf)

![ct](img/ct_2_9_0725.png)

### [District Of Columbia](img/dc_2_9_0725.pdf)

![dc](img/dc_2_9_0725.png)

### [Delaware](img/de_2_9_0725.pdf)

![de](img/de_2_9_0725.png)

### [Florida](img/fl_2_9_0725.pdf)

![fl](img/fl_2_9_0725.png)

### [Georgia](img/ga_2_9_0725.pdf)

![ga](img/ga_2_9_0725.png)

### [Hawaii](img/hi_2_9_0725.pdf)

![hi](img/hi_2_9_0725.png)

### [Iowa](img/ia_2_9_0725.pdf)

![ia](img/ia_2_9_0725.png)

### [Idaho](img/id_2_9_0725.pdf)

![id](img/id_2_9_0725.png)

### [Illinois](img/il_2_9_0725.pdf)

![il](img/il_2_9_0725.png)

### [Indiana](img/in_2_9_0725.pdf)

![in](img/in_2_9_0725.png)

### [Kansas](img/ks_2_9_0725.pdf)

![ks](img/ks_2_9_0725.png)

### [Kentucky](img/ky_2_9_0725.pdf)

![ky](img/ky_2_9_0725.png)

### [Louisiana](img/la_2_9_0725.pdf)

![la](img/la_2_9_0725.png)

### [Massachusetts](img/ma_2_9_0725.pdf)

![ma](img/ma_2_9_0725.png)

### [Maryland](img/md_2_9_0725.pdf)

![md](img/md_2_9_0725.png)

### [Maine](img/me_2_9_0725.pdf)

![me](img/me_2_9_0725.png)

### [Michigan](img/mi_2_9_0725.pdf)

![mi](img/mi_2_9_0725.png)

### [Minnesota](img/mn_2_9_0725.pdf)

![mn](img/mn_2_9_0725.png)

### [Missouri](img/mo_2_9_0725.pdf)

![mo](img/mo_2_9_0725.png)

### [Mississippi](img/ms_2_9_0725.pdf)

![ms](img/ms_2_9_0725.png)

### [Montana](img/mt_2_9_0725.pdf)

![mt](img/mt_2_9_0725.png)

### [North Carolina](img/nc_2_9_0725.pdf)

![nc](img/nc_2_9_0725.png)

### [North Dakota](img/nd_2_9_0725.pdf)

![nd](img/nd_2_9_0725.png)

### [Nebraska](img/ne_2_9_0725.pdf)

![ne](img/ne_2_9_0725.png)

### [New Hampshire](img/nh_2_9_0725.pdf)

![nh](img/nh_2_9_0725.png)

### [New Jersey](img/nj_2_9_0725.pdf)

![nj](img/nj_2_9_0725.png)

### [New Mexico](img/nm_2_9_0725.pdf)

![nm](img/nm_2_9_0725.png)

### [Nevada](img/nv_2_9_0725.pdf)

![nv](img/nv_2_9_0725.png)

### [New York](img/ny_2_9_0725.pdf)

![ny](img/ny_2_9_0725.png)

### [Ohio](img/oh_2_9_0725.pdf)

![oh](img/oh_2_9_0725.png)

### [Oklahoma](img/ok_2_9_0725.pdf)

![ok](img/ok_2_9_0725.png)

### [Oregon](img/or_2_9_0725.pdf)

![or](img/or_2_9_0725.png)

### [Pennsylvania](img/pa_2_9_0725.pdf)

![pa](img/pa_2_9_0725.png)

### [Puerto Rico](img/pr_2_9_0725.pdf)

![pr](img/pr_2_9_0725.png)

### [Rhode Island](img/ri_2_9_0725.pdf)

![ri](img/ri_2_9_0725.png)

### [South Carolina](img/sc_2_9_0725.pdf)

![sc](img/sc_2_9_0725.png)

### [South Dakota](img/sd_2_9_0725.pdf)

![sd](img/sd_2_9_0725.png)

### [Tennessee](img/tn_2_9_0725.pdf)

![tn](img/tn_2_9_0725.png)

### [Texas](img/tx_2_9_0725.pdf)

![tx](img/tx_2_9_0725.png)

### [Utah](img/ut_2_9_0725.pdf)

![ut](img/ut_2_9_0725.png)

### [Virginia](img/va_2_9_0725.pdf)

![va](img/va_2_9_0725.png)

### [Vermont](img/vt_2_9_0725.pdf)

![vt](img/vt_2_9_0725.png)

### [Washington](img/wa_2_9_0725.pdf)

![wa](img/wa_2_9_0725.png)

### [Wisconsin](img/wi_2_9_0725.pdf)

![wi](img/wi_2_9_0725.png)

### [West Virginia](img/wv_2_9_0725.pdf)

![wv](img/wv_2_9_0725.png)

### [Wyoming](img/wy_2_9_0725.pdf)

![wy](img/wy_2_9_0725.png)


## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, cases are forecast to grow at a rate of about 7% per day (doubling every 10 days).

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

