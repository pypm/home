## August 1, 2021 Analysis of USA state data

## Swing in growth rates due to delta and relaxation

The selection coefficient for delta (wrt alpha) indicates that the daily growth rate for delta is about 9% per day larger than
the daily growth rate for alpha (under the same circumstances.

At the same that the delta variant has emerged, there has been general relaxation of social distancing measures.
As a result, the swing in growth rate is much larger than 9% in the past several weeks.
The figure below shows the distribution of growth swing for the states, having a mean of 16% and standard deviation of 4%.

![usa_swing](img/usa_swing_20210801.png)

The growth of delta in the US is now on average 10% per day with a standardard deviation of 3%.

![usa_swing](img/usa_delta_growth_20210801.png)

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until July 31, 2021.

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
AR, CA, CT, IL, KY, LA, MI, NJ, TX, and WI
were found to
have hospitalization growth rates significantly less than their case growth rates, and therefore hospitalization data was used to
define the most recent trajectories for hospitalizations and deaths.

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).

At the bottom of this page, plots showing the combined forecast for the US are shown.

### [Alaska](img/ak_2_9_0801.pdf)

![ak](img/ak_2_9_0801.png)

### [Alabama](img/al_2_9_0801.pdf)

![al](img/al_2_9_0801.png)

### [Arkansas](img/ar_2_9_0801.pdf)

![ar](img/ar_2_9_0801.png)

### [Arizona](img/az_2_9_0801.pdf)

![az](img/az_2_9_0801.png)

### [California](img/ca_2_9_0801.pdf)

![ca](img/ca_2_9_0801.png)

### [Colorado](img/co_2_9_0801.pdf)

![co](img/co_2_9_0801.png)

### [Connecticut](img/ct_2_9_0801.pdf)

![ct](img/ct_2_9_0801.png)

### [District Of Columbia](img/dc_2_9_0801.pdf)

![dc](img/dc_2_9_0801.png)

### [Delaware](img/de_2_9_0801.pdf)

![de](img/de_2_9_0801.png)

### [Florida](img/fl_2_9_0801.pdf)

![fl](img/fl_2_9_0801.png)

### [Georgia](img/ga_2_9_0801.pdf)

![ga](img/ga_2_9_0801.png)

### [Hawaii](img/hi_2_9_0801.pdf)

![hi](img/hi_2_9_0801.png)

### [Iowa](img/ia_2_9_0801.pdf)

![ia](img/ia_2_9_0801.png)

### [Idaho](img/id_2_9_0801.pdf)

![id](img/id_2_9_0801.png)

### [Illinois](img/il_2_9_0801.pdf)

![il](img/il_2_9_0801.png)

### [Indiana](img/in_2_9_0801.pdf)

![in](img/in_2_9_0801.png)

### [Kansas](img/ks_2_9_0801.pdf)

![ks](img/ks_2_9_0801.png)

### [Kentucky](img/ky_2_9_0801.pdf)

![ky](img/ky_2_9_0801.png)

### [Louisiana](img/la_2_9_0801.pdf)

![la](img/la_2_9_0801.png)

### [Massachusetts](img/ma_2_9_0801.pdf)

![ma](img/ma_2_9_0801.png)

### [Maryland](img/md_2_9_0801.pdf)

![md](img/md_2_9_0801.png)

### [Maine](img/me_2_9_0801.pdf)

![me](img/me_2_9_0801.png)

### [Michigan](img/mi_2_9_0801.pdf)

![mi](img/mi_2_9_0801.png)

### [Minnesota](img/mn_2_9_0801.pdf)

![mn](img/mn_2_9_0801.png)

### [Missouri](img/mo_2_9_0801.pdf)

![mo](img/mo_2_9_0801.png)

### [Mississippi](img/ms_2_9_0801.pdf)

![ms](img/ms_2_9_0801.png)

### [Montana](img/mt_2_9_0801.pdf)

![mt](img/mt_2_9_0801.png)

### [North Carolina](img/nc_2_9_0801.pdf)

![nc](img/nc_2_9_0801.png)

### [North Dakota](img/nd_2_9_0801.pdf)

![nd](img/nd_2_9_0801.png)

### [Nebraska](img/ne_2_9_0801.pdf)

![ne](img/ne_2_9_0801.png)

### [New Hampshire](img/nh_2_9_0801.pdf)

![nh](img/nh_2_9_0801.png)

### [New Jersey](img/nj_2_9_0801.pdf)

![nj](img/nj_2_9_0801.png)

### [New Mexico](img/nm_2_9_0801.pdf)

![nm](img/nm_2_9_0801.png)

### [Nevada](img/nv_2_9_0801.pdf)

![nv](img/nv_2_9_0801.png)

### [New York](img/ny_2_9_0801.pdf)

![ny](img/ny_2_9_0801.png)

### [Ohio](img/oh_2_9_0801.pdf)

![oh](img/oh_2_9_0801.png)

### [Oklahoma](img/ok_2_9_0801.pdf)

![ok](img/ok_2_9_0801.png)

### [Oregon](img/or_2_9_0801.pdf)

![or](img/or_2_9_0801.png)

### [Pennsylvania](img/pa_2_9_0801.pdf)

![pa](img/pa_2_9_0801.png)

### [Puerto Rico](img/pr_2_9_0801.pdf)

![pr](img/pr_2_9_0801.png)

### [Rhode Island](img/ri_2_9_0801.pdf)

![ri](img/ri_2_9_0801.png)

### [South Carolina](img/sc_2_9_0801.pdf)

![sc](img/sc_2_9_0801.png)

### [South Dakota](img/sd_2_9_0801.pdf)

![sd](img/sd_2_9_0801.png)

### [Tennessee](img/tn_2_9_0801.pdf)

![tn](img/tn_2_9_0801.png)

### [Texas](img/tx_2_9_0801.pdf)

![tx](img/tx_2_9_0801.png)

### [Utah](img/ut_2_9_0801.pdf)

![ut](img/ut_2_9_0801.png)

### [Virginia](img/va_2_9_0801.pdf)

![va](img/va_2_9_0801.png)

### [Vermont](img/vt_2_9_0801.pdf)

![vt](img/vt_2_9_0801.png)

### [Washington](img/wa_2_9_0801.pdf)

![wa](img/wa_2_9_0801.png)

### [Wisconsin](img/wi_2_9_0801.pdf)

![wi](img/wi_2_9_0801.png)

### [West Virginia](img/wv_2_9_0801.pdf)

![wv](img/wv_2_9_0801.png)

### [Wyoming](img/wy_2_9_0801.pdf)

![wy](img/wy_2_9_0801.png)


## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, cases are forecast to grow at a rate of about 7% per day (doubling every 10 days).

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

