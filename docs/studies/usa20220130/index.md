## January 30, 2022 Analysis of US state data

The characteristic Omicron signature of rapid growth in cases and hospital admissions,
has been visible in all US states for several weeks.
This was followed by a dramatic reduction in growth rate near the end of December, as reported
in previous reports.
Many states are now past the peak in daily cases and hospital admissions.

This report shows the result of analyses that use hospital admission data to estimate
the transmission rate following the rapid transition to lower growth rate.
The only parameters adjusted are the current transmission rate (assumed constant since
the transition near the end of December), and normalization constants.
Hospital admission data are used, to avoid testing capacity issues and to
better predict future hospital admission rates.

## Rapid reduction in Omicron growth rates

As usual, the infection model is defined by fitting the model to the case data, and the
hospitalization and deaths models are derived from the infection model.
To estimate the current transmission rate of Omicron, however, hospital admission data
are used.

The Omicron variant is assumed to have a much larger susceptible population, due to its
ability to evade immunity (natural and vaccination immunity). 
For this study, those immunized against earlier strains only have 20% effective immunity
against omicron.

Booster doses have been included in this analysis, and are assumed to raise the
vaccine effectiveness from 20% to 80% with a time delay given by a gamma distribution with
mean 10 days and standard deviation 5 days.

The Omicron variant is also assumed to produce more infections that go undetected as cases.
The reporting fraction of omicron infections is assumed to be 0.6 times that of Delta infections.
This has the effect of reducing peak infection and hospitalization rates.
The scaling of the reporting fraction had been 0.4 in previous analyses of US data, 
but is changed to 0.6, given the inclusion of boosters in the model, which increases
population immunity.

The green points are the daily cases, the grey points the daily hospitalizations, 
The larger circles are weekly averages to help guide the eye.

The case data are used to define the periods for which transmission rate appears to be constant.
The vertical dashed lines show where the transmission rate is changed.
If the susceptible fraction is constant (immunity not changing quickly), constant transmission rates
lead to steady exponential growth or decline.
With immunity growing, the curves bend downwards due to the herd effect.
Interpretting the growth of Omicron with changing Delta rates growth rates leads to additional
uncertainty in the interpretations.

### Individual state hospitalization analyses

The plots for each state below show the case, hospital admisions, and deaths data since
October 15 2021, on a linear scale (left) and log scale (right).
The right figures show how the model attributes cases from Delta and Omicron infections,
and the hospital admissions from Omicron infections.
Omicron hospital admissions make a useful metric to compare 
the growth of Omicron across different states, removing
the widely variable Delta hospital admissions.

The left plots also show the hospital admission model curves from the previous week's analysis,
to show the degree of variability when new data is included.
For those states where peak hospital admission was reached more than a week ago, the
new model projections are typically close to the previous week's projection, as expected.

The model is able to describe data from the states by introducing a transition to lower
transmission rate near the end of December 2021.
This introduces a kink in the log scale plots (as constant transmission rate
corresponds to straight lines, if population immunity is roughly constant).

Following the individual state plots, summaries of all states are shown below.

### [Alaska](img/ak_4_2_0130.pdf)

![ak](img/ak_4_2_0130.png)

### [Alabama](img/al_4_2_0130.pdf)

![al](img/al_4_2_0130.png)

### [Arkansas](img/ar_4_2_0130.pdf)

![ar](img/ar_4_2_0130.png)

### [Arizona](img/az_4_2_0130.pdf)

![az](img/az_4_2_0130.png)

### [California](img/ca_4_2_0130.pdf)

![ca](img/ca_4_2_0130.png)

### [Colorado](img/co_4_2_0130.pdf)

![co](img/co_4_2_0130.png)

### [Connecticut](img/ct_4_2_0130.pdf)

![ct](img/ct_4_2_0130.png)

### [District Of Columbia](img/dc_4_2_0130.pdf)

![dc](img/dc_4_2_0130.png)

### [Delaware](img/de_4_2_0130.pdf)

![de](img/de_4_2_0130.png)

### [Florida](img/fl_4_2_0130.pdf)

![fl](img/fl_4_2_0130.png)

### [Georgia](img/ga_4_2_0130.pdf)

![ga](img/ga_4_2_0130.png)

### [Hawaii](img/hi_4_2_0130.pdf)

![hi](img/hi_4_2_0130.png)

### [Iowa](img/ia_4_2_0130.pdf)

![ia](img/ia_4_2_0130.png)

### [Idaho](img/id_4_2_0130.pdf)

![id](img/id_4_2_0130.png)

### [Illinois](img/il_4_2_0130.pdf)

![il](img/il_4_2_0130.png)

### [Indiana](img/in_4_2_0130.pdf)

![in](img/in_4_2_0130.png)

### [Kansas](img/ks_4_2_0130.pdf)

![ks](img/ks_4_2_0130.png)

