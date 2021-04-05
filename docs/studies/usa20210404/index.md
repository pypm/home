## April 4, 2021 Analysis of USA state data

## Individual state histories

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The data fits were done using data up until March 27, 2021.

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
The dashed curves separately show the reported cases from the original variant and the B117 variant.

Below the set of individual state plots, summary plots are provided that indicate the degree that
natural and vaccination immunization is helping to bring down infections.

The final set of plots show the 4 week forecast for the USA and for each state.

## Genomic data

For some staes, genomic screening [data](https://github.com/myhelix/helix-covid19db)
is available to estimate the growth advantage (aka selection coefficient, s)
of the B117 variant as well as the current fraction of cases dues to that variant.

Note that the last week fraction for several states is lower than expected. This could happen
if the samples are from an outbreak of non-SGTF cases, for example.

Below is a figure showing fits to
the ratio of the SGTF cases to non-SGTF cases used to estimate the selection coefficient
and current "frequency" of these cases.

![usa_v_r](img/usa_variant_ratio.png)

State | s | w |f_v (April 3)
---|---|---|---
Arizona|0.080 +/- 0.005|0.000 +/- 0.000|0.622 +/- 0.048
California|0.063 +/- 0.001|0.001 +/- 0.000|0.640 +/- 0.015
Florida|0.059 +/- 0.001|0.005 +/- 0.000|0.810 +/- 0.006
Georgia|0.087 +/- 0.002|0.001 +/- 0.000|0.891 +/- 0.008
Illinois|0.068 +/- 0.006|0.000 +/- 0.001|0.603 +/- 0.048
Indiana|0.093 +/- 0.004|0.001 +/- 0.000|0.766 +/- 0.020
Louisiana|0.103 +/- 0.013|0.002 +/- 0.001|0.882 +/- 0.044
Massachusetts|0.078 +/- 0.004|0.029 +/- 0.002|0.708 +/- 0.019
Michigan|0.083 +/- 0.003|0.000 +/- 0.000|0.882 +/- 0.008
Minnesota|0.082 +/- 0.006|0.001 +/- 0.000|0.875 +/- 0.020
North Carolina|0.082 +/- 0.003|0.000 +/- 0.000|0.672 +/- 0.022
New Jersey|0.062 +/- 0.007|0.000 +/- 0.001|0.622 +/- 0.057
New York|0.060 +/- 0.008|0.002 +/- 0.003|0.723 +/- 0.061
Pennsylvania|0.075 +/- 0.002|0.003 +/- 0.000|0.699 +/- 0.012
Texas|0.084 +/- 0.002|0.000 +/- 0.000|0.866 +/- 0.011

 * s: selection coefficient
 * w: SGTF false identification probability
 * f_v: fraction of cases due to the variant on March 27, 2021


## States with genomic data

The states with independent genomic data allow for better constraint on the growth advantage and current
case fraction.
With the variant potentially causing growth in the weeks to come, predictions for these states
are much better established.


### [Arizona](img/az_2_8_0404.pdf)

![az](img/az_2_8_0404.png)

### [California](img/ca_2_8_0404.pdf)

![ca](img/ca_2_8_0404.png)

### [Florida](img/fl_2_8_0404.pdf)

![fl](img/fl_2_8_0404.png)

### [Georgia](img/ga_2_8_0404.pdf)

![ga](img/ga_2_8_0404.png)

### [Illinois](img/il_2_8_0404.pdf)

![il](img/il_2_8_0404.png)

### [Indiana](img/in_2_8_0404.pdf)

![in](img/in_2_8_0404.png)

### [Louisiana](img/la_2_8_0404.pdf)

![la](img/la_2_8_0404.png)

### [Massachusetts](img/ma_2_8_0404.pdf)

![ma](img/ma_2_8_0404.png)

### [Michigan](img/mi_2_8_0404.pdf)

![mi](img/mi_2_8_0404.png)

### [Minnesota](img/mn_2_8_0404.pdf)

![mn](img/mn_2_8_0404.png)

### [North Carolina](img/nc_2_8_0404.pdf)

![nc](img/nc_2_8_0404.png)

### [New Jersey](img/nj_2_8_0404.pdf)

![nj](img/nj_2_8_0404.png)

### [New York](img/ny_2_8_0404.pdf)

![ny](img/ny_2_8_0404.png)

### [Pennsylvania](img/pa_2_8_0404.pdf)

![pa](img/pa_2_8_0404.png)

### [Texas](img/tx_2_8_0404.pdf)

![tx](img/tx_2_8_0404.png)


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

### [Alaska](img/ak_2_8_0404.pdf)

![ak](img/ak_2_8_0404.png)

### [Alabama](img/al_2_8_0404.pdf)

![al](img/al_2_8_0404.png)

### [Arkansas](img/ar_2_8_0404.pdf)

![ar](img/ar_2_8_0404.png)

### [Colorado](img/co_2_8_0404.pdf)

![co](img/co_2_8_0404.png)

### [Connecticut](img/ct_2_8_0404.pdf)

![ct](img/ct_2_8_0404.png)

### [District Of Columbia](img/dc_2_8_0404.pdf)

![dc](img/dc_2_8_0404.png)

### [Delaware](img/de_2_8_0404.pdf)

![de](img/de_2_8_0404.png)

### [Hawaii](img/hi_2_8_0404.pdf)

![hi](img/hi_2_8_0404.png)

### [Iowa](img/ia_2_8_0404.pdf)

![ia](img/ia_2_8_0404.png)

### [Idaho](img/id_2_8_0404.pdf)

![id](img/id_2_8_0404.png)

### [Kansas](img/ks_2_8_0404.pdf)

![ks](img/ks_2_8_0404.png)

### [Kentucky](img/ky_2_8_0404.pdf)

![ky](img/ky_2_8_0404.png)

### [Maryland](img/md_2_8_0404.pdf)

![md](img/md_2_8_0404.png)

### [Maine](img/me_2_8_0404.pdf)

![me](img/me_2_8_0404.png)

### [Missouri](img/mo_2_8_0404.pdf)

![mo](img/mo_2_8_0404.png)

### [Mississippi](img/ms_2_8_0404.pdf)

![ms](img/ms_2_8_0404.png)

### [Montana](img/mt_2_8_0404.pdf)

![mt](img/mt_2_8_0404.png)

### [North Dakota](img/nd_2_8_0404.pdf)

![nd](img/nd_2_8_0404.png)

### [Nebraska](img/ne_2_8_0404.pdf)

![ne](img/ne_2_8_0404.png)

### [New Hampshire](img/nh_2_8_0404.pdf)

![nh](img/nh_2_8_0404.png)

### [New Mexico](img/nm_2_8_0404.pdf)

![nm](img/nm_2_8_0404.png)

### [Nevada](img/nv_2_8_0404.pdf)

![nv](img/nv_2_8_0404.png)

### [Ohio](img/oh_2_8_0404.pdf)

![oh](img/oh_2_8_0404.png)

### [Oklahoma](img/ok_2_8_0404.pdf)

![ok](img/ok_2_8_0404.png)

### [Oregon](img/or_2_8_0404.pdf)

![or](img/or_2_8_0404.png)

### [Puerto Rico](img/pr_2_8_0404.pdf)

![pr](img/pr_2_8_0404.png)

### [Rhode Island](img/ri_2_8_0404.pdf)

![ri](img/ri_2_8_0404.png)

### [South Carolina](img/sc_2_8_0404.pdf)

![sc](img/sc_2_8_0404.png)

### [South Dakota](img/sd_2_8_0404.pdf)

![sd](img/sd_2_8_0404.png)

### [Tennessee](img/tn_2_8_0404.pdf)

![tn](img/tn_2_8_0404.png)

### [Utah](img/ut_2_8_0404.pdf)

![ut](img/ut_2_8_0404.png)

### [Virginia](img/va_2_8_0404.pdf)

![va](img/va_2_8_0404.png)

### [Vermont](img/vt_2_8_0404.pdf)

![vt](img/vt_2_8_0404.png)

### [Washington](img/wa_2_8_0404.pdf)

![wa](img/wa_2_8_0404.png)

### [Wisconsin](img/wi_2_8_0404.pdf)

![wi](img/wi_2_8_0404.png)

### [West Virginia](img/wv_2_8_0404.pdf)

![wv](img/wv_2_8_0404.png)

### [Wyoming](img/wy_2_8_0404.pdf)

![wy](img/wy_2_8_0404.png)


## Forecasts

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)

