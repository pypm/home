## March 28, 2021 Analysis of USA state data

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

Below is a figure showing fits to
the ratio of the SGTF cases to non-SGTF cases used to estimate the selection coefficient
and current "frequency" of these cases.

![usa_v_r](img/usa_variant_ratio.png)

State | s | w |f_v (Mar 27)
---|---|---|---
Arizona|0.088 +/- 0.007|0.000 +/- 0.000|0.572 +/- 0.067
California|0.065 +/- 0.002|0.002 +/- 0.000|0.569 +/- 0.020
Florida|0.063 +/- 0.001|0.005 +/- 0.000|0.765 +/- 0.008
Georgia|0.091 +/- 0.003|0.001 +/- 0.000|0.838 +/- 0.013
Illinois|0.061 +/- 0.007|0.000 +/- 0.000|0.396 +/- 0.065
Indiana|0.090 +/- 0.005|0.001 +/- 0.000|0.604 +/- 0.037
Louisiana|0.112 +/- 0.020|0.002 +/- 0.001|0.833 +/- 0.077
Massachusetts|0.093 +/- 0.006|0.030 +/- 0.002|0.681 +/- 0.033
Michigan|0.096 +/- 0.005|0.000 +/- 0.000|0.861 +/- 0.014
Minnesota|0.090 +/- 0.009|0.001 +/- 0.000|0.839 +/- 0.035
North Carolina|0.087 +/- 0.004|0.001 +/- 0.000|0.587 +/- 0.034
New Jersey|0.063 +/- 0.009|0.000 +/- 0.001|0.534 +/- 0.092
New York|0.062 +/- 0.009|0.002 +/- 0.003|0.664 +/- 0.080
Pennsylvania|0.080 +/- 0.003|0.003 +/- 0.000|0.613 +/- 0.020
Texas|0.088 +/- 0.003|0.000 +/- 0.000|0.811 +/- 0.017

 * s: selection coefficient
 * w: SGTF false identification probability
 * f_v: fraction of cases due to the variant on March 27, 2021


## States with genomic data

The states with independent genomic data allow for better constraint on the growth advantage and current
case fraction.
With the variant potentially causing growth in the weeks to come, predictions for these states
are much better established.


### [Arizona](img/az_2_8_0328.pdf)

![az](img/az_2_8_0328.png)

### [California](img/ca_2_8_0328.pdf)

![ca](img/ca_2_8_0328.png)

### [Florida](img/fl_2_8_0328.pdf)

![fl](img/fl_2_8_0328.png)

### [Georgia](img/ga_2_8_0328.pdf)

![ga](img/ga_2_8_0328.png)

### [Illinois](img/il_2_8_0328.pdf)

![il](img/il_2_8_0328.png)

### [Indiana](img/in_2_8_0328.pdf)

![in](img/in_2_8_0328.png)

### [Louisiana](img/la_2_8_0328.pdf)

![la](img/la_2_8_0328.png)

### [Massachusetts](img/ma_2_8_0328.pdf)

![ma](img/ma_2_8_0328.png)

### [Michigan](img/mi_2_8_0328.pdf)

![mi](img/mi_2_8_0328.png)

### [Minnesota](img/mn_2_8_0328.pdf)

![mn](img/mn_2_8_0328.png)

### [North Carolina](img/nc_2_8_0328.pdf)

![nc](img/nc_2_8_0328.png)

### [New Jersey](img/nj_2_8_0328.pdf)

![nj](img/nj_2_8_0328.png)

### [New York](img/ny_2_8_0328.pdf)

![ny](img/ny_2_8_0328.png)

### [Pennsylvania](img/pa_2_8_0328.pdf)

![pa](img/pa_2_8_0328.png)

### [Texas](img/tx_2_8_0328.pdf)

![tx](img/tx_2_8_0328.png)


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

### [Alaska](img/ak_2_8_0328.pdf)

![ak](img/ak_2_8_0328.png)

### [Alabama](img/al_2_8_0328.pdf)

![al](img/al_2_8_0328.png)

### [Arkansas](img/ar_2_8_0328.pdf)

![ar](img/ar_2_8_0328.png)

### [Colorado](img/co_2_8_0328.pdf)

![co](img/co_2_8_0328.png)

### [Connecticut](img/ct_2_8_0328.pdf)

![ct](img/ct_2_8_0328.png)

### [District Of Columbia](img/dc_2_8_0328.pdf)

![dc](img/dc_2_8_0328.png)

