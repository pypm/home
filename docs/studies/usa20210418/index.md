## April 18, 2021 Analysis of USA state data

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until April 17, 2021.

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
The dashed curves separately show the reported cases from the original strain and from variants of concern.

The final set of plots show a comparison of forecasts from 5 weeks ago
with the most recent data.

## Genomic data

For some staes, genomic screening [data](https://github.com/myhelix/helix-covid19db)
using the SGTF protocol,
is available to estimate the growth advantage (aka selection coefficient, s)
of the B117 variant as well as the current fraction of cases dues to that variant.

Recently in several states, the  SGTF/non-SGTF ratio is no longer growing exponentially, which
could be due to other variants of concern with a similar growth advantage but which are not
tagged by SGTF.

Below is a figure showing fits to
the ratio of the SGTF cases to non-SGTF cases which is used
used to estimate the selection coefficient (s),
the ratio of other VoC to the B.1.1.7 (rpb), and
the current fraction of cases due to variants of concern (f_v).

The curves are the best fit, the shaded region indicates the 95% central interval of the ensemble of
curves (modifying the parameters according to their covariance) and the vertical bars are the
central 95% intervals for each binomial sampling.

![usa_v_r](img/usa_variant_ratio_p.png)

region | s | rpb| w |f_v (Apr 18)
---|---|---|---|---
Arizona|0.086 +/- 0.008|0.538 +/- 0.241|0.000 +/- 0.000|0.920 +/- 0.043
California|0.071 +/- 0.002|0.633 +/- 0.076|0.002 +/- 0.000|0.936 +/- 0.013
Florida|0.074 +/- 0.002|0.396 +/- 0.018|0.006 +/- 0.000|0.978 +/- 0.003
Georgia|0.098 +/- 0.003|0.255 +/- 0.026|0.001 +/- 0.000|0.987 +/- 0.003
Illinois|0.071 +/- 0.007|0.270 +/- 0.179|0.000 +/- 0.001|0.869 +/- 0.051
Indiana|0.098 +/- 0.005|0.264 +/- 0.053|0.001 +/- 0.000|0.959 +/- 0.011
Louisiana|0.127 +/- 0.028|0.387 +/- 0.118|0.002 +/- 0.001|0.989 +/- 0.017
Massachusetts|0.121 +/- 0.010|0.964 +/- 0.071|0.030 +/- 0.002|0.994 +/- 0.003
Michigan|0.107 +/- 0.005|0.220 +/- 0.015|0.001 +/- 0.000|0.992 +/- 0.002
Minnesota|0.096 +/- 0.010|0.186 +/- 0.043|0.001 +/- 0.000|0.983 +/- 0.010
North Carolina|0.091 +/- 0.004|0.413 +/- 0.075|0.001 +/- 0.000|0.945 +/- 0.015
New Jersey|0.071 +/- 0.010|0.515 +/- 0.254|0.000 +/- 0.001|0.914 +/- 0.054
New York|0.085 +/- 0.018|1.054 +/- 0.286|0.004 +/- 0.004|0.983 +/- 0.023
Pennsylvania|0.095 +/- 0.004|0.677 +/- 0.040|0.003 +/- 0.001|0.976 +/- 0.005
Texas|0.099 +/- 0.004|0.400 +/- 0.041|0.000 +/- 0.000|0.989 +/- 0.003

 * s: selection coefficient
 * rpb: ratio of other VoC to B.1.1.7
 * w: SGTF false identification of VoC per sample
 * f_v: fraction of cases due to variants of concern on April 18, 2021


## States with genomic data

The states with independent genomic data allow for better constraint on the growth advantage and current
case fraction.
With the variant potentially causing growth in the weeks to come, predictions for these states
are much better established.


### [Arizona](img/az_2_8_0418.pdf)

![az](img/az_2_8_0418.png)

### [California](img/ca_2_8_0418.pdf)

![ca](img/ca_2_8_0418.png)

### [Florida](img/fl_2_8_0418.pdf)

![fl](img/fl_2_8_0418.png)

### [Georgia](img/ga_2_8_0418.pdf)

![ga](img/ga_2_8_0418.png)

### [Illinois](img/il_2_8_0418.pdf)

![il](img/il_2_8_0418.png)

### [Indiana](img/in_2_8_0418.pdf)

![in](img/in_2_8_0418.png)

### [Louisiana](img/la_2_8_0418.pdf)

![la](img/la_2_8_0418.png)

### [Massachusetts](img/ma_2_8_0418.pdf)

![ma](img/ma_2_8_0418.png)

### [Michigan](img/mi_2_8_0418.pdf)

![mi](img/mi_2_8_0418.png)

### [Minnesota](img/mn_2_8_0418.pdf)

![mn](img/mn_2_8_0418.png)

### [North Carolina](img/nc_2_8_0418.pdf)

![nc](img/nc_2_8_0418.png)

### [New Jersey](img/nj_2_8_0418.pdf)

![nj](img/nj_2_8_0418.png)

### [New York](img/ny_2_8_0418.pdf)

![ny](img/ny_2_8_0418.png)

### [Pennsylvania](img/pa_2_8_0418.pdf)

![pa](img/pa_2_8_0418.png)

### [Texas](img/tx_2_8_0418.pdf)

![tx](img/tx_2_8_0418.png)


## States without genomic data

In absence of genomic data, the growth advantage s = 0.08 is assumed. The current strength of the B117
is estimated from the fit to case data.
Essentially this is derived by how fare the case data deviate from the expected trajectory for the original
strain model (orange dashed curve).
For states where the deviation is just beginning, there will be significant uncertainty on the
timing of the next peak.

These model fits assume that there is no change to NPI (non-pharmiceutical intervention) between the
vertical dotted lines.
Such NPI changes can lead to large changes in the projections for the future growth of the variant.

### [Alaska](img/ak_2_8_0418.pdf)

![ak](img/ak_2_8_0418.png)

### [Alabama](img/al_2_8_0418.pdf)

![al](img/al_2_8_0418.png)

### [Arkansas](img/ar_2_8_0418.pdf)

![ar](img/ar_2_8_0418.png)

### [Colorado](img/co_2_8_0418.pdf)

![co](img/co_2_8_0418.png)

### [Connecticut](img/ct_2_8_0418.pdf)

![ct](img/ct_2_8_0418.png)

### [District Of Columbia](img/dc_2_8_0418.pdf)

![dc](img/dc_2_8_0418.png)

### [Delaware](img/de_2_8_0418.pdf)

![de](img/de_2_8_0418.png)

### [Hawaii](img/hi_2_8_0418.pdf)

![hi](img/hi_2_8_0418.png)

### [Iowa](img/ia_2_8_0418.pdf)

![ia](img/ia_2_8_0418.png)

### [Idaho](img/id_2_8_0418.pdf)

![id](img/id_2_8_0418.png)

### [Kansas](img/ks_2_8_0418.pdf)

![ks](img/ks_2_8_0418.png)

### [Kentucky](img/ky_2_8_0418.pdf)

![ky](img/ky_2_8_0418.png)

### [Maryland](img/md_2_8_0418.pdf)

![md](img/md_2_8_0418.png)

### [Maine](img/me_2_8_0418.pdf)

![me](img/me_2_8_0418.png)

### [Missouri](img/mo_2_8_0418.pdf)

![mo](img/mo_2_8_0418.png)

### [Mississippi](img/ms_2_8_0418.pdf)

![ms](img/ms_2_8_0418.png)

### [Montana](img/mt_2_8_0418.pdf)

![mt](img/mt_2_8_0418.png)

### [North Dakota](img/nd_2_8_0418.pdf)

![nd](img/nd_2_8_0418.png)

### [Nebraska](img/ne_2_8_0418.pdf)

![ne](img/ne_2_8_0418.png)

### [New Hampshire](img/nh_2_8_0418.pdf)

![nh](img/nh_2_8_0418.png)

### [New Mexico](img/nm_2_8_0418.pdf)

![nm](img/nm_2_8_0418.png)

### [Nevada](img/nv_2_8_0418.pdf)

![nv](img/nv_2_8_0418.png)

### [Ohio](img/oh_2_8_0418.pdf)

![oh](img/oh_2_8_0418.png)

### [Oklahoma](img/ok_2_8_0418.pdf)

![ok](img/ok_2_8_0418.png)

### [Oregon](img/or_2_8_0418.pdf)

![or](img/or_2_8_0418.png)

### [Puerto Rico](img/pr_2_8_0418.pdf)

![pr](img/pr_2_8_0418.png)

### [Rhode Island](img/ri_2_8_0418.pdf)

![ri](img/ri_2_8_0418.png)

### [South Carolina](img/sc_2_8_0418.pdf)

![sc](img/sc_2_8_0418.png)

### [South Dakota](img/sd_2_8_0418.pdf)

![sd](img/sd_2_8_0418.png)

### [Tennessee](img/tn_2_8_0418.pdf)

![tn](img/tn_2_8_0418.png)

### [Utah](img/ut_2_8_0418.pdf)

![ut](img/ut_2_8_0418.png)

### [Virginia](img/va_2_8_0418.pdf)

![va](img/va_2_8_0418.png)

### [Vermont](img/vt_2_8_0418.pdf)

![vt](img/vt_2_8_0418.png)

### [Washington](img/wa_2_8_0418.pdf)

![wa](img/wa_2_8_0418.png)

### [Wisconsin](img/wi_2_8_0418.pdf)

![wi](img/wi_2_8_0418.png)

### [West Virginia](img/wv_2_8_0418.pdf)

![wv](img/wv_2_8_0418.png)

### [Wyoming](img/wy_2_8_0418.pdf)

![wy](img/wy_2_8_0418.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)

## Comparison with model fit to case data from 5 weeks ago

The following plots show 3 figures for each state
 * Left: case data available until March 14
 * Middle: case data fit on March 16. Red points show data collected after model fit
 * Right: case data fit on April 18.

For many states, the 2 strain model correctly predicted the rise following the plateau.
In several cases, the rise was predicted to come earlier than obsevered.
Without genomic data, the fraction of cases arising from variants of concern is unknown before
observing the rise in cases.

### [Alabama](img/al_2_8_0418_cmp.pdf)

![al](img/al_2_8_0418_cmp.png)

### [Alaska](img/ak_2_8_0418_cmp.pdf)

![ak](img/ak_2_8_0418_cmp.png)

### [Arkansas](img/ar_2_8_0418_cmp.pdf)

![ar](img/ar_2_8_0418_cmp.png)

### [Arizona](img/az_2_8_0418_cmp.pdf)

![az](img/az_2_8_0418_cmp.png)

### [California](img/ca_2_8_0418_cmp.pdf)

![ca](img/ca_2_8_0418_cmp.png)

### [Colorado](img/co_2_8_0418_cmp.pdf)

![co](img/co_2_8_0418_cmp.png)

### [Connecticut](img/ct_2_8_0418_cmp.pdf)

![ct](img/ct_2_8_0418_cmp.png)

### [District Of Columbia](img/dc_2_8_0418_cmp.pdf)

![dc](img/dc_2_8_0418_cmp.png)

### [Delaware](img/de_2_8_0418_cmp.pdf)

![de](img/de_2_8_0418_cmp.png)

### [Florida](img/fl_2_8_0418_cmp.pdf)

![fl](img/fl_2_8_0418_cmp.png)

### [Georgia](img/ga_2_8_0418_cmp.pdf)

![ga](img/ga_2_8_0418_cmp.png)

### [Hawaii](img/hi_2_8_0418_cmp.pdf)

![hi](img/hi_2_8_0418_cmp.png)

### [Iowa](img/ia_2_8_0418_cmp.pdf)

![ia](img/ia_2_8_0418_cmp.png)

### [Idaho](img/id_2_8_0418_cmp.pdf)

![id](img/id_2_8_0418_cmp.png)

### [Illinois](img/il_2_8_0418_cmp.pdf)

![il](img/il_2_8_0418_cmp.png)

### [Indiana](img/in_2_8_0418_cmp.pdf)

![in](img/in_2_8_0418_cmp.png)

### [Kansas](img/ks_2_8_0418_cmp.pdf)

![ks](img/ks_2_8_0418_cmp.png)

### [Kentucky](img/ky_2_8_0418_cmp.pdf)

![ky](img/ky_2_8_0418_cmp.png)

### [Louisiana](img/la_2_8_0418_cmp.pdf)

![la](img/la_2_8_0418_cmp.png)

### [Massachusetts](img/ma_2_8_0418_cmp.pdf)

![ma](img/ma_2_8_0418_cmp.png)

### [Maryland](img/md_2_8_0418_cmp.pdf)

![md](img/md_2_8_0418_cmp.png)

### [Maine](img/me_2_8_0418_cmp.pdf)

![me](img/me_2_8_0418_cmp.png)

### [Michigan](img/mi_2_8_0418_cmp.pdf)

![mi](img/mi_2_8_0418_cmp.png)

### [Minnesota](img/mn_2_8_0418_cmp.pdf)

![mn](img/mn_2_8_0418_cmp.png)

### [Missouri](img/mo_2_8_0418_cmp.pdf)

![mo](img/mo_2_8_0418_cmp.png)

### [Mississippi](img/ms_2_8_0418_cmp.pdf)

![ms](img/ms_2_8_0418_cmp.png)

### [Montana](img/mt_2_8_0418_cmp.pdf)

![mt](img/mt_2_8_0418_cmp.png)

### [North Carolina](img/nc_2_8_0418_cmp.pdf)

![nc](img/nc_2_8_0418_cmp.png)

### [North Dakota](img/nd_2_8_0418_cmp.pdf)

![nd](img/nd_2_8_0418_cmp.png)

### [Nebraska](img/ne_2_8_0418_cmp.pdf)

![ne](img/ne_2_8_0418_cmp.png)

### [New Hampshire](img/nh_2_8_0418_cmp.pdf)

![nh](img/nh_2_8_0418_cmp.png)

### [New Jersey](img/nj_2_8_0418_cmp.pdf)

![nj](img/nj_2_8_0418_cmp.png)

### [New Mexico](img/nm_2_8_0418_cmp.pdf)

![nm](img/nm_2_8_0418_cmp.png)

### [Nevada](img/nv_2_8_0418_cmp.pdf)

![nv](img/nv_2_8_0418_cmp.png)

### [New York](img/ny_2_8_0418_cmp.pdf)

![ny](img/ny_2_8_0418_cmp.png)

### [Ohio](img/oh_2_8_0418_cmp.pdf)

![oh](img/oh_2_8_0418_cmp.png)

### [Oklahoma](img/ok_2_8_0418_cmp.pdf)

![ok](img/ok_2_8_0418_cmp.png)

### [Oregon](img/or_2_8_0418_cmp.pdf)

![or](img/or_2_8_0418_cmp.png)

### [Pennsylvania](img/pa_2_8_0418_cmp.pdf)

![pa](img/pa_2_8_0418_cmp.png)

### [Puerto Rico](img/pr_2_8_0418_cmp.pdf)

![pr](img/pr_2_8_0418_cmp.png)

### [Rhode Island](img/ri_2_8_0418_cmp.pdf)

![ri](img/ri_2_8_0418_cmp.png)

### [South Carolina](img/sc_2_8_0418_cmp.pdf)

![sc](img/sc_2_8_0418_cmp.png)

### [South Dakota](img/sd_2_8_0418_cmp.pdf)

![sd](img/sd_2_8_0418_cmp.png)

### [Tennessee](img/tn_2_8_0418_cmp.pdf)

![tn](img/tn_2_8_0418_cmp.png)

### [Texas](img/tx_2_8_0418_cmp.pdf)

![tx](img/tx_2_8_0418_cmp.png)

### [Utah](img/ut_2_8_0418_cmp.pdf)

![ut](img/ut_2_8_0418_cmp.png)

### [Vermont](img/vt_2_8_0418_cmp.pdf)

![vt](img/vt_2_8_0418_cmp.png)

### [Virginia](img/va_2_8_0418_cmp.pdf)

![va](img/va_2_8_0418_cmp.png)

### [Washington](img/wa_2_8_0418_cmp.pdf)

![wa](img/wa_2_8_0418_cmp.png)

### [Wisconsin](img/wi_2_8_0418_cmp.pdf)

![wi](img/wi_2_8_0418_cmp.png)

### [West Virginia](img/wv_2_8_0418_cmp.pdf)

![wv](img/wv_2_8_0418_cmp.png)

### [Wyoming](img/wy_2_8_0418_cmp.pdf)

![wy](img/wy_2_8_0418_cmp.png)


## [return to case studies](../index.md)

