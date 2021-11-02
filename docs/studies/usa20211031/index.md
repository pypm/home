## October 31, 2021 Analysis of USA state data

Summary: For most states, daily growth rates for cases
are negative, meaning that infection rates are in decline.
Furthermore, the daily growth rates themselves are trending
more negative for many states.

See the October 24 report for the
comparison of growth rates then and 4 weeks prior
for US states, Canadian provinces, and European nations.
The situation in Europe is very concerning, showing an increase in
growth rates by 5%/day or more, resulting in rapid
growth in the majority of Europe.
European studies are posted [here](../index.md).

Some states have shown a recent upswing in growth rates, namely
Alabama,
Arkansas,
California,
Georgia,
Hawaii,
Mississippi, and
Nebraska.
Given the recent situation in Europe, it is important to monitor
the situation closely in the US.

## Individual state histories

The plots below show the case / hospital admissions / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until October 30, 2021.

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

For several states recently, case data are problematic, having many anomalous entries.
For those states, hospital admission data is used instead to define the recent trends in the infection model.
The list of states affected for this analysis are:
Arkansas, Arizona, California, Colorado, Delaware, Florida, Iowa, Indiana, Kansas, Minnesota, Nebraska, and Wisconsin.

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).

At the bottom of this page, plots showing the combined forecast for the US are shown.

### [Alaska](img/ak_2_9_1031.pdf)

![ak](img/ak_2_9_1031.png)

### [Alabama](img/al_2_9_1031.pdf)

![al](img/al_2_9_1031.png)

### [Arkansas](img/ar_2_9_1031.pdf)

![ar](img/ar_2_9_1031.png)

### [Arizona](img/az_2_9_1031.pdf)

![az](img/az_2_9_1031.png)

### [California](img/ca_2_9_1031.pdf)

![ca](img/ca_2_9_1031.png)

### [Colorado](img/co_2_9_1031.pdf)

![co](img/co_2_9_1031.png)

### [Connecticut](img/ct_2_9_1031.pdf)

![ct](img/ct_2_9_1031.png)

### [District Of Columbia](img/dc_2_9_1031.pdf)

![dc](img/dc_2_9_1031.png)

### [Delaware](img/de_2_9_1031.pdf)

![de](img/de_2_9_1031.png)

### [Florida](img/fl_2_9_1031.pdf)

![fl](img/fl_2_9_1031.png)

### [Georgia](img/ga_2_9_1031.pdf)

![ga](img/ga_2_9_1031.png)

### [Hawaii](img/hi_2_9_1031.pdf)

![hi](img/hi_2_9_1031.png)

### [Iowa](img/ia_2_9_1031.pdf)

![ia](img/ia_2_9_1031.png)

### [Idaho](img/id_2_9_1031.pdf)

![id](img/id_2_9_1031.png)

### [Illinois](img/il_2_9_1031.pdf)

![il](img/il_2_9_1031.png)

### [Indiana](img/in_2_9_1031.pdf)

![in](img/in_2_9_1031.png)

### [Kansas](img/ks_2_9_1031.pdf)

![ks](img/ks_2_9_1031.png)

### [Kentucky](img/ky_2_9_1031.pdf)

![ky](img/ky_2_9_1031.png)

### [Louisiana](img/la_2_9_1031.pdf)

![la](img/la_2_9_1031.png)

### [Massachusetts](img/ma_2_9_1031.pdf)

![ma](img/ma_2_9_1031.png)

### [Maryland](img/md_2_9_1031.pdf)

![md](img/md_2_9_1031.png)

### [Maine](img/me_2_9_1031.pdf)

![me](img/me_2_9_1031.png)

### [Michigan](img/mi_2_9_1031.pdf)

![mi](img/mi_2_9_1031.png)

### [Minnesota](img/mn_2_9_1031.pdf)

![mn](img/mn_2_9_1031.png)

### [Missouri](img/mo_2_9_1031.pdf)

![mo](img/mo_2_9_1031.png)

### [Mississippi](img/ms_2_9_1031.pdf)

![ms](img/ms_2_9_1031.png)

### [Montana](img/mt_2_9_1031.pdf)

![mt](img/mt_2_9_1031.png)

### [North Carolina](img/nc_2_9_1031.pdf)

![nc](img/nc_2_9_1031.png)

### [North Dakota](img/nd_2_9_1031.pdf)

![nd](img/nd_2_9_1031.png)

### [Nebraska](img/ne_2_9_1031.pdf)

![ne](img/ne_2_9_1031.png)

### [New Hampshire](img/nh_2_9_1031.pdf)

![nh](img/nh_2_9_1031.png)

### [New Jersey](img/nj_2_9_1031.pdf)

![nj](img/nj_2_9_1031.png)

### [New Mexico](img/nm_2_9_1031.pdf)

![nm](img/nm_2_9_1031.png)

### [Nevada](img/nv_2_9_1031.pdf)

![nv](img/nv_2_9_1031.png)

### [New York](img/ny_2_9_1031.pdf)

![ny](img/ny_2_9_1031.png)

### [Ohio](img/oh_2_9_1031.pdf)

![oh](img/oh_2_9_1031.png)

### [Oklahoma](img/ok_2_9_1031.pdf)

![ok](img/ok_2_9_1031.png)

### [Oregon](img/or_2_9_1031.pdf)

![or](img/or_2_9_1031.png)

### [Pennsylvania](img/pa_2_9_1031.pdf)

![pa](img/pa_2_9_1031.png)

### [Puerto Rico](img/pr_2_9_1031.pdf)

![pr](img/pr_2_9_1031.png)

### [Rhode Island](img/ri_2_9_1031.pdf)

![ri](img/ri_2_9_1031.png)

### [South Carolina](img/sc_2_9_1031.pdf)

![sc](img/sc_2_9_1031.png)

### [South Dakota](img/sd_2_9_1031.pdf)

![sd](img/sd_2_9_1031.png)

### [Tennessee](img/tn_2_9_1031.pdf)

![tn](img/tn_2_9_1031.png)

### [Texas](img/tx_2_9_1031.pdf)

![tx](img/tx_2_9_1031.png)

### [Utah](img/ut_2_9_1031.pdf)

![ut](img/ut_2_9_1031.png)

### [Virginia](img/va_2_9_1031.pdf)

![va](img/va_2_9_1031.png)

### [Vermont](img/vt_2_9_1031.pdf)

![vt](img/vt_2_9_1031.png)

### [Washington](img/wa_2_9_1031.pdf)

![wa](img/wa_2_9_1031.png)

### [Wisconsin](img/wi_2_9_1031.pdf)

![wi](img/wi_2_9_1031.png)

### [West Virginia](img/wv_2_9_1031.pdf)

![wv](img/wv_2_9_1031.png)

### [Wyoming](img/wy_2_9_1031.pdf)

![wy](img/wy_2_9_1031.png)

## Comparing prevalence between states 

The following plots show the daily cases per 100,000 people in each state, grouped according to the 10 standard federal regions.

![prev](img/USA_2_9_1031_prevalence.png)

## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, case rates, hospitalizations, and deaths are forecast to continue to decline.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