## Comparison with model fit to case data from 3 weeks ago

The following plots show 3 figures for each state
 * Left: case data available until March 14
 * Middle: case data fit on March 16. Red points show data collected after model fit
 * Right: case data fit on April 4.

For many states, the 2 strain model correctly predicted the rise following the plateau.
In several cases, the rise was predicted to come earlier than obsevered.
Without genomic data, the fraction of cases arising from B.1.1.7 is unknown before
observing the rise in cases.

### [Alabama](img/al_2_8_0404_cmp.pdf)

![al](img/al_2_8_0404_cmp.png)

### [Alaska](img/ak_2_8_0404_cmp.pdf)

![ak](img/ak_2_8_0404_cmp.png)

### [Arkansas](img/ar_2_8_0404_cmp.pdf)

![ar](img/ar_2_8_0404_cmp.png)

### [Arizona](img/az_2_8_0404_cmp.pdf)

![az](img/az_2_8_0404_cmp.png)

### [California](img/ca_2_8_0404_cmp.pdf)

![ca](img/ca_2_8_0404_cmp.png)

### [Colorado](img/co_2_8_0404_cmp.pdf)

![co](img/co_2_8_0404_cmp.png)

### [Connecticut](img/ct_2_8_0404_cmp.pdf)

![ct](img/ct_2_8_0404_cmp.png)

