## March 21, 2021 Analysis of German state data

This shows the results of fits to data from the 16 German states.
A much earlier [study](../archive/germany20200625/index.md)
is described in detail as in the paper [Charaterizing the spread of CoViD-19](../index.md),
and the more recent [study](../archive/germany20201206/index.md)
which showed results prior to Christmas period, showing interesting results for different age groups.

The figures below show the daily cases and deaths since October 2020 on linear and log scales.
The green and indico points show the weekly average cases and deaths.
The pypm model is fit to the case data to determine the infection trajectory.
That trajectory is itself defined by long periods of constant transmission rates,
and the vetical lines show where the transmission rate is changed in the model.
Constant transmission rate leads to steady exponential growth or decline for the infection trajectory,
which appear as straight lines on these log-scale plots.

A two week period of lower than normal case reporting rate is assumed for late December.
The reduction is a free parameter in the fits to case data.

A second infection cycle is included to model the B.1.1.7 variant, with an advantage of
9-10% growth per day over the existing strains.
The cases attributed to the variant are shown in olive-green below. 
Data appear to be consistent with 45-85% of cases as being due to the variant.
Estimating the variant fraction from case data alone is prone to large systematic bias.
Genomic information is necessary to measure this well.

### [Baden-Wurttemberg](img/bw_2_8_0321.pdf)

![bw](img/bw_2_8_0321.png)

### [Bavaria](img/by_2_8_0321.pdf)

![by](img/by_2_8_0321.png)

### [Berlin](img/be_2_8_0321.pdf)

![be](img/be_2_8_0321.png)

### [Brandenburg](img/bb_2_8_0321.pdf)

![bb](img/bb_2_8_0321.png)

### [Bremen](img/hb_2_8_0321.pdf)

![hb](img/hb_2_8_0321.png)

### [Hamburg](img/hh_2_8_0321.pdf)

![hh](img/hh_2_8_0321.png)

### [Hesse](img/he_2_8_0321.pdf)

![he](img/he_2_8_0321.png)

### [Lower Saxony](img/ni_2_8_0321.pdf)

![ni](img/ni_2_8_0321.png)

### [Mecklenburg-Vorpommern](img/mv_2_8_0321.pdf)

![mv](img/mv_2_8_0321.png)

### [North Rhine-Westphalia](img/nw_2_8_0321.pdf)

![nw](img/nw_2_8_0321.png)

### [Rhineland-Palatinate](img/rp_2_8_0321.pdf)

![rp](img/rp_2_8_0321.png)

### [Saarland](img/sl_2_8_0321.pdf)

![sl](img/sl_2_8_0321.png)

### [Saxony](img/sn_2_8_0321.pdf)

![sn](img/sn_2_8_0321.png)

### [Saxony-Anhalt](img/st_2_8_0321.pdf)

![st](img/st_2_8_0321.png)

### [Schleswig-Holstein](img/sh_2_8_0321.pdf)

![sh](img/sh_2_8_0321.png)

### [Thuringia](img/th_2_8_0321.pdf)

![th](img/th_2_8_0321.png)

## Summary of growth rates (with and without immunity)

The following plots summarize the infection history.
The upper plot shows the daily growth/decline of infections (% per day) for the original strains.
The dashed curve are the growths that would have been experienced in absense of immunity.
As immunity builds up, primarily through vaccination, it will help reduce infections.

The lower plot shows an estimate of the contagious fraction of the population as a function of time.

### [Baden-Warttemberg](img/bw-growth.pdf)

![bw](img/bw-growth.png)

### [Bavaria](img/by-growth.pdf)

![by](img/by-growth.png)

### [Berlin](img/be-growth.pdf)

![be](img/be-growth.png)

### [Brandenburg](img/bb-growth.pdf)

![bb](img/bb-growth.png)

### [Bremen](img/hb-growth.pdf)

![hb](img/hb-growth.png)

### [Hamburg](img/hh-growth.pdf)

![hh](img/hh-growth.png)

### [Hesse](img/he-growth.pdf)

![he](img/he-growth.png)

### [Lower Saxony](img/ni-growth.pdf)

![ni](img/ni-growth.png)

### [Mecklenburg-Vorpommern](img/mv-growth.pdf)

![mv](img/mv-growth.png)

### [North Rhine-Westphalia](img/nw-growth.pdf)

![nw](img/nw-growth.png)

### [Rhineland-Palatinate](img/rp-growth.pdf)

![rp](img/rp-growth.png)

### [Saarland](img/sl-growth.pdf)

![sl](img/sl-growth.png)

### [Saxony](img/sn-growth.pdf)

![sn](img/sn-growth.png)

### [Saxony-Anhalt](img/st-growth.pdf)

![st](img/st-growth.png)

### [Schleswig-Holstein](img/sh-growth.pdf)

![sh](img/sh-growth.png)

### [Thuringia](img/th-growth.pdf)

![th](img/th-growth.png)

## [return to case studies](../index.md)