### [Delaware](img/de_2_8_0328.pdf)

![de](img/de_2_8_0328.png)

### [Hawaii](img/hi_2_8_0328.pdf)

![hi](img/hi_2_8_0328.png)

### [Iowa](img/ia_2_8_0328.pdf)

![ia](img/ia_2_8_0328.png)

### [Idaho](img/id_2_8_0328.pdf)

![id](img/id_2_8_0328.png)

### [Kansas](img/ks_2_8_0328.pdf)

![ks](img/ks_2_8_0328.png)

### [Kentucky](img/ky_2_8_0328.pdf)

![ky](img/ky_2_8_0328.png)

### [Maryland](img/md_2_8_0328.pdf)

![md](img/md_2_8_0328.png)

### [Maine](img/me_2_8_0328.pdf)

![me](img/me_2_8_0328.png)

### [Missouri](img/mo_2_8_0328.pdf)

![mo](img/mo_2_8_0328.png)

### [Mississippi](img/ms_2_8_0328.pdf)

![ms](img/ms_2_8_0328.png)

### [Montana](img/mt_2_8_0328.pdf)

![mt](img/mt_2_8_0328.png)

### [North Dakota](img/nd_2_8_0328.pdf)

![nd](img/nd_2_8_0328.png)

### [Nebraska](img/ne_2_8_0328.pdf)

![ne](img/ne_2_8_0328.png)

### [New Hampshire](img/nh_2_8_0328.pdf)

![nh](img/nh_2_8_0328.png)

### [New Mexico](img/nm_2_8_0328.pdf)

![nm](img/nm_2_8_0328.png)

### [Nevada](img/nv_2_8_0328.pdf)

![nv](img/nv_2_8_0328.png)

### [Ohio](img/oh_2_8_0328.pdf)

![oh](img/oh_2_8_0328.png)

### [Oklahoma](img/ok_2_8_0328.pdf)

![ok](img/ok_2_8_0328.png)

### [Oregon](img/or_2_8_0328.pdf)

![or](img/or_2_8_0328.png)

### [Puerto Rico](img/pr_2_8_0328.pdf)

![pr](img/pr_2_8_0328.png)

### [Rhode Island](img/ri_2_8_0328.pdf)

![ri](img/ri_2_8_0328.png)

### [South Carolina](img/sc_2_8_0328.pdf)

![sc](img/sc_2_8_0328.png)

### [South Dakota](img/sd_2_8_0328.pdf)

![sd](img/sd_2_8_0328.png)

### [Tennessee](img/tn_2_8_0328.pdf)

![tn](img/tn_2_8_0328.png)

### [Utah](img/ut_2_8_0328.pdf)

![ut](img/ut_2_8_0328.png)

### [Virginia](img/va_2_8_0328.pdf)

![va](img/va_2_8_0328.png)

### [Vermont](img/vt_2_8_0328.pdf)

![vt](img/vt_2_8_0328.png)

### [Washington](img/wa_2_8_0328.pdf)

![wa](img/wa_2_8_0328.png)

### [Wisconsin](img/wi_2_8_0328.pdf)

![wi](img/wi_2_8_0328.png)

### [West Virginia](img/wv_2_8_0328.pdf)

![wv](img/wv_2_8_0328.png)

### [Wyoming](img/wy_2_8_0328.pdf)

![wy](img/wy_2_8_0328.png)

## Summary of growth rates (with and without immunity)

The following plots summarize the infection history.
The upper plot shows the daily growth/decline of infections (% per day) for the orginal strain.
The dashed curve are the growths that would have been experienced in absense of immunity.
Natural immunity built up during the course of the epidemic has helped reduce infections and
this is now being overtaken by vaccine immunity in many of the states.
Note that the daily growth rate for the B117 variant is typically 8% more than that of the original strain.

The lower plot shows an estimate of the contagious fraction of the population as a function of time.

### [Alabama](img/al-growth.pdf)

![al](img/al-growth.png)

### [Alaska](img/ak-growth.pdf)

![ak](img/ak-growth.png)

### [Arkansas](img/ar-growth.pdf)

![ar](img/ar-growth.png)

### [Arizona](img/az-growth.pdf)

![az](img/az-growth.png)

### [California](img/ca-growth.pdf)

![ca](img/ca-growth.png)

### [Colorado](img/co-growth.pdf)

![co](img/co-growth.png)

### [Connecticut](img/ct-growth.pdf)