### [Kentucky](img/ky_4_2_0130.pdf)

![ky](img/ky_4_2_0130.png)

### [Louisiana](img/la_4_2_0130.pdf)

![la](img/la_4_2_0130.png)

### [Massachusetts](img/ma_4_2_0130.pdf)

![ma](img/ma_4_2_0130.png)

### [Maryland](img/md_4_2_0130.pdf)

![md](img/md_4_2_0130.png)

### [Maine](img/me_4_2_0130.pdf)

![me](img/me_4_2_0130.png)

### [Michigan](img/mi_4_2_0130.pdf)

![mi](img/mi_4_2_0130.png)

### [Minnesota](img/mn_4_2_0130.pdf)

![mn](img/mn_4_2_0130.png)

### [Missouri](img/mo_4_2_0130.pdf)

![mo](img/mo_4_2_0130.png)

### [Mississippi](img/ms_4_2_0130.pdf)

![ms](img/ms_4_2_0130.png)

### [Montana](img/mt_4_2_0130.pdf)

![mt](img/mt_4_2_0130.png)

### [North Carolina](img/nc_4_2_0130.pdf)

![nc](img/nc_4_2_0130.png)

### [North Dakota](img/nd_4_2_0130.pdf)

![nd](img/nd_4_2_0130.png)

### [Nebraska](img/ne_4_2_0130.pdf)

![ne](img/ne_4_2_0130.png)

### [New Hampshire](img/nh_4_2_0130.pdf)

![nh](img/nh_4_2_0130.png)

### [New Jersey](img/nj_4_2_0130.pdf)

![nj](img/nj_4_2_0130.png)

### [New Mexico](img/nm_4_2_0130.pdf)

![nm](img/nm_4_2_0130.png)

### [Nevada](img/nv_4_2_0130.pdf)

![nv](img/nv_4_2_0130.png)

### [New York](img/ny_4_2_0130.pdf)

![ny](img/ny_4_2_0130.png)

### [Ohio](img/oh_4_2_0130.pdf)

![oh](img/oh_4_2_0130.png)

### [Oklahoma](img/ok_4_2_0130.pdf)

![ok](img/ok_4_2_0130.png)

### [Oregon](img/or_4_2_0130.pdf)

![or](img/or_4_2_0130.png)

### [Pennsylvania](img/pa_4_2_0130.pdf)

![pa](img/pa_4_2_0130.png)

### [Puerto Rico](img/pr_4_2_0130.pdf)

![pr](img/pr_4_2_0130.png)

### [Rhode Island](img/ri_4_2_0130.pdf)

![ri](img/ri_4_2_0130.png)

### [South Carolina](img/sc_4_2_0130.pdf)

![sc](img/sc_4_2_0130.png)

### [South Dakota](img/sd_4_2_0130.pdf)

![sd](img/sd_4_2_0130.png)

### [Tennessee](img/tn_4_2_0130.pdf)

![tn](img/tn_4_2_0130.png)

### [Texas](img/tx_4_2_0130.pdf)

![tx](img/tx_4_2_0130.png)

### [Utah](img/ut_4_2_0130.pdf)

![ut](img/ut_4_2_0130.png)

### [Virginia](img/va_4_2_0130.pdf)

![va](img/va_4_2_0130.png)

### [Vermont](img/vt_4_2_0130.pdf)

![vt](img/vt_4_2_0130.png)

### [Washington](img/wa_4_2_0130.pdf)

![wa](img/wa_4_2_0130.png)

### [Wisconsin](img/wi_4_2_0130.pdf)

![wi](img/wi_4_2_0130.png)

### [West Virginia](img/wv_4_2_0130.pdf)

![wv](img/wv_4_2_0130.png)

### [Wyoming](img/wy_4_2_0130.pdf)

![wy](img/wy_4_2_0130.png)


## Comparisons of Omicron daily hospital admissions

Hospital admissions can be used in a per-capita comparison of infections between states,
avoiding potential issues with test capacity.
Using Omicron hospital admissions removes the variability of the Delta hospital admissions taking
place during the emergence of Omicron.
This metric relies on a model to attribute hospital admissions during the phase when Delta contributes
a substantial fraction of hospital admissions.

The plot below shows this metric, aligned on the day that Omicron hospital 
admissions first exceeded 2 per day per 100,000.
The solid lines end on January 23, and the dashed lines show
model projections.

![hosp](img/USA_4_2_0130_compare_omicron_hosp_aligned.png)

The same figure shown in log scale:

![hosplog](img/USA_4_2_0130_compare_omicron_hosp_aligned_log.png)

## USA Forecast

The following plots show the combined US 4 week forecast. The shaded areas are 50%, 80%, and 95% intervals.
Overall, case rates and hospitalizations are expected to begin declining while deaths are forecast to grow.

### [USA](img/usa-forecast.pdf)

![usa](img/usa-forecast.png)

## [return to case studies](../index.md)