### [District Of Columbia](img/dc_2_8_0404_cmp.pdf)

![dc](img/dc_2_8_0404_cmp.png)

### [Delaware](img/de_2_8_0404_cmp.pdf)

![de](img/de_2_8_0404_cmp.png)

### [Florida](img/fl_2_8_0404_cmp.pdf)

![fl](img/fl_2_8_0404_cmp.png)

### [Georgia](img/ga_2_8_0404_cmp.pdf)

![ga](img/ga_2_8_0404_cmp.png)

### [Hawaii](img/hi_2_8_0404_cmp.pdf)

![hi](img/hi_2_8_0404_cmp.png)

### [Iowa](img/ia_2_8_0404_cmp.pdf)

![ia](img/ia_2_8_0404_cmp.png)

### [Idaho](img/id_2_8_0404_cmp.pdf)

![id](img/id_2_8_0404_cmp.png)

### [Illinois](img/il_2_8_0404_cmp.pdf)

![il](img/il_2_8_0404_cmp.png)

### [Indiana](img/in_2_8_0404_cmp.pdf)

![in](img/in_2_8_0404_cmp.png)

### [Kansas](img/ks_2_8_0404_cmp.pdf)

![ks](img/ks_2_8_0404_cmp.png)

### [Kentucky](img/ky_2_8_0404_cmp.pdf)

![ky](img/ky_2_8_0404_cmp.png)

### [Louisiana](img/la_2_8_0404_cmp.pdf)

![la](img/la_2_8_0404_cmp.png)

### [Massachusetts](img/ma_2_8_0404_cmp.pdf)

![ma](img/ma_2_8_0404_cmp.png)

### [Maryland](img/md_2_8_0404_cmp.pdf)

![md](img/md_2_8_0404_cmp.png)

### [Maine](img/me_2_8_0404_cmp.pdf)

![me](img/me_2_8_0404_cmp.png)