![ct](img/ct-growth.png)

### [District Of Columbia](img/dc-growth.pdf)

![dc](img/dc-growth.png)

### [Delaware](img/de-growth.pdf)

![de](img/de-growth.png)

### [Florida](img/fl-growth.pdf)

![fl](img/fl-growth.png)

### [Georgia](img/ga-growth.pdf)

![ga](img/ga-growth.png)

### [Hawaii](img/hi-growth.pdf)

![hi](img/hi-growth.png)

### [Iowa](img/ia-growth.pdf)

![ia](img/ia-growth.png)

### [Idaho](img/id-growth.pdf)

![id](img/id-growth.png)

### [Illinois](img/il-growth.pdf)

![il](img/il-growth.png)

### [Indiana](img/in-growth.pdf)

![in](img/in-growth.png)

### [Kansas](img/ks-growth.pdf)

![ks](img/ks-growth.png)

### [Kentucky](img/ky-growth.pdf)

![ky](img/ky-growth.png)

### [Louisiana](img/la-growth.pdf)

![la](img/la-growth.png)

### [Massachusetts](img/ma-growth.pdf)

![ma](img/ma-growth.png)

### [Maryland](img/md-growth.pdf)

![md](img/md-growth.png)

### [Maine](img/me-growth.pdf)

![me](img/me-growth.png)

### [Michigan](img/mi-growth.pdf)

![mi](img/mi-growth.png)

### [Minnesota](img/mn-growth.pdf)

![mn](img/mn-growth.png)

### [Missouri](img/mo-growth.pdf)

![mo](img/mo-growth.png)

### [Mississippi](img/ms-growth.pdf)

![ms](img/ms-growth.png)

### [Montana](img/mt-growth.pdf)

![mt](img/mt-growth.png)

### [North Carolina](img/nc-growth.pdf)

![nc](img/nc-growth.png)

### [North Dakota](img/nd-growth.pdf)

![nd](img/nd-growth.png)

### [Nebraska](img/ne-growth.pdf)

![ne](img/ne-growth.png)

### [New Hampshire](img/nh-growth.pdf)

![nh](img/nh-growth.png)

### [New Jersey](img/nj-growth.pdf)

![nj](img/nj-growth.png)

### [New Mexico](img/nm-growth.pdf)

![nm](img/nm-growth.png)

### [Nevada](img/nv-growth.pdf)

![nv](img/nv-growth.png)

### [New York](img/ny-growth.pdf)

![ny](img/ny-growth.png)

### [Ohio](img/oh-growth.pdf)

![oh](img/oh-growth.png)

### [Oklahoma](img/ok-growth.pdf)

![ok](img/ok-growth.png)

### [Oregon](img/or-growth.pdf)

![or](img/or-growth.png)

### [Pennsylvania](img/pa-growth.pdf)

![pa](img/pa-growth.png)

### [Puerto Rico](img/pr-growth.pdf)

![pr](img/pr-growth.png)

### [Rhode Island](img/ri-growth.pdf)

![ri](img/ri-growth.png)

### [South Carolina](img/sc-growth.pdf)

![sc](img/sc-growth.png)

### [South Dakota](img/sd-growth.pdf)

![sd](img/sd-growth.png)

### [Tennessee](img/tn-growth.pdf)

![tn](img/tn-growth.png)

### [Texas](img/tx-growth.pdf)

![tx](img/tx-growth.png)

### [Utah](img/ut-growth.pdf)

![ut](img/ut-growth.png)

### [Vermont](img/vt-growth.pdf)

![vt](img/vt-growth.png)

### [Virginia](img/va-growth.pdf)

![va](img/va-growth.png)

### [Washington](img/wa-growth.pdf)

![wa](img/wa-growth.png)

### [Wisconsin](img/wi-growth.pdf)

![wi](img/wi-growth.png)

### [West Virginia](img/wv-growth.pdf)

![wv](img/wv-growth.png)

### [Wyoming](img/wy-growth.pdf)

![wy](img/wy-growth.png)

## Forecasts

The following plots show 4 week forecasts. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)

### [Alabama](img/al-forecast.pdf)

![al](img/al-forecast.png)

### [Alaska](img/ak-forecast.pdf)

![ak](img/ak-forecast.png)

### [Arkansas](img/ar-forecast.pdf)

![ar](img/ar-forecast.png)

### [Arizona](img/az-forecast.pdf)

![az](img/az-forecast.png)

### [California](img/ca-forecast.pdf)

