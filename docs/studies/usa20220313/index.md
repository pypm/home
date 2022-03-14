## March 13, 2022 Analysis of US state data

The characteristic Omicron signature of rapid growth in cases and hospital admissions,
was followed by a dramatic reduction in growth rate near the end of 2021, as reported
in previous reports.
Infection rates have declined significantly over the past several weeks.

This report shows the result of analyses that use hospital admission data to estimate
the transmission rate following the rapid transition to lower growth rate.
The only parameters adjusted are the transmission rates 
and normalization constants.
Hospital admission data are used, to avoid testing capacity issues and to
better predict future hospital admission rates.
For some states, the model for cases differs significantly from case data.

## Rapid reduction in Omicron growth rates

As usual, the infection model is defined by fitting the model to the case data, and the
hospitalization and deaths models are derived from the infection model.
To estimate the transmission rates of Omicron in 2022 hospital admission data
are used.

The Omicron variant is assumed to have a much larger susceptible population, due to its
ability to evade immunity (natural and vaccination immunity). 
For this study, those immunized against earlier strains only have 20% effective immunity
against omicron.

Booster doses have been included in this analysis, and are assumed to raise the
vaccine effectiveness from 20% to 80% with a time delay given by a gamma distribution with
mean 10 days and standard deviation 5 days.
The Omicron variant is also assumed to produce more infections that go undetected as cases
(as compard to Delta).

The green points are the daily cases, the grey points the daily hospitalizations, 
The larger circles are weekly averages to help guide the eye.

The vertical dashed lines show where the transmission rate is changed.
If the susceptible fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline.
With immunity growing, the curves bend downwards due to the herd effect.

### Individual state hospitalization analyses

The plots for each state below show the case, hospital admisions, and deaths data since
October 15 2021, on a linear scale (left) and log scale (right).
The right figures show how the model attributes cases from Delta and Omicron infections,
and the hospital admissions from Omicron infections.
Omicron hospital admissions make a useful metric to compare 
the growth of Omicron across different states, removing
the widely variable Delta hospital admissions.

The left plots also show the hospital admission model curves from previous projections (2 and 4 weeks ago)
(February 13 and 27), to show the degree of variability when new data is included.
For most states the previous weeks' model projections agree with the recent data.
With the rapid drop in infection rates, the decay of daily hospital admissions has much to do with the
long tail in the time delay between infection and hospital admission (reported in the August 10, 2021 report).
As a result the sensitivity to recent changes in transmission rate (relaxation or BA.2) is reduced.

The model is able to describe data from the states by introducing a transition to lower
transmission rate near the end of December 2021.
This introduces a kink in the log scale plots (as constant transmission rate
corresponds to straight lines, if population immunity is roughly constant).
For several states, a transition is included in February to improve the model fit to data.

Following the individual state plots, summaries of all states are shown below.

### [Alaska](img/ak_4_2_0313.pdf)

![ak](img/ak_4_2_0313.png)

### [Alabama](img/al_4_2_0313.pdf)

![al](img/al_4_2_0313.png)

### [Arkansas](img/ar_4_2_0313.pdf)

![ar](img/ar_4_2_0313.png)

### [Arizona](img/az_4_2_0313.pdf)

![az](img/az_4_2_0313.png)

### [California](img/ca_4_2_0313.pdf)

![ca](img/ca_4_2_0313.png)

### [Colorado](img/co_4_2_0313.pdf)

![co](img/co_4_2_0313.png)

### [Connecticut](img/ct_4_2_0313.pdf)

![ct](img/ct_4_2_0313.png)

### [District Of Columbia](img/dc_4_2_0313.pdf)

![dc](img/dc_4_2_0313.png)

### [Delaware](img/de_4_2_0313.pdf)

![de](img/de_4_2_0313.png)

### [Florida](img/fl_4_2_0313.pdf)

![fl](img/fl_4_2_0313.png)

### [Georgia](img/ga_4_2_0313.pdf)

![ga](img/ga_4_2_0313.png)

### [Hawaii](img/hi_4_2_0313.pdf)

![hi](img/hi_4_2_0313.png)

### [Iowa](img/ia_4_2_0313.pdf)

![ia](img/ia_4_2_0313.png)

