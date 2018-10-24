---
layout: default
title: Wmunu
image_sliders:
  - WmunuParameters
  - ConeCutsMunu
  - MassConesWmunu
  - BackgroundAnalysisMunu
  - ABCDmunu
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
	1. Why delphi is max<br>
	2. QCD contribution<br>
	3. Overshoot-undershoot discuss in summary

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

The etcones and ptcones cuts influenced the mass distribution calculated for the invarient mass of the lepton pair. It was crucial to make note of the regions in the mass distribution, where the influence due to the cones was maximum. Accordingly, the mass distribution was sliced between (55 -120) GeV. Fining the cuts further resulted in loss of signal data and a balance was decided by exploring the influence of the cone cuts, as shown in [Slider 3.3](#slider-33). The ptcones and etcones were varied from (0.5 - 3) GeV. It was observed that for 0.5-1.5 GeV,  better agreement of the data was observed with the signal (majorly at the tails of the distribution). However, the number of counts was reduced by a factor ~ $2\times 10^4$ relative to the cone cut at 3 GeV. Thus a balance was evaluated at 2 GeV showing consistency with the cone cuts decided from the plots shown in [Slider 3.2](#slider-32).


<a name="slider-33"></a>

{% include slider.html selector="MassConesWmunu" %}


#### __Slider 3.3__: The invariant transverse mass distribution is plotted for the $W^{\pm} \rightarrow \mu^{\pm}\nu$ for a range of ptcone and etcone cuts. These cuts influence the shape of the signal and the data. Larger values of cones accommodates for more background data from showers and QCD processes. 

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


The data was observed for ptcones and etcones larger than 2 GeV. The distribution obtained corresponds to events which have passed all the other selection cuts except the cone cuts. The shape of this distribution, as shown in [Slider 3.4](#slider-34), gives a rough estimate of the shape of the QCD background contribution for a range of cuts set on the cones. In order to further refine the shape, the signal events present in the background were subtracted. The QCD shape obtained was normalized with the Monte Carlo contributions (both signal and background). The difference between the data and net shape obtained was minimized in order to attain the appropriate normalization constants. The normalization constants were noted, briefed in the titles in [Slider 3.4](#slider-34), and chi-squares were evaluated. It was observed that the data overshoots the signal and this discrepency has been accouted for as a systematic uncertainty which is further discuessed in the [Summary](summary.md#uncertainty).


<a name="slider-34"></a>

{% include slider.html selector="BackgroundAnalysisMunu" %}

#### __Slider 3.4__: The plots shows the results obtained by accounting for the background contribution due to QCD. The simulated processes were renormalized with the QCD processes to obtain better comparison with measured data.


### 5.2 ABCD Method

The data driven ABCD method was also attempted to estimate the nummber of QCD events present in the measured data. This method assumes that the $p_{T}^{cones}$, and $p_{T}$ variables are uncorrelated with $m_{T}$ of the $W^{\pm}$ decay. The density plots generated by this method is shown in [Slider 3.5](#slider-35). For uncorrelated signals, the B quadrant must consist of signal counts while the other 3 quadrants must be dominated with background. [Table 3.2](#table-32) shows the number of counts recorded in each quadrant. 


<a name="table-32"></a>
<table style="width:90%" align="center">
  <tr>    
  	<th bgcolor="#D8DDE4"> Quadrant </th>
    <th bgcolor="#e6ffcc">Muon Data Set</th>
    <th bgcolor="#EFE89E"> Monte Carlo signal </th> 
    <th bgcolor="#8CAEDE"> Monte Carlo Background </th>  
  </tr>
                                               
  <tr>     
  	<td> A </td>                                         
    <td align="center"> $(3.76\pm 0.07)\times 10^6$ </td>
    <td>$ 1.86\times 10^3$</td>
    <td> $5.50\times 10^3$</td>
  </tr>

  <tr> 
    <td>  B </td>
    <td align="center"> $(2.84 \pm 0.04)\times 10^6$ </td>
    <td> $2.54 \times 10^3$</td>
    <td> 223.5 </td>
  </tr>

  <tr> 
    <td> C </td>
    <td align="center"> $(0.28 \pm 0.07)\times 10^6$ </td>
    <td>~0 </td>
    <td> ~0</td>   
  </tr>

  <tr>  
    <td>  D </td>
    <td align="center"> $(0.10 \pm 0.04)\times10^6$ </td>
    <td> ~0</td>
    <td> ~0</td>
  </tr>

</table>

#### __Table 3.2__ : The A, B, C and D values generated in each quadrant for the data, Monte Carlo signal and background are tabulated. 

Improvements could be made to this method by ensuring that the boundaries of the quandrants are not touching. However, the systematic uncertainty quoted in [Table 3.2](#table-32) arise by calculating the variance in the number of counts in each quadrant achieved while changing the isolation fraction boundary. <a name="isolation-fraction"></a>The [isolation fraction](#isolation-fraction) is defined as the ratio of $p_{T}^{cones}$ to $p_{T}$. The choice of this boundary was made to be 0.07, such that negligible signal is found beyond the boundary. This can be confirmed from the values obtained for Monte Carlo signal in [Table 3.2](#table-32). 


<a name="slider-35"></a>

{% include slider.html selector="ABCDmunu" %}

#### __Slider 3.5__: The density plots generated show the concentration of counts in each of the quadrants A, B, C and D. B is the signal dominated quadrant while A, C and D are mostly containing background events. 

The number of QCD events in the data can then be estimated using the following formula,
\begin{equation}
	N_{QCD} = A\times \frac{D}{C} <br> \implies N_{QCD}[W^{\pm} \rightarrow \mu^{\pm}\nu] \approx 1.3 \times 10^6
\end{equation}


---

## 6. Cross Section calculation

---

## 7. Summary of Results


The cross-section of the process $W^{\pm} \rightarrow \mu^{\pm}\nu$ was calculated by accounting for all the simulated background sources with the estimated QCD background from the data. Two methods were employed to attain estimates on the QCD background contribution as detailed in [Section 5](#5-background-analysis).  
The [two cross-sections values obtained](#6-cross-section-calculation) by the two methods are consistent ~~OR not-consistent~~ with each other. The analysis gives a well-versed overview of background estimation and cross-section calculation in particle physics collisions. The experiment was followed by the [[$W^{\pm} \rightarrow e^{\pm}\nu$]](Wenu.md#Contents) analysis.

---
