---
layout: default
title: Zmumu
image_sliders:
  - ZmumuParameters
  - ZmumuCones
  - ZmumuParamCones
  - ZmumuMass
use_math: true
---

## $Z\rightarrow\mu^+\mu^-$
---
## Contents

1. [Theory](#1-theory)
2. [Parameter Analysis](#2-parameter-analysis)
3. [Cone Cuts](#3-cone-cuts)
4. [Mass Distribution](#4-mass-distribution)
5. [Cross Section](#5-cross-section)
	* [Uncertainties](#uncertainties)
6. [Mass Resonance Fit](#6-mass-resonance-fit)

---

## 1. Theory
Theory of this process goes in here.

## 2. Parameter Analysis

As a first criteria for the $Z\rightarrow\mu^+\mu^-$ process, we are selecting events in which there are at least two leptons, **_one positive and one negative muon_**. On physical grounds, explained in [Section 1](#1.-theory), only the highest [$p_T$](index.md#variable-names) was selected.
The parameters involved in the [invariant mass calculation](index.md#invariant-mass) of the muon pair have been plotted separately. They can be seen in the plot below.

{% include slider.html selector="ZmumuParameters" %}

From these, one can see that cuts on $\eta$ and $\phi$ would not be very lucrative. However, high $p_T$ signal muons dominate over all the other (simulated) sources in the [Muon data](index.md#data-sets-and-simulations).


## 3. Muon Cones

After applying the cuts detailed in the previous section, the [$P_T^\mathrm{cone}$](index.md#variable-names) and the [$E_T^\mathrm{cone}$](index.md#variable-names) of the filtered muons were plotted. These plots are available below.

{% include slider.html selector="ZmumuCones" %}

Based on these plots, we added one more selection cut based on the $P_T^\mathrm{cone}$ and $E_T^\mathrm{cone}$ parameters. Thus, we only recorded muons that have both $P_T^\mathrm{cone}$ and $E_T^\mathrm{cone}$ lower than 6 GeV.
As an aside, before settling on the 6 GeV cut, the effect of various cone cuts on the other parameter plots from [Section 2](#2-parameter-analysis) was studied. These show superimposed plots of the parameters at different cone cuts in GeV (both $P_T^\mathrm{cone}$ and $E_T^\mathrm{cone}$ were cut at the same value).

{% include slider.html selector="ZmumuParamCones" %}

## 4. Mass Distribution

The muons that pass all the selection cuts detailed in [Section 2](#2-parameter-analysis) and [Section 3](#3-muon-cones) were used to calculate the [invariant mass](#invariant-mass). However, the cuts on the cones was varied from 4 Gev to 8 GeV in steps of 1 GeV (symmetric interval around original cut of 6 GeV). Mass resonance curves were obtained for each of these cuts.

{% include slider.html selector="ZmumuMass" %}

It is obvious that these cuts do not display a significant difference between one another. However, they were used in estimating the systematic error on the cross section.

## 5. Cross Section


### Uncertainties
#### Statistical Uncertainty

#### Systematic Uncertainty

#### Luminosity Uncertainty

## 6. Mass Resonance Fit
