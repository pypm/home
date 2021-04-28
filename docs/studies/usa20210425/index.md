## April 25, 2021 Analysis of USA state data

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until April 24, 2021.

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

At the bottom of this page, plots showing the combined forecast for the US is shown.

## Genomic data

For some staes, genomic screening [data](https://github.com/myhelix/helix-covid19db)
using the SGTF protocol,
is available to estimate the growth advantage (aka selection coefficient, s)
of the B117 variant as well as the current fraction of cases dues to that variant.

Recently in several states, the  SGTF/non-SGTF ratio is no longer growing exponentially, which
is likely due to other variants of concern with a similar growth advantage but which are not
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

State | s | rpb| w |f_v (Apr 25)
---|---|---|---|---
Arizona|0.086 +/- 0.007|0.605 +/- 0.150|0.000 +/- 0.000|0.957 +/- 0.022
California|0.071 +/- 0.002|0.636 +/- 0.056|0.002 +/- 0.000|0.960 +/- 0.008
Florida|0.073 +/- 0.001|0.393 +/- 0.014|0.006 +/- 0.000|0.987 +/- 0.002
Georgia|0.099 +/- 0.003|0.272 +/- 0.020|0.001 +/- 0.000|0.994 +/- 0.001
Illinois|0.073 +/- 0.007|0.375 +/- 0.136|0.000 +/- 0.001|0.926 +/- 0.033
Indiana|0.103 +/- 0.005|0.339 +/- 0.036|0.001 +/- 0.000|0.985 +/- 0.004
Louisiana|0.124 +/- 0.026|0.352 +/- 0.095|0.002 +/- 0.001|0.993 +/- 0.013
Massachusetts|0.123 +/- 0.009|0.993 +/- 0.055|0.031 +/- 0.002|0.998 +/- 0.001
Michigan|0.107 +/- 0.005|0.215 +/- 0.012|0.001 +/- 0.000|0.996 +/- 0.001
Minnesota|0.094 +/- 0.008|0.168 +/- 0.033|0.001 +/- 0.000|0.990 +/- 0.005
North Carolina|0.092 +/- 0.004|0.464 +/- 0.053|0.001 +/- 0.000|0.973 +/- 0.007
New Jersey|0.069 +/- 0.010|0.428 +/- 0.216|0.000 +/- 0.001|0.928 +/- 0.046
New York|0.092 +/- 0.019|1.261 +/- 0.239|0.004 +/- 0.004|0.994 +/- 0.008
Pennsylvania|0.094 +/- 0.003|0.667 +/- 0.031|0.003 +/- 0.000|0.987 +/- 0.003
Texas|0.097 +/- 0.003|0.352 +/- 0.031|0.000 +/- 0.000|0.993 +/- 0.002

 * s: selection coefficient
 * rpb: ratio of other VoC to B.1.1.7
 * w: SGTF false identification of VoC per sample
 * f_v: fraction of cases due to variants of concern on April 25, 2021


## States with genomic data

The states with independent genomic data allow for better constraint on the growth advantage and current
case fraction.
With the variant potentially causing growth in the weeks to come, predictions for these states
are much better established.


### [Arizona](img/az_2_8_0425.pdf)

![az](img/az_2_8_0425.png)

### [California](img/ca_2_8_0425.pdf)

![ca](img/ca_2_8_0425.png)

### [Florida](img/fl_2_8_0425.pdf)

![fl](img/fl_2_8_0425.png)

### [Georgia](img/ga_2_8_0425.pdf)

![ga](img/ga_2_8_0425.png)

### [Illinois](img/il_2_8_0425.pdf)

![il](img/il_2_8_0425.png)

### [Indiana](img/in_2_8_0425.pdf)

![in](img/in_2_8_0425.png)

### [Louisiana](img/la_2_8_0425.pdf)

![la](img/la_2_8_0425.png)

### [Massachusetts](img/ma_2_8_0425.pdf)

![ma](img/ma_2_8_0425.png)

### [Michigan](img/mi_2_8_0425.pdf)

![mi](img/mi_2_8_0425.png)

### [Minnesota](img/mn_2_8_0425.pdf)

![mn](img/mn_2_8_0425.png)

### [North Carolina](img/nc_2_8_0425.pdf)

![nc](img/nc_2_8_0425.png)

### [New Jersey](img/nj_2_8_0425.pdf)

![nj](img/nj_2_8_0425.png)

### [New York](img/ny_2_8_0425.pdf)

![ny](img/ny_2_8_0425.png)

### [Pennsylvania](img/pa_2_8_0425.pdf)

![pa](img/pa_2_8_0425.png)

### [Texas](img/tx_2_8_0425.pdf)

![tx](img/tx_2_8_0425.png)


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

### [Alaska](img/ak_2_8_0425.pdf)

![ak](img/ak_2_8_0425.png)

### [Alabama](img/al_2_8_0425.pdf)

![al](img/al_2_8_0425.png)

### [Arkansas](img/ar_2_8_0425.pdf)

![ar](img/ar_2_8_0425.png)

### [Colorado](img/co_2_8_0425.pdf)

![co](img/co_2_8_0425.png)

### [Connecticut](img/ct_2_8_0425.pdf)

![ct](img/ct_2_8_0425.png)

### [District Of Columbia](img/dc_2_8_0425.pdf)

![dc](img/dc_2_8_0425.png)

### [Delaware](img/de_2_8_0425.pdf)

![de](img/de_2_8_0425.png)

### [Hawaii](img/hi_2_8_0425.pdf)

![hi](img/hi_2_8_0425.png)

### [Iowa](img/ia_2_8_0425.pdf)

![ia](img/ia_2_8_0425.png)

### [Idaho](img/id_2_8_0425.pdf)

![id](img/id_2_8_0425.png)

### [Kansas](img/ks_2_8_0425.pdf)

![ks](img/ks_2_8_0425.png)

### [Kentucky](img/ky_2_8_0425.pdf)

![ky](img/ky_2_8_0425.png)

### [Maryland](img/md_2_8_0425.pdf)

![md](img/md_2_8_0425.png)

### [Maine](img/me_2_8_0425.pdf)

![me](img/me_2_8_0425.png)

### [Missouri](img/mo_2_8_0425.pdf)

![mo](img/mo_2_8_0425.png)

### [Mississippi](img/ms_2_8_0425.pdf)

![ms](img/ms_2_8_0425.png)

### [Montana](img/mt_2_8_0425.pdf)

![mt](img/mt_2_8_0425.png)

### [North Dakota](img/nd_2_8_0425.pdf)

![nd](img/nd_2_8_0425.png)

### [Nebraska](img/ne_2_8_0425.pdf)

![ne](img/ne_2_8_0425.png)

### [New Hampshire](img/nh_2_8_0425.pdf)

![nh](img/nh_2_8_0425.png)

### [New Mexico](img/nm_2_8_0425.pdf)

![nm](img/nm_2_8_0425.png)

### [Nevada](img/nv_2_8_0425.pdf)

![nv](img/nv_2_8_0425.png)

### [Ohio](img/oh_2_8_0425.pdf)

![oh](img/oh_2_8_0425.png)

### [Oklahoma](img/ok_2_8_0425.pdf)

![ok](img/ok_2_8_0425.png)

### [Oregon](img/or_2_8_0425.pdf)

![or](img/or_2_8_0425.png)

### [Puerto Rico](img/pr_2_8_0425.pdf)

![pr](img/pr_2_8_0425.png)

### [Rhode Island](img/ri_2_8_0425.pdf)

![ri](img/ri_2_8_0425.png)

### [South Carolina](img/sc_2_8_0425.pdf)

![sc](img/sc_2_8_0425.png)

### [South Dakota](img/sd_2_8_0425.pdf)

![sd](img/sd_2_8_0425.png)

### [Tennessee](img/tn_2_8_0425.pdf)

![tn](img/tn_2_8_0425.png)

### [Utah](img/ut_2_8_0425.pdf)

![ut](img/ut_2_8_0425.png)

### [Virginia](img/va_2_8_0425.pdf)

![va](img/va_2_8_0425.png)

### [Vermont](img/vt_2_8_0425.pdf)

![vt](img/vt_2_8_0425.png)

### [Washington](img/wa_2_8_0425.pdf)

![wa](img/wa_2_8_0425.png)

### [Wisconsin](img/wi_2_8_0425.pdf)

![wi](img/wi_2_8_0425.png)

### [West Virginia](img/wv_2_8_0425.pdf)

![wv](img/wv_2_8_0425.png)

### [Wyoming](img/wy_2_8_0425.pdf)

![wy](img/wy_2_8_0425.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)


## [return to case studies](../index.md)

