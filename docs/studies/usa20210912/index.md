## September 12, 2021 Analysis of USA state data

Summary: After many weeks with rapid growth in cases (more that six weeks
after the delta variant became dominant), most states are turning around,
as the herd effect begins to take effect.
Some states, such as Louisiana, what had a significant turnaround
as a result of mask mandates or other measures.

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until September 11, 2021.

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

For this analysis, a long tail in the delay time between symptoms and hospital admission is
included - which improves the model fits to hospitalization data.
Now with this correction, the data appear to be
consistent with the hypothesis that hospitalization probability is roughly constant
(for most states).

The dashed curves separately show the reported cases from the original strains and from variants of
concern, divided into two types B.1.1.7 (alpha) and B.1.617.2 (delta).

At the bottom of this page, plots showing the combined forecast for the US are shown.

### [Alaska](img/ak_2_9_0912.pdf)

![ak](img/ak_2_9_0912.png)

### [Alabama](img/al_2_9_0912.pdf)

![al](img/al_2_9_0912.png)

### [Arkansas](img/ar_2_9_0912.pdf)

![ar](img/ar_2_9_0912.png)

### [Arizona](img/az_2_9_0912.pdf)

![az](img/az_2_9_0912.png)

### [California](img/ca_2_9_0912.pdf)

![ca](img/ca_2_9_0912.png)

### [Colorado](img/co_2_9_0912.pdf)

![co](img/co_2_9_0912.png)

### [Connecticut](img/ct_2_9_0912.pdf)

![ct](img/ct_2_9_0912.png)

### [District Of Columbia](img/dc_2_9_0912.pdf)

![dc](img/dc_2_9_0912.png)

### [Delaware](img/de_2_9_0912.pdf)

![de](img/de_2_9_0912.png)

### [Florida](img/fl_2_9_0912.pdf)

![fl](img/fl_2_9_0912.png)

### [Georgia](img/ga_2_9_0912.pdf)

![ga](img/ga_2_9_0912.png)

### [Hawaii](img/hi_2_9_0912.pdf)

![hi](img/hi_2_9_0912.png)

### [Iowa](img/ia_2_9_0912.pdf)

![ia](img/ia_2_9_0912.png)

### [Idaho](img/id_2_9_0912.pdf)

![id](img/id_2_9_0912.png)

### [Illinois](img/il_2_9_0912.pdf)

![il](img/il_2_9_0912.png)

### [Indiana](img/in_2_9_0912.pdf)

![in](img/in_2_9_0912.png)

### [Kansas](img/ks_2_9_0912.pdf)

![ks](img/ks_2_9_0912.png)

### [Kentucky](img/ky_2_9_0912.pdf)

![ky](img/ky_2_9_0912.png)

### [Louisiana](img/la_2_9_0912.pdf)

![la](img/la_2_9_0912.png)

### [Massachusetts](img/ma_2_9_0912.pdf)

![ma](img/ma_2_9_0912.png)

### [Maryland](img/md_2_9_0912.pdf)

![md](img/md_2_9_0912.png)

### [Maine](img/me_2_9_0912.pdf)

![me](img/me_2_9_0912.png)

### [Michigan](img/mi_2_9_0912.pdf)

![mi](img/mi_2_9_0912.png)

### [Minnesota](img/mn_2_9_0912.pdf)

![mn](img/mn_2_9_0912.png)

### [Missouri](img/mo_2_9_0912.pdf)

![mo](img/mo_2_9_0912.png)

### [Mississippi](img/ms_2_9_0912.pdf)

![ms](img/ms_2_9_0912.png)

### [Montana](img/mt_2_9_0912.pdf)

![mt](img/mt_2_9_0912.png)

### [North Carolina](img/nc_2_9_0912.pdf)

![nc](img/nc_2_9_0912.png)

### [North Dakota](img/nd_2_9_0912.pdf)

![nd](img/nd_2_9_0912.png)

### [Nebraska](img/ne_2_9_0912.pdf)

![ne](img/ne_2_9_0912.png)

### [New Hampshire](img/nh_2_9_0912.pdf)

![nh](img/nh_2_9_0912.png)

### [New Jersey](img/nj_2_9_0912.pdf)

![nj](img/nj_2_9_0912.png)

### [New Mexico](img/nm_2_9_0912.pdf)

![nm](img/nm_2_9_0912.png)

### [Nevada](img/nv_2_9_0912.pdf)

![nv](img/nv_2_9_0912.png)

### [New York](img/ny_2_9_0912.pdf)

![ny](img/ny_2_9_0912.png)

### [Ohio](img/oh_2_9_0912.pdf)

![oh](img/oh_2_9_0912.png)

### [Oklahoma](img/ok_2_9_0912.pdf)

![ok](img/ok_2_9_0912.png)

### [Oregon](img/or_2_9_0912.pdf)

![or](img/or_2_9_0912.png)

### [Pennsylvania](img/pa_2_9_0912.pdf)

![pa](img/pa_2_9_0912.png)

### [Puerto Rico](img/pr_2_9_0912.pdf)

![pr](img/pr_2_9_0912.png)

### [Rhode Island](img/ri_2_9_0912.pdf)

![ri](img/ri_2_9_0912.png)

### [South Carolina](img/sc_2_9_0912.pdf)

![sc](img/sc_2_9_0912.png)

### [South Dakota](img/sd_2_9_0912.pdf)

![sd](img/sd_2_9_0912.png)

### [Tennessee](img/tn_2_9_0912.pdf)

![tn](img/tn_2_9_0912.png)

### [Texas](img/tx_2_9_0912.pdf)

![tx](img/tx_2_9_0912.png)

### [Utah](img/ut_2_9_0912.pdf)

![ut](img/ut_2_9_0912.png)

### [Virginia](img/va_2_9_0912.pdf)

![va](img/va_2_9_0912.png)

### [Vermont](img/vt_2_9_0912.pdf)

![vt](img/vt_2_9_0912.png)

### [Washington](img/wa_2_9_0912.pdf)

![wa](img/wa_2_9_0912.png)

### [Wisconsin](img/wi_2_9_0912.pdf)

![wi](img/wi_2_9_0912.png)

### [West Virginia](img/wv_2_9_0912.pdf)

![wv](img/wv_2_9_0912.png)

### [Wyoming](img/wy_2_9_0912.pdf)

![wy](img/wy_2_9_0912.png)


## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, case rates are forecast to be declining.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

