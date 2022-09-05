## September 4, 2022 Analysis of US state data

This report shows the result of analyses that use hospital admission data to estimate
the transmission rates in the past few months to characterize the recent Omicron waves.
Hospital admission data are used, to avoid testing capacity issues and to
better predict future hospital admission rates.

The modelling approach for US states has now changed to follow the approach first
applied in July for European nations.
See this [link](../eu20220717/index.md) for more information.

The European nations in the study were chosen for the distinct BA.2 wave which allowed
critical aspects of population-level immunity to be measured from the data:
* the population-level immunity at the start of the BA.2 wave
* the rate at which immunity grew with every hospital admission

Few US states had a distinct BA.2 wave, and so the identical approach cannot be applied.
Instead, information from the previous models (that included the entire time history)
was transferred to the new models that contain now history prior to 2022,
and mimic the initial population immunity as arising from natural infections
occuring near the beginning of 2022.
Since the turnover of waves results from the growth in immunity from infections,
the rate to which immunity grows is effectively measured by fit of the model parameters
to the data, assuming constant transmission rates.

As seen in the recent European analyses, immunity waning appears to be a significant
effect, and the same waning parameters are fit in the US data.
Given the lack of the well established BA.2 wave to calibrate immunity, the
waning parameter estimates may not be directly comparable to those from Europe.

In the figures below, the small dots show daily values, and
the larger circles are weekly averages to help guide the eye.
There are no changes to transmission rates (normally shown by dashed vertical lines)
within the time periods shown below. Each strain has just 2 parameters (transmission rate and timing).

### Individual state hospitalization analyses

The plots for each state below show the daily hospital admissions and deaths since April
on a linear scale (left) and log scale (right).
Cases are also included on the right.
BA.4 and BA.5 are combined into one strain, labelled BA.5.
For some states, the combination of BA.2, BA.4 and BA.5 are combined in one strain, labelled BA.5.

The projections below show a significant resurgance for some states.
These are not definitive predictions, but instead 
is an indication of the sensitivity on the degree to which immunity wanes, which is not yet well established.

### [Alaska](img/ak_4_4_0904.pdf)

![ak](img/ak_4_4_0904.png)

### [Alabama](img/al_4_4_0904.pdf)

![al](img/al_4_4_0904.png)

### [Arkansas](img/ar_4_4_0904.pdf)

![ar](img/ar_4_4_0904.png)

### [Arizona](img/az_4_4_0904.pdf)

![az](img/az_4_4_0904.png)

### [California](img/ca_4_4_0904.pdf)

![ca](img/ca_4_4_0904.png)

### [Colorado](img/co_4_4_0904.pdf)

![co](img/co_4_4_0904.png)

### [Connecticut](img/ct_4_4_0904.pdf)

![ct](img/ct_4_4_0904.png)

### [District Of Columbia](img/dc_4_4_0904.pdf)

![dc](img/dc_4_4_0904.png)

### [Delaware](img/de_4_4_0904.pdf)

![de](img/de_4_4_0904.png)

### [Florida](img/fl_4_4_0904.pdf)

![fl](img/fl_4_4_0904.png)

### [Georgia](img/ga_4_4_0904.pdf)

![ga](img/ga_4_4_0904.png)

### [Hawaii](img/hi_4_4_0904.pdf)

![hi](img/hi_4_4_0904.png)

### [Iowa](img/ia_4_4_0904.pdf)

![ia](img/ia_4_4_0904.png)

### [Idaho](img/id_4_4_0904.pdf)

![id](img/id_4_4_0904.png)

### [Illinois](img/il_4_4_0904.pdf)

![il](img/il_4_4_0904.png)

### [Indiana](img/in_4_4_0904.pdf)

![in](img/in_4_4_0904.png)

### [Kansas](img/ks_4_4_0904.pdf)

![ks](img/ks_4_4_0904.png)

### [Kentucky](img/ky_4_4_0904.pdf)

![ky](img/ky_4_4_0904.png)

### [Louisiana](img/la_4_4_0904.pdf)

![la](img/la_4_4_0904.png)

### [Massachusetts](img/ma_4_4_0904.pdf)

![ma](img/ma_4_4_0904.png)

### [Maryland](img/md_4_4_0904.pdf)

![md](img/md_4_4_0904.png)

### [Maine](img/me_4_4_0904.pdf)

![me](img/me_4_4_0904.png)

### [Michigan](img/mi_4_4_0904.pdf)

![mi](img/mi_4_4_0904.png)

### [Minnesota](img/mn_4_4_0904.pdf)

![mn](img/mn_4_4_0904.png)

### [Missouri](img/mo_4_4_0904.pdf)

![mo](img/mo_4_4_0904.png)

### [Mississippi](img/ms_4_4_0904.pdf)

![ms](img/ms_4_4_0904.png)

### [Montana](img/mt_4_4_0904.pdf)

![mt](img/mt_4_4_0904.png)

### [North Carolina](img/nc_4_4_0904.pdf)

![nc](img/nc_4_4_0904.png)

### [North Dakota](img/nd_4_4_0904.pdf)

![nd](img/nd_4_4_0904.png)

### [Nebraska](img/ne_4_4_0904.pdf)

![ne](img/ne_4_4_0904.png)

### [New Hampshire](img/nh_4_4_0904.pdf)

![nh](img/nh_4_4_0904.png)

### [New Jersey](img/nj_4_4_0904.pdf)

![nj](img/nj_4_4_0904.png)

### [New Mexico](img/nm_4_4_0904.pdf)

![nm](img/nm_4_4_0904.png)

### [Nevada](img/nv_4_4_0904.pdf)

![nv](img/nv_4_4_0904.png)

### [New York](img/ny_4_4_0904.pdf)

![ny](img/ny_4_4_0904.png)

### [Ohio](img/oh_4_4_0904.pdf)

![oh](img/oh_4_4_0904.png)

### [Oklahoma](img/ok_4_4_0904.pdf)

![ok](img/ok_4_4_0904.png)

### [Oregon](img/or_4_4_0904.pdf)

![or](img/or_4_4_0904.png)

### [Pennsylvania](img/pa_4_4_0904.pdf)

![pa](img/pa_4_4_0904.png)

### [Puerto Rico](img/pr_4_4_0904.pdf)

![pr](img/pr_4_4_0904.png)

### [Rhode Island](img/ri_4_4_0904.pdf)

![ri](img/ri_4_4_0904.png)

### [South Carolina](img/sc_4_4_0904.pdf)

![sc](img/sc_4_4_0904.png)

### [South Dakota](img/sd_4_4_0904.pdf)

![sd](img/sd_4_4_0904.png)

### [Tennessee](img/tn_4_4_0904.pdf)

![tn](img/tn_4_4_0904.png)

### [Texas](img/tx_4_4_0904.pdf)

![tx](img/tx_4_4_0904.png)

### [Utah](img/ut_4_4_0904.pdf)

![ut](img/ut_4_4_0904.png)

### [Virginia](img/va_4_4_0904.pdf)

![va](img/va_4_4_0904.png)

### [Vermont](img/vt_4_4_0904.pdf)

![vt](img/vt_4_4_0904.png)

### [Washington](img/wa_4_4_0904.pdf)

![wa](img/wa_4_4_0904.png)

### [Wisconsin](img/wi_4_4_0904.pdf)

![wi](img/wi_4_4_0904.png)

### [West Virginia](img/wv_4_4_0904.pdf)

![wv](img/wv_4_4_0904.png)

### [Wyoming](img/wy_4_4_0904.pdf)

![wy](img/wy_4_4_0904.png)

## [return to case studies](../index.md)

