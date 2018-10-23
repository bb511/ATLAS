---
layout: default
title: Zmumu
image_sliders:
  - ZmumuParameters
  - ZmumuCones
  - ZmumuParamCones
  - ZmumuMass
  - ZmumuXsect
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

The cross section for each of the five invariant mass distributions was calculated using the method detailed [here](index.md#cross-sections). A plot of the five cross section values is available below.

{% include slider.html selector="ZmumuXsect" %}

At the **6 GeV cone cut**, we obtain a value of **$\sigma_{Z\mu\mu} = 1.2941$ nb** (nanobarns).
In the next sections we will discuss the uncertainty on this value, i.e. at a **6 GeV cone cut**.
## Uncertainties

In this section we state the considered sources of uncertainty and their quantitative estimates.

#### Statistical Uncertainty
The statistical uncertainty of $\sigma_{Z\mu\mu}$ was determined by propagating the errors on the calculated efficienty, number of signal counts and number of background counts. An exact description of the error propagation process can be found [here](index.md#uncertainties).

A final estimate of the **statistical uncertainty** on the calculated cross-section is **0.02 nb**.

#### Systematic Uncertainty
The systematic uncertainty was approximated using the plot of the five cuts. Details of why and how this is done are available [here](index.md#uncertainties). 

A final estimate of the **systematic uncertainty** ont the calculated cross-section is **0.0001 nb**.
#### Luminosity Uncertainty
Finally, the uncertainty on the luminosity was taken to be **0.02 nb**.

## Final Value
Finally, we quote the final value for the cross section obtained in the $Z\rightarrow\mu\mu$ process to be
\begin{equation}
\sigma_{Z\mu\mu} = 1.294\pm 0.002 \mathrm{(stat)}\pm 0.0001 \mathrm{(syst)}\pm 0.02 \mathrm{(lumi)}
\end{equation}

## 6. Mass Resonance Fit

The invariant mass distribution of the $Z\rightarrow\mu\mu$ process was fitted. 

### Fitting Process
**The Relativistic Breit Wigner Distribution** has the form:
\begin{equation}
f(E) = \frac{k}{\left(E^2-M^2\right)^2+M^2\Gamma^2}
\end{equation}
where $k$ is a constant of proportionality, equal to 
\begin{equation}
k = \frac{2 \sqrt{2} M \Gamma  \gamma }{\pi \sqrt{M^2+\gamma}} \;\; \mathrm{with} \;\; \gamma=\sqrt{M^2\left(M^2+\Gamma^2\right)}
\end{equation}

where $M$ is the mass of the resonance, $\Gamma$ is the resonance width (or decay width) and $E$ is the center of mass energy that produces the resonance. This distribution was convoluted with a **Gaussian** in the $M$ parameter and fitted to the data. The free parameters of the fit were $E$, $\Gamma$ and lastly $\sigma$, the width of the Gaussian distribution. 

### Results of the fitting

Mathematica was used to fit the convolution to the data. A figure of the fitted data is available below.

![Fitted Data](/assets/figures/Zmumu/fitted/fitted.png)

This fit has a reduced $\chi^2 = 5.89$ with a probability of obtaining this value of $P=1.54\times 10^{-16}$. Table of the fitted parameters:

|           | Estimate | Standard Error | t-Statistic |     P-Value    |
|:---------:|:--------:|:--------------:|:-----------:|:--------------:|
| $\lambda$ |  271635. |     1566.49    |   173.404   | 4.92122*10^-40 |
|  $\sigma$ |  0.85068 |    0.104545    |   8.13697   |  1.72187*10^-8 |
|    $M$    |  90.7495 |    0.015869    |   5718.66   | 5.50204*10^-78 |
|  $\Gamma$ |  5.8301  |    0.107572    |   54.1973   | 1.90166*10^-27 |