### [Michigan](img/mi_2_8_0404_cmp.pdf)

![mi](img/mi_2_8_0404_cmp.png)

### [Minnesota](img/mn_2_8_0404_cmp.pdf)

![mn](img/mn_2_8_0404_cmp.png)

### [Missouri](img/mo_2_8_0404_cmp.pdf)

![mo](img/mo_2_8_0404_cmp.png)

### [Mississippi](img/ms_2_8_0404_cmp.pdf)

![ms](img/ms_2_8_0404_cmp.png)

### [Montana](img/mt_2_8_0404_cmp.pdf)

![mt](img/mt_2_8_0404_cmp.png)

### [North Carolina](img/nc_2_8_0404_cmp.pdf)

![nc](img/nc_2_8_0404_cmp.png)

### [North Dakota](img/nd_2_8_0404_cmp.pdf)

![nd](img/nd_2_8_0404_cmp.png)

### [Nebraska](img/ne_2_8_0404_cmp.pdf)

![ne](img/ne_2_8_0404_cmp.png)

### [New Hampshire](img/nh_2_8_0404_cmp.pdf)

![nh](img/nh_2_8_0404_cmp.png)

### [New Jersey](img/nj_2_8_0404_cmp.pdf)

![nj](img/nj_2_8_0404_cmp.png)

### [New Mexico](img/nm_2_8_0404_cmp.pdf)

![nm](img/nm_2_8_0404_cmp.png)

### [Nevada](img/nv_2_8_0404_cmp.pdf)

![nv](img/nv_2_8_0404_cmp.png)

### [New York](img/ny_2_8_0404_cmp.pdf)

![ny](img/ny_2_8_0404_cmp.png)

### [Ohio](img/oh_2_8_0404_cmp.pdf)

![oh](img/oh_2_8_0404_cmp.png)

### [Oklahoma](img/ok_2_8_0404_cmp.pdf)

![ok](img/ok_2_8_0404_cmp.png)

### [Oregon](img/or_2_8_0404_cmp.pdf)

![or](img/or_2_8_0404_cmp.png)

### [Pennsylvania](img/pa_2_8_0404_cmp.pdf)

![pa](img/pa_2_8_0404_cmp.png)

### [Puerto Rico](img/pr_2_8_0404_cmp.pdf)

![pr](img/pr_2_8_0404_cmp.png)

### [Rhode Island](img/ri_2_8_0404_cmp.pdf)

![ri](img/ri_2_8_0404_cmp.png)

### [South Carolina](img/sc_2_8_0404_cmp.pdf)

![sc](img/sc_2_8_0404_cmp.png)

### [South Dakota](img/sd_2_8_0404_cmp.pdf)

![sd](img/sd_2_8_0404_cmp.png)

### [Tennessee](img/tn_2_8_0404_cmp.pdf)

![tn](img/tn_2_8_0404_cmp.png)

### [Texas](img/tx_2_8_0404_cmp.pdf)

![tx](img/tx_2_8_0404_cmp.png)

### [Utah](img/ut_2_8_0404_cmp.pdf)

![ut](img/ut_2_8_0404_cmp.png)

### [Vermont](img/vt_2_8_0404_cmp.pdf)

![vt](img/vt_2_8_0404_cmp.png)

### [Virginia](img/va_2_8_0404_cmp.pdf)

![va](img/va_2_8_0404_cmp.png)

### [Washington](img/wa_2_8_0404_cmp.pdf)

![wa](img/wa_2_8_0404_cmp.png)

### [Wisconsin](img/wi_2_8_0404_cmp.pdf)

![wi](img/wi_2_8_0404_cmp.png)

### [West Virginia](img/wv_2_8_0404_cmp.pdf)

![wv](img/wv_2_8_0404_cmp.png)

### [Wyoming](img/wy_2_8_0404_cmp.pdf)

![wy](img/wy_2_8_0404_cmp.png)


## [return to case studies](../index.md)

