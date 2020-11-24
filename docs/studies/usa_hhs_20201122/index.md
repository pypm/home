## November 22, 2020 Analysis of USA state data: New hospitalization data

A new data source for hospitalization data has
been made available by the US HHS [here](https://healthdata.gov/dataset/covid-19-reported-patient-impact-and-hospital-capacity-state-timeseries)

The plots shown in this summary can be compared to similar
[plots](../usa20201115)
that used data from the [Covid Tracking Project](https://covidtracking.com/data/api).

## Summary

For each state, its infection trajectory
can be summarized by the observed exponential growth in cases or
exponential growth in hospitalization.
The plot below compares the current inferred growth rate (in % per day)
for each state measured in these two ways.
For many states the hospitalization growth (from HHS data) is
remarkably close to the case growth.

![delta_compare](img/delta_compare.png)

The HHS data has both daily hospitalizations and current hospital
occupancy data for every state.
Having both, allows one to infer the mean stay for patients.

The Covid Tracking Project provided one or both of these data for
many states.

The inferred mean hospital stay time is found to be much more
consistent with the HHS data, compared to the Covid Tracking Project data,
as shown in the figures below. The only outlier in the HHS data is
for the state of Rhode Island.

#### Mean hospital stay (days) inferred from the covid tracking project data

![hosp_covid_tracking](hosp_covid_tracking.png)

#### Mean hospital stay (days) inferred from the US HHS data

![hosp_hhs](hosp_hhs.png)

## Individual state fits

The plots below show the case / hospitalization / deaths data for all 50 states, DC, and PR.
The infection trajectory is determined by fits to the cumulative case data.
The data fits were done using data up until November 21. 

The left figures show the daily cases, hospitalization, and deaths
on a log scale, since July 1.
The green points are the case data, the stars show the
weekly average, and the green curve is the fit of the model to the case data.
Hospitalization and deaths are in grey and purple.

For states where the hospitalization indicates a different trajectory,
the growth is inferred from the hospitalization data.

The right figures highlight the in-hospitalization numbers (hospital occupancy) in teal.
The curve shows the model prediction with the growth inferred from cases (or hospitalization).
A single parameter, the mean stay in hospital, is adjusted to fit the data.
That parameter value is shown in the histogram above.

### [Alaska](img/ak_2_3_1122.pdf)

![ak](img/ak_2_3_1122.png)

### [Alabama](img/al_2_3_1122.pdf)

![al](img/al_2_3_1122.png)

### [Arkansas](img/ar_2_3_1122_h.pdf)

![ar](img/ar_2_3_1122_h.png)

### [Arizona](img/az_2_3_1122.pdf)

![az](img/az_2_3_1122.png)

### [California](img/ca_2_3_1122_h.pdf)

![ca](img/ca_2_3_1122_h.png)

### [Colorado](img/co_2_3_1122.pdf)

![co](img/co_2_3_1122.png)

### [Connecticut](img/ct_2_3_1122.pdf)

![ct](img/ct_2_3_1122.png)

### [District Of Columbia](img/dc_2_3_1122.pdf)

![dc](img/dc_2_3_1122.png)

### [Delaware](img/de_2_5_1122.pdf)

![de](img/de_2_5_1122.png)

### [Florida](img/fl_2_3_1122_h.pdf)

![fl](img/fl_2_3_1122_h.png)

### [Georgia](img/ga_2_3_1122_h.pdf)

![ga](img/ga_2_3_1122_h.png)

### [Hawaii](img/hi_2_3_1122.pdf)

![hi](img/hi_2_3_1122.png)

### [Iowa](img/ia_2_5_1122.pdf)

![ia](img/ia_2_5_1122.png)

### [Idaho](img/id_2_3_1122.pdf)

![id](img/id_2_3_1122.png)

### [Illinois](img/il_2_5_1122.pdf)

![il](img/il_2_5_1122.png)

### [Indiana](img/in_2_3_1122_h.pdf)

![in](img/in_2_3_1122_h.png)

### [Kansas](img/ks_2_3_1122.pdf)

![ks](img/ks_2_3_1122.png)

### [Kentucky](img/ky_2_3_1122.pdf)

![ky](img/ky_2_3_1122.png)

### [Louisiana](img/la_2_5_1122_h.pdf)

![la](img/la_2_5_1122_h.png)

### [Massachusetts](img/ma_2_3_1122_h.pdf)

![ma](img/ma_2_3_1122_h.png)

### [Maryland](img/md_2_3_1122_h.pdf)

![md](img/md_2_3_1122_h.png)

### [Maine](img/me_2_3_1122.pdf)

![me](img/me_2_3_1122.png)

### [Michigan](img/mi_2_3_1122.pdf)

![mi](img/mi_2_3_1122.png)

### [Minnesota](img/mn_2_3_1122.pdf)

![mn](img/mn_2_3_1122.png)

### [Missouri](img/mo_2_3_1122.pdf)

![mo](img/mo_2_3_1122.png)

### [Mississippi](img/ms_2_3_1122.pdf)

![ms](img/ms_2_3_1122.png)

### [Montana](img/mt_2_3_1122.pdf)

![mt](img/mt_2_3_1122.png)

### [North Carolina](img/nc_2_3_1122.pdf)

![nc](img/nc_2_3_1122.png)

### [North Dakota](img/nd_2_3_1122.pdf)

![nd](img/nd_2_3_1122.png)

### [Nebraska](img/ne_2_3_1122.pdf)

![ne](img/ne_2_3_1122.png)

### [New Hampshire](img/nh_2_3_1122.pdf)

![nh](img/nh_2_3_1122.png)

### [New Jersey](img/nj_2_3_1122.pdf)

![nj](img/nj_2_3_1122.png)

### [New Mexico](img/nm_2_3_1122.pdf)

![nm](img/nm_2_3_1122.png)

### [Nevada](img/nv_2_3_1122.pdf)

![nv](img/nv_2_3_1122.png)

### [New York](img/ny_2_3_1122.pdf)

![ny](img/ny_2_3_1122.png)

### [Ohio](img/oh_2_3_1122.pdf)

![oh](img/oh_2_3_1122.png)

### [Oklahoma](img/ok_2_3_1122_h.pdf)

![ok](img/ok_2_3_1122_h.png)

### [Oregon](img/or_2_3_1122.pdf)

![or](img/or_2_3_1122.png)

### [Pennsylvania](img/pa_2_3_1122.pdf)

![pa](img/pa_2_3_1122.png)

### [Puerto Rico](img/pr_2_3_1122.pdf)

![pr](img/pr_2_3_1122.png)

### [Rhode Island](img/ri_2_3_1122.pdf)

![ri](img/ri_2_3_1122.png)

### [South Carolina](img/sc_2_3_1122_h.pdf)

![sc](img/sc_2_3_1122_h.png)

### [South Dakota](img/sd_2_3_1122.pdf)

![sd](img/sd_2_3_1122.png)

### [Tennessee](img/tn_2_3_1122_h.pdf)

![tn](img/tn_2_3_1122_h.png)

### [Texas](img/tx_2_3_1122.pdf)

![tx](img/tx_2_3_1122.png)

### [Utah](img/ut_2_3_1122.pdf)

![ut](img/ut_2_3_1122.png)

### [Virginia](img/va_2_3_1122.pdf)

![va](img/va_2_3_1122.png)

### [Vermont](img/vt_2_3_1122.pdf)

![vt](img/vt_2_3_1122.png)

### [Washington](img/wa_2_3_1122.pdf)

![wa](img/wa_2_3_1122.png)

### [Wisconsin](img/wi_2_3_1122.pdf)

![wi](img/wi_2_3_1122.png)

### [West Virginia](img/wv_2_3_1122.pdf)

![wv](img/wv_2_3_1122.png)

### [Wyoming](img/wy_2_3_1122.pdf)

![wy](img/wy_2_3_1122.png)



## [return to case studies](../index.md)

