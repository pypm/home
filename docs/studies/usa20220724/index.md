## July 24, 2022 Analysis of US state data

This report shows the result of analyses that use hospital admission data to estimate
the transmission rates in the past few months to characterize the recent Omicron waves.
The only parameters adjusted are the transmission rates 
and normalization constants.
Hospital admission data are used, to avoid testing capacity issues and to
better predict future hospital admission rates.

The Omicron variants are assumed to have a much larger susceptible population, due to its
ability to evade immunity (natural and vaccination immunity). 
For this study, those immunized against earlier strains only have 20% effective immunity
against omicron.

Booster doses have been included in this analysis, and are assumed to raise the
vaccine effectiveness from 20% to 80% with a time delay given by a gamma distribution with
mean 10 days and standard deviation 5 days.
The Omicron variants are also assumed to produce more infections that go undetected as cases
(as compard to Delta).

In the figures below, the small dots show daily values, and
the larger circles are weekly averages to help guide the eye.

The vertical dashed lines show where the transmission rate is changed in the model to better fit the data.
Few changes to transmission rate are needed.
If the susceptible fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline.
With immunity growing, the curves bend downwards due to the herd effect.

With the large number of BA.1 infections providing natural immunity, the model predicted
turn-overs in hospital admissions in BA.2 in the previous report.
The new Omicron variants (BA.4 and BA.5) are combined as a new strain in this analysis, and labelled as BA.45.
The strength of the BA.45 wave that is apparent in the data forces the model to
reduce natural immunity from the earlier Omicron infections.
For these analyses, the natural immunity from Omicron infections wanes with a mean time
of 200 days.

There are a number of assumptions made to characterize population immunity and as a result
these forecasts have a great deal of uncertainty.

### Individual state hospitalization analyses

The plots for each state below show the daily hospital admissions and deaths since early February
on a linear scale (left) and log scale (right).
The figures show how the model attributes admissions from Delta and Omicron infections.
For some states, the new BA.45 strain is not yet included in the model.

For most states, BA.4 and 5 rose to dominance before the BA.2 wave had subsided and as a result
the hospital admission data does not show a separate wave for BA.45.
For some states, the separation is evident (Eg. Michigan, New York, and others).

### [Alaska](img/ak_4_4_0724.pdf)

![ak](img/ak_4_4_0724.png)

### [Alabama](img/al_4_4_0724.pdf)

![al](img/al_4_4_0724.png)

### [Arkansas](img/ar_4_4_0724.pdf)

![ar](img/ar_4_4_0724.png)

### [Arizona](img/az_4_4_0724.pdf)

![az](img/az_4_4_0724.png)

### [California](img/ca_4_4_0724.pdf)

![ca](img/ca_4_4_0724.png)

### [Colorado](img/co_4_4_0724.pdf)

![co](img/co_4_4_0724.png)

### [Connecticut](img/ct_4_4_0724.pdf)

![ct](img/ct_4_4_0724.png)

### [District Of Columbia](img/dc_4_4_0724.pdf)

![dc](img/dc_4_4_0724.png)

### [Delaware](img/de_4_4_0724.pdf)

![de](img/de_4_4_0724.png)

### [Florida](img/fl_4_4_0724.pdf)

![fl](img/fl_4_4_0724.png)

### [Georgia](img/ga_4_4_0724.pdf)

![ga](img/ga_4_4_0724.png)

### [Hawaii](img/hi_4_4_0724.pdf)

![hi](img/hi_4_4_0724.png)

### [Iowa](img/ia_4_4_0724.pdf)

![ia](img/ia_4_4_0724.png)

### [Idaho](img/id_4_4_0724.pdf)

![id](img/id_4_4_0724.png)

### [Illinois](img/il_4_4_0724.pdf)

![il](img/il_4_4_0724.png)

### [Indiana](img/in_4_4_0724.pdf)

![in](img/in_4_4_0724.png)