### [Idaho](img/id_4_2_0313.pdf)

![id](img/id_4_2_0313.png)

### [Illinois](img/il_4_2_0313.pdf)

![il](img/il_4_2_0313.png)

### [Indiana](img/in_4_2_0313.pdf)

![in](img/in_4_2_0313.png)

### [Kansas](img/ks_4_2_0313.pdf)

![ks](img/ks_4_2_0313.png)

### [Kentucky](img/ky_4_2_0313.pdf)

![ky](img/ky_4_2_0313.png)

### [Louisiana](img/la_4_2_0313.pdf)

![la](img/la_4_2_0313.png)

### [Massachusetts](img/ma_4_2_0313.pdf)

![ma](img/ma_4_2_0313.png)

### [Maryland](img/md_4_2_0313.pdf)

![md](img/md_4_2_0313.png)

### [Maine](img/me_4_2_0313.pdf)

![me](img/me_4_2_0313.png)

### [Michigan](img/mi_4_2_0313.pdf)

![mi](img/mi_4_2_0313.png)

### [Minnesota](img/mn_4_2_0313.pdf)

![mn](img/mn_4_2_0313.png)

### [Missouri](img/mo_4_2_0313.pdf)

![mo](img/mo_4_2_0313.png)

### [Mississippi](img/ms_4_2_0313.pdf)

![ms](img/ms_4_2_0313.png)

### [Montana](img/mt_4_2_0313.pdf)

![mt](img/mt_4_2_0313.png)

### [North Carolina](img/nc_4_2_0313.pdf)

![nc](img/nc_4_2_0313.png)

### [North Dakota](img/nd_4_2_0313.pdf)

![nd](img/nd_4_2_0313.png)

### [Nebraska](img/ne_4_2_0313.pdf)

![ne](img/ne_4_2_0313.png)

### [New Hampshire](img/nh_4_2_0313.pdf)

![nh](img/nh_4_2_0313.png)

### [New Jersey](img/nj_4_2_0313.pdf)

![nj](img/nj_4_2_0313.png)

### [New Mexico](img/nm_4_2_0313.pdf)

![nm](img/nm_4_2_0313.png)

### [Nevada](img/nv_4_2_0313.pdf)

![nv](img/nv_4_2_0313.png)

### [New York](img/ny_4_2_0313.pdf)

![ny](img/ny_4_2_0313.png)

### [Ohio](img/oh_4_2_0313.pdf)

![oh](img/oh_4_2_0313.png)

### [Oklahoma](img/ok_4_2_0313.pdf)

![ok](img/ok_4_2_0313.png)

### [Oregon](img/or_4_2_0313.pdf)

![or](img/or_4_2_0313.png)

### [Pennsylvania](img/pa_4_2_0313.pdf)

![pa](img/pa_4_2_0313.png)

### [Puerto Rico](img/pr_4_2_0313.pdf)

![pr](img/pr_4_2_0313.png)

### [Rhode Island](img/ri_4_2_0313.pdf)

![ri](img/ri_4_2_0313.png)

### [South Carolina](img/sc_4_2_0313.pdf)

![sc](img/sc_4_2_0313.png)

### [South Dakota](img/sd_4_2_0313.pdf)

![sd](img/sd_4_2_0313.png)

### [Tennessee](img/tn_4_2_0313.pdf)

![tn](img/tn_4_2_0313.png)

### [Texas](img/tx_4_2_0313.pdf)

![tx](img/tx_4_2_0313.png)

### [Utah](img/ut_4_2_0313.pdf)

![ut](img/ut_4_2_0313.png)

### [Virginia](img/va_4_2_0313.pdf)

![va](img/va_4_2_0313.png)

### [Vermont](img/vt_4_2_0313.pdf)

![vt](img/vt_4_2_0313.png)

### [Washington](img/wa_4_2_0313.pdf)

![wa](img/wa_4_2_0313.png)

### [Wisconsin](img/wi_4_2_0313.pdf)

![wi](img/wi_4_2_0313.png)

### [West Virginia](img/wv_4_2_0313.pdf)

![wv](img/wv_4_2_0313.png)

### [Wyoming](img/wy_4_2_0313.pdf)

![wy](img/wy_4_2_0313.png)

## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)

## [return to case studies](../index.md)

