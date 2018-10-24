---
layout: default
title: Wmunu
image_sliders:
  - WmunuParameters
  - ConeCutsMunu
  - MassConesWmunu
  - BackgroundAnalysisMunu
use_math: true
---
<style>

	table, th, td {
    padding: 12px;
    font-family: Arial, Helvetica, sans-serif;
	}

</style>

<center> <h1> $W^{\pm} \rightarrow \mu^{\pm}\nu$ </h1> </center>


## Contents:
1. [Theory](#1-theory)
2. [Parameter Analysis](#2-parameter-analysis)
3. [Ptcone and Etcone Cuts](#3-ptcone-and-etcone-cuts)
4. [Mass Distribution](#4-mass-distribution)
5. [Background Analysis](#5-background-analysis)<br>
	5.1 [Estimation of Background Shape](#51-estimation-of-background-shape)<br>
	5.2 [ABCD Method](#52-abcd-method)
6. [Cross Section calculation](#6-cross-section-calculation)
7. [Summary of Results](#7-summary-of-results)


## 1. Theory

Points to cover:<br>
	1. Why delphi is max
	2. QCD contribution

---

## 2. Parameter Analysis

The parameters considered initially were $\eta$,  $p_{T}$ of the lepton, $E_{T}^{miss}$, and $\Delta \phi$, as shown in [Slider 3.1](#slider-31). It was observed that $\eta$ showed a negligible dip between 1-1.5. The influence of $\eta$ on the mass distribution and cross-section was [later explored](#6-cross-section-calculation). It was hence concluded that no cuts were required on $\eta$. However, $p_{T}$ showed a significant jump at ~ 25.5 GeV. Hence it was required for the leptons to have $p_{T} > 25.5 GeV$. Additionally, $E_{T}^{miss}$ showed overlap with background simulations below ~ 35.5 GeV. Thus, the events with $E_{T}^{miss}$ less than 35.5 GeV were eliminated. $\Delta \phi$ was an interesting parameter which showed the contribution of background for cases where  $\Delta \phi \rightarrow$ 0. This is also as expected from [section 1](#1-theory). Thus it was added as a selection criteria requiring $\Delta \phi$ to be maximum for a given event. All the selection cuts detailed here have been summarized in [Table 3.1](#table-31). 

<a name="slider-31"></a>

{% include slider.html selector="WmunuParameters" %}

#### __Slider 3.1__: The parameter plots for $\eta$, $p_{T}$ of the lepton, $E_{T}^{miss}$, and $\Delta \phi$ were plotted. The cuts on the parameters were made by comparison with background processes.

---

## 3. Ptcone and Etcone Cuts

The ptcones and etcones were useful tools to distinguish between leptons and $\nu$ produced by electroweak processes and hadron showers and other miscellaneous processes. As shown in [Slider 3.2](#slider-32), it was observed that for values of ptcones and etcones larger than 2 GeV, the background processes began to dominate. Hence, the cuts added on ptcones and etcones required the events to be **less than 2 GeV** respectively. 


<a name="slider-32"></a>

{% include slider.html selector="ConeCutsMunu" %}

#### __Slider 3.2__: The parameter plots for etcones and ptcones were used to further eliminate background events from the 'Muon Data' set.
---

## 4. Mass distribution

The etcones and ptcones cuts influenced the mass distribution calculated for the invarient mass of the lepton pair. It was crucial to make note of the regions in the mass distribution, where the influence due to the cones was maximum. Accordingly, the mass distribution was sliced between (55 -120) GeV. Fining the cuts further resulted in loss of signal data and a balance was decided by exploring the influence of the cone cuts, as shown in [Slider 3.3](#slider-33). The ptcones and etcones were varied from (0.5 - 3) GeV. It was observed that for 0.5-1.5 GeV,  better agreement of the data was observed with the signal (majorly at the tails of the distribution). However, the number of counts was reduced by a factor ~ $2\times 10^4$ relative to the cone cut at 3 GeV. Thus a balance was evalueted at 2 GeV showing consistency with the cone cuts decided from the plots shown in [Slider 3.2](#slider-32).


<a name="slider-33"></a>

{% include slider.html selector="MassConesWmunu" %}

Thus, this concludes to the section on analysis of parameters to select candidate events. All the cuts mentioned in [Section 2](#2-parameter-analysis) to [4](#4-mass-distribution) have been summarized in [Table  3.1](table-31). However, the analysis is yet not complete as we can observe some discrepency between the Monte carlo signal and data. One of the major contributions to background is that from QCD, as detailed in [Section 1](#1-theory). Two methods for background contribution from QCD have been estimated in [Section 5](#5-background-analysis).

<a name="table-31"></a>
<table style="width:60%" align="center">
  <tr>
    <th bgcolor="#e6ffcc">Parameter Name</th>
    <th bgcolor="#e6ffcc">Selection Cuts </th> 
  </tr>
                                               
  <tr>                                          
    <td align="center"> $p_{T}$ </td>
    <td> Greater than 25.5 GeV</td>
  </tr>

  <tr>                                          
    <td align="center"> $E_{T}^{miss}$ </td>
    <td> Greater than 35.5 GeV</td>
  </tr>

  <tr>                                          
    <td align="center"> $|\Delta\phi|$ </td>
    <td>Maximum</td>
  </tr>

  <tr>                                          
    <td align="center"> $M_T$ </td>
    <td> Greater than <b>55</b> GeV <br> Less than <b>120</b> GeV</td>
  </tr>

  <tr>                                          
    <td align="center"> $P_{T}^{cones}$ </td>
    <td> Less than 2 GeV</td>
  </tr>


  <tr>                                          
    <td align="center"> $E_{T}^{cones}$ </td>
    <td> Less than 2 GeV</td>
  </tr>

</table>

#### __Table 3.1__ : The selection criteria for all candidate events influencing the Muon data are summarized. 
---

## 5. Background Analysis

### 5.1 Estimation of Background Shape

{% include slider.html selector="BackgroundAnalysisMunu" %}

### 5.2 ABCD Method

---

## 6. Cross Section


## Uncertainties


#### Statistical Uncertainty


#### Systematic Uncertainty

#### Luminosity Uncertainty

## Final Value
Finally, we quote the final value for the cross section obtained in the $W\rightarrow\mu\nu$ process to be
\begin{equation}
\sigma_{W\mu\nu} = 12.35\pm 0.03 \mathrm{(stat)}\pm 0.47 \mathrm{(syst)}\pm 0.02 \mathrm{(lumi)}
\end{equation}
---

## 7. Summary of Results
---