### [Kansas](img/ks_4_4_0724.pdf)

![ks](img/ks_4_4_0724.png)

### [Kentucky](img/ky_4_4_0724.pdf)

![ky](img/ky_4_4_0724.png)

### [Louisiana](img/la_4_4_0724.pdf)

![la](img/la_4_4_0724.png)

### [Massachusetts](img/ma_4_4_0724.pdf)

![ma](img/ma_4_4_0724.png)

### [Maryland](img/md_4_4_0724.pdf)

![md](img/md_4_4_0724.png)

### [Maine](img/me_4_4_0724.pdf)

![me](img/me_4_4_0724.png)

### [Michigan](img/mi_4_4_0724.pdf)

![mi](img/mi_4_4_0724.png)

### [Minnesota](img/mn_4_4_0724.pdf)

![mn](img/mn_4_4_0724.png)

### [Missouri](img/mo_4_4_0724.pdf)

![mo](img/mo_4_4_0724.png)

### [Mississippi](img/ms_4_4_0724.pdf)

![ms](img/ms_4_4_0724.png)

### [Montana](img/mt_4_4_0724.pdf)

![mt](img/mt_4_4_0724.png)

### [North Carolina](img/nc_4_4_0724.pdf)

![nc](img/nc_4_4_0724.png)

### [North Dakota](img/nd_4_4_0724.pdf)

![nd](img/nd_4_4_0724.png)

### [Nebraska](img/ne_4_4_0724.pdf)

![ne](img/ne_4_4_0724.png)

### [New Hampshire](img/nh_4_4_0724.pdf)

![nh](img/nh_4_4_0724.png)

### [New Jersey](img/nj_4_4_0724.pdf)

![nj](img/nj_4_4_0724.png)

### [New Mexico](img/nm_4_4_0724.pdf)

![nm](img/nm_4_4_0724.png)

### [Nevada](img/nv_4_4_0724.pdf)

![nv](img/nv_4_4_0724.png)

### [New York](img/ny_4_4_0724.pdf)

![ny](img/ny_4_4_0724.png)

### [Ohio](img/oh_4_4_0724.pdf)

![oh](img/oh_4_4_0724.png)

### [Oklahoma](img/ok_4_4_0724.pdf)

![ok](img/ok_4_4_0724.png)

### [Oregon](img/or_4_4_0724.pdf)

![or](img/or_4_4_0724.png)

### [Pennsylvania](img/pa_4_4_0724.pdf)

![pa](img/pa_4_4_0724.png)

### [Puerto Rico](img/pr_4_4_0724.pdf)

![pr](img/pr_4_4_0724.png)

### [Rhode Island](img/ri_4_4_0724.pdf)

![ri](img/ri_4_4_0724.png)

### [South Carolina](img/sc_4_4_0724.pdf)

![sc](img/sc_4_4_0724.png)

### [South Dakota](img/sd_4_4_0724.pdf)

![sd](img/sd_4_4_0724.png)

### [Tennessee](img/tn_4_4_0724.pdf)

![tn](img/tn_4_4_0724.png)

### [Texas](img/tx_4_4_0724.pdf)

![tx](img/tx_4_4_0724.png)

### [Utah](img/ut_4_4_0724.pdf)

![ut](img/ut_4_4_0724.png)

### [Virginia](img/va_4_4_0724.pdf)

![va](img/va_4_4_0724.png)

### [Vermont](img/vt_4_4_0724.pdf)

![vt](img/vt_4_4_0724.png)

### [Washington](img/wa_4_4_0724.pdf)

![wa](img/wa_4_4_0724.png)

### [Wisconsin](img/wi_4_4_0724.pdf)

![wi](img/wi_4_4_0724.png)

### [West Virginia](img/wv_4_4_0724.pdf)

![wv](img/wv_4_4_0724.png)

### [Wyoming](img/wy_4_4_0724.pdf)

![wy](img/wy_4_4_0724.png)

## [return to case studies](../index.md)

