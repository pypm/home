## October 24, 2021 Analysis of USA state data

Summary: For all states, daily growth rates for cases
are negative, meaning that infection rates are in decline.
Furthermore, the daily growth rates themselves are trending
more negative for many states.
These states have a growth rate that is 2%/day less than
they were 4 weeks ago.
That rate of change of the growth rate is consistent
with the effect of increasing immunity in the population.

The comparison of growth rates now and 4 weeks ago are shown in the figure below
for US states, Canadian provinces, and European nations.
The situation in Europe is very concerning, showing an increase in
growth rates by 5%/day or more, resulting in rapid
growth in the majority of Europe.
European studies are posted [here](../index.md).

![growth_change](img/growth_change_20211025.png)

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until October 23, 2021.

An infection model is setup for each state, calibrated using the case data from that state.
Given the time history of infections, projections for hospitalization and death are calculated
and shown as curves in the plots below.
The degree that hospitalization and death data following the model projections, indicates the
ability of this approach to forecast future hospitalization and death.

The green points are the daily cases, the grey points the daily hospitalizations, and
indigo points are the daily deaths (each averaged over a week).
The case data are used to define the periods for which transmission rate appears to be constant.
The vertical lines show where the transmission rate is changed.
If the susceptibe fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline during, which appear as straight lines on
these log-scale plots.
With immunity growing, these lines are no longer straight - bending downwards due to the herd effect.
The curves are the model expectations for cases, hospitalizations, and deaths, and
all three are determined from the case data.

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).

At the bottom of this page, plots showing the combined forecast for the US are shown.

### [Alaska](img/ak_2_9_1024.pdf)

![ak](img/ak_2_9_1024.png)

### [Alabama](img/al_2_9_1024.pdf)

![al](img/al_2_9_1024.png)

### [Arkansas](img/ar_2_9_1024.pdf)

![ar](img/ar_2_9_1024.png)

### [Arizona](img/az_2_9_1024.pdf)

![az](img/az_2_9_1024.png)

### [California](img/ca_2_9_1024.pdf)

![ca](img/ca_2_9_1024.png)

### [Colorado](img/co_2_9_1024.pdf)

![co](img/co_2_9_1024.png)

### [Connecticut](img/ct_2_9_1024.pdf)

![ct](img/ct_2_9_1024.png)

### [District Of Columbia](img/dc_2_9_1024.pdf)

![dc](img/dc_2_9_1024.png)

### [Delaware](img/de_2_9_1024.pdf)

![de](img/de_2_9_1024.png)

### [Florida](img/fl_2_9_1024.pdf)

![fl](img/fl_2_9_1024.png)

### [Georgia](img/ga_2_9_1024.pdf)

![ga](img/ga_2_9_1024.png)

### [Hawaii](img/hi_2_9_1024.pdf)

![hi](img/hi_2_9_1024.png)

### [Iowa](img/ia_2_9_1024.pdf)

![ia](img/ia_2_9_1024.png)

### [Idaho](img/id_2_9_1024.pdf)

![id](img/id_2_9_1024.png)

### [Illinois](img/il_2_9_1024.pdf)

![il](img/il_2_9_1024.png)

### [Indiana](img/in_2_9_1024.pdf)

![in](img/in_2_9_1024.png)

### [Kansas](img/ks_2_9_1024.pdf)

![ks](img/ks_2_9_1024.png)

### [Kentucky](img/ky_2_9_1024.pdf)

![ky](img/ky_2_9_1024.png)

### [Louisiana](img/la_2_9_1024.pdf)

![la](img/la_2_9_1024.png)

### [Massachusetts](img/ma_2_9_1024.pdf)

![ma](img/ma_2_9_1024.png)

### [Maryland](img/md_2_9_1024.pdf)

![md](img/md_2_9_1024.png)

### [Maine](img/me_2_9_1024.pdf)

![me](img/me_2_9_1024.png)

### [Michigan](img/mi_2_9_1024.pdf)

![mi](img/mi_2_9_1024.png)

### [Minnesota](img/mn_2_9_1024.pdf)

![mn](img/mn_2_9_1024.png)

### [Missouri](img/mo_2_9_1024.pdf)

![mo](img/mo_2_9_1024.png)

### [Mississippi](img/ms_2_9_1024.pdf)

![ms](img/ms_2_9_1024.png)

### [Montana](img/mt_2_9_1024.pdf)

![mt](img/mt_2_9_1024.png)

### [North Carolina](img/nc_2_9_1024.pdf)

![nc](img/nc_2_9_1024.png)

### [North Dakota](img/nd_2_9_1024.pdf)

![nd](img/nd_2_9_1024.png)

### [Nebraska](img/ne_2_9_1024.pdf)

![ne](img/ne_2_9_1024.png)

### [New Hampshire](img/nh_2_9_1024.pdf)

![nh](img/nh_2_9_1024.png)

### [New Jersey](img/nj_2_9_1024.pdf)

![nj](img/nj_2_9_1024.png)

### [New Mexico](img/nm_2_9_1024.pdf)

![nm](img/nm_2_9_1024.png)

### [Nevada](img/nv_2_9_1024.pdf)

![nv](img/nv_2_9_1024.png)

### [New York](img/ny_2_9_1024.pdf)

![ny](img/ny_2_9_1024.png)

### [Ohio](img/oh_2_9_1024.pdf)

![oh](img/oh_2_9_1024.png)

### [Oklahoma](img/ok_2_9_1024.pdf)

![ok](img/ok_2_9_1024.png)

### [Oregon](img/or_2_9_1024.pdf)

![or](img/or_2_9_1024.png)

### [Pennsylvania](img/pa_2_9_1024.pdf)

![pa](img/pa_2_9_1024.png)

### [Puerto Rico](img/pr_2_9_1024.pdf)

![pr](img/pr_2_9_1024.png)

### [Rhode Island](img/ri_2_9_1024.pdf)

![ri](img/ri_2_9_1024.png)

### [South Carolina](img/sc_2_9_1024.pdf)

![sc](img/sc_2_9_1024.png)

### [South Dakota](img/sd_2_9_1024.pdf)

![sd](img/sd_2_9_1024.png)

### [Tennessee](img/tn_2_9_1024.pdf)

![tn](img/tn_2_9_1024.png)

### [Texas](img/tx_2_9_1024.pdf)

![tx](img/tx_2_9_1024.png)

### [Utah](img/ut_2_9_1024.pdf)

![ut](img/ut_2_9_1024.png)

### [Virginia](img/va_2_9_1024.pdf)

![va](img/va_2_9_1024.png)

### [Vermont](img/vt_2_9_1024.pdf)

![vt](img/vt_2_9_1024.png)

### [Washington](img/wa_2_9_1024.pdf)

![wa](img/wa_2_9_1024.png)

### [Wisconsin](img/wi_2_9_1024.pdf)

![wi](img/wi_2_9_1024.png)

### [West Virginia](img/wv_2_9_1024.pdf)

![wv](img/wv_2_9_1024.png)

### [Wyoming](img/wy_2_9_1024.pdf)

![wy](img/wy_2_9_1024.png)

## Comparing prevalence between states 

The following plots show the daily cases per 100,000 people in each state, grouped according to the 10 standard federal regions.

![prev](img/USA_2_9_1024_prevalence.png)

## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, case rates, hospitalizations, and deaths are forecast to continue to decline.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