![ca](img/ca-forecast.png)

### [Colorado](img/co-forecast.pdf)

![co](img/co-forecast.png)

### [Connecticut](img/ct-forecast.pdf)

![ct](img/ct-forecast.png)

### [District Of Columbia](img/dc-forecast.pdf)

![dc](img/dc-forecast.png)

### [Delaware](img/de-forecast.pdf)

![de](img/de-forecast.png)

### [Florida](img/fl-forecast.pdf)

![fl](img/fl-forecast.png)

### [Georgia](img/ga-forecast.pdf)

![ga](img/ga-forecast.png)

### [Hawaii](img/hi-forecast.pdf)

![hi](img/hi-forecast.png)

### [Iowa](img/ia-forecast.pdf)

![ia](img/ia-forecast.png)

### [Idaho](img/id-forecast.pdf)

![id](img/id-forecast.png)

### [Illinois](img/il-forecast.pdf)

![il](img/il-forecast.png)

### [Indiana](img/in-forecast.pdf)

![in](img/in-forecast.png)

### [Kansas](img/ks-forecast.pdf)

![ks](img/ks-forecast.png)

### [Kentucky](img/ky-forecast.pdf)

![ky](img/ky-forecast.png)

### [Louisiana](img/la-forecast.pdf)

![la](img/la-forecast.png)

### [Massachusetts](img/ma-forecast.pdf)

![ma](img/ma-forecast.png)

### [Maryland](img/md-forecast.pdf)

![md](img/md-forecast.png)

### [Maine](img/me-forecast.pdf)

![me](img/me-forecast.png)

### [Michigan](img/mi-forecast.pdf)

![mi](img/mi-forecast.png)

### [Minnesota](img/mn-forecast.pdf)

![mn](img/mn-forecast.png)

### [Missouri](img/mo-forecast.pdf)

![mo](img/mo-forecast.png)

### [Mississippi](img/ms-forecast.pdf)

![ms](img/ms-forecast.png)

### [Montana](img/mt-forecast.pdf)

![mt](img/mt-forecast.png)

### [North Carolina](img/nc-forecast.pdf)

![nc](img/nc-forecast.png)

### [North Dakota](img/nd-forecast.pdf)

![nd](img/nd-forecast.png)

### [Nebraska](img/ne-forecast.pdf)

![ne](img/ne-forecast.png)

### [New Hampshire](img/nh-forecast.pdf)

![nh](img/nh-forecast.png)

### [New Jersey](img/nj-forecast.pdf)

![nj](img/nj-forecast.png)

### [New Mexico](img/nm-forecast.pdf)

![nm](img/nm-forecast.png)

### [Nevada](img/nv-forecast.pdf)

![nv](img/nv-forecast.png)

### [New York](img/ny-forecast.pdf)

![ny](img/ny-forecast.png)

### [Ohio](img/oh-forecast.pdf)

![oh](img/oh-forecast.png)

### [Oklahoma](img/ok-forecast.pdf)

![ok](img/ok-forecast.png)

### [Oregon](img/or-forecast.pdf)

![or](img/or-forecast.png)

### [Pennsylvania](img/pa-forecast.pdf)

![pa](img/pa-forecast.png)

### [Puerto Rico](img/pr-forecast.pdf)

![pr](img/pr-forecast.png)

### [Rhode Island](img/ri-forecast.pdf)

![ri](img/ri-forecast.png)

### [South Carolina](img/sc-forecast.pdf)

![sc](img/sc-forecast.png)

### [South Dakota](img/sd-forecast.pdf)

![sd](img/sd-forecast.png)

### [Tennessee](img/tn-forecast.pdf)

![tn](img/tn-forecast.png)

### [Texas](img/tx-forecast.pdf)

![tx](img/tx-forecast.png)

### [Utah](img/ut-forecast.pdf)

![ut](img/ut-forecast.png)

### [Vermont](img/vt-forecast.pdf)

![vt](img/vt-forecast.png)

### [Virginia](img/va-forecast.pdf)

![va](img/va-forecast.png)

### [Washington](img/wa-forecast.pdf)

![wa](img/wa-forecast.png)

### [Wisconsin](img/wi-forecast.pdf)

![wi](img/wi-forecast.png)

### [West Virginia](img/wv-forecast.pdf)

![wv](img/wv-forecast.png)

### [Wyoming](img/wy-forecast.pdf)

![wy](img/wy-forecast.png)



## [return to case studies](../index.md)

