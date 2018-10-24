---
layout: default
title: Wenu
image_sliders:
  - WenuParameters
  - ConeCutsEnu
  - MassConesWenu
  - BackgroundAnalysisEnu
  - ABCDenu
use_math: true
---
<style>

	table, th, td {
    padding: 12px;
    font-family: Arial, Helvetica, sans-serif;
	}

</style>

<center> <h1> $W^{\pm} \rightarrow e^{\pm}\nu$ </h1> </center>


## Contents:
1. [Theory](#1-theory)
2. [Parameter Analysis](#2-parameter-analysis)
3. [Ptcone and Etcone Cuts](#3-ptcone-and-etcone-cuts)
4. [Mass Distribution](#4-mass-distribution)
5. [Background Analysis](#5-background-analysis)<br>
	5.1 [Estimation of Background Shape](#51-estimation-of-background-shape)<br>
	5.2 [ABCD Method](#52-abcd-method)
6. [Cross Section Calculation](#6-cross-section-calculation)
7. [Summary of Results](#7-summary-of-results)

---

## 1. Theory



## 2. Parameter Analysis


The parameters $\eta$ , $p_{T}$ of the detected electron, $E_{T}^{miss}$ and $|\Delta\phi|$ 
were analysed to apply cuts on the 'Electron Data' set. 
As shown in [Slider 4.1](#slider-41), $\eta$ showed a significant dip in the range between $ 
\approx 1.2 - 1.7$. A more detailed analysis of this region has been covered in [Section 6](
#6-cross-section-calculation) and it's influence on the calculated cross-section has been 
accounted for as a systematic uncertainty. $p_{T}$ showed a jump at $\approx -- GeV$, hence 
only events with $p_{T}> -- GeV$ were selected. Similarly, the $E_{T}^{miss}$ parameter was 
chosen to be greater than 30.0 GeV to minimize background contribution at lower values. 
Finally, as detailed in [[Theory for $W^{\pm} \rightarrow \mu^{\pm}\nu$]](Wmunu.md#1-theory)
, $|\Delta\phi|$ was chosen to be maximum. The summary of the cuts on all the parrameters is
summarized in [Table 4.1](#table-41). 

<a name="slider-41"></a>

{% include slider.html selector="WenuParameters" %}

#### __Slider 4.1__: The parameter plots for $\eta$, $p_{T}$ of the lepton, $E_{T}^{miss}$, and $\Delta \phi$ were plotted. The cuts on the parameters were made by comparison with background processes.

---

## 3. Ptcone and Etcone Cuts

The ptcones and etcones were plotted after applying the cuts on $p_{T}$, $E_{T}^{miss}$, and 
$|\Delta\phi|$. The results obtained are shown in [Slider 4.2](#slider-42), and show that 
the data diverger drastically from the Monte Carlo signal for values of ptcones larger than 
4 GeV and etcones large than 5 GeV. The effect of the cone cuts (centred around  4 GeV for 
ptcones and 5 GeV for etcones) was tested on the mass distribution in order to decide on the 
optimal cut as detailed in [Section 4](#4-mass-distribution).

<a name="slider-42"></a>

{% include slider.html selector="ConeCutsEnu" %}


#### __Slider 4.2__: The parameter plots for etcones and ptcones were used to further eliminate background events from the 'Muon Data' set.
---

## 4. Mass Distribution

The transverse mass distribution was plotted for a range of ptcones from $(0.5 - 5) GeV$, and etcones from $(1.5 - 6) Gev$. It was observed that for lower cone cuts, the data undershoots the Monte Carlo signal. Thus implying that our cuts are resulting in loss of signal data. Hence, the cone cuts were set to 4 GeV for ptcones and 5 GeV for etcones as it provided an optimal balance between preserving signal data and eliminating unwanted background processes. 

<a name="slider-43"></a>

{% include slider.html selector="MassConesWenu" %}

#### __Slider 4.3__: The invariant transverse mass distribution is plotted for the $W^{\pm} \rightarrow e^{\pm}\nu$ for a range of ptcone and etcone cuts. These cuts influence the shape of the signal and the data. Larger values of cones accommodates for more background data from showers and QCD processes.



<a name="table-41"></a>


<table style="width:60%" align="center">
  <tr>
    <th bgcolor="#e6ffcc">Parameter Name</th>
    <th bgcolor="#e6ffcc">Selection Cuts </th> 
  </tr>
                                               
  <tr>                                          
    <td align="center"> $p_{T}$ </td>
    <td> Greater than 15 GeV</td>
  </tr>

  <tr>                                          
    <td align="center"> $E_{T}^{miss}$ </td>
    <td> Greater than 30 GeV </td>
  </tr>

  <tr>                                          
    <td align="center"> $|\Delta\phi|$ </td>
    <td> Maximum</td>
  </tr>

  <tr>                                          
    <td align="center"> $M_T$ </td>
    <td> Greater than <b>55</b> GeV <br> Less than <b>120</b> GeV</td>
  </tr>

  <tr>                                          
    <td align="center"> $P_{T}^{cones}$ </td>
    <td> Less than 4 GeV</td>
  </tr>


  <tr>                                          
    <td align="center"> $E_{T}^{cones}$ </td>
    <td> Less than 5 GeV</td>
  </tr>

</table>

#### __Table 4.1__ : The selection criteria for all candidate events influencing the Electron data are summarized. 


---

## 5. Background Analysis

### 5.1 Estimation of Background Shape

{% include slider.html selector="BackgroundAnalysisEnu" %}

### 5.2 ABCD Method

A similar procedure as that explained for $W^{\pm} \rightarrow \mu^{\pm}\nu$ decay was followed. The [isolation fraction](Wmunu.md#isolation-fraction) was chosen to be 0.2 in accordance with the selection cuts detailed in [Table 3.1](#table-31). The uncertainty on the counts in the 'Electron Data Set' was estimated by varying the isolation cut and obtaining the statistical deviation in the sample. The density plots generated for this method are shown in [Slider 4.5](#slider-45). It is evidently observed that majority of the signal counts are concentrated in the region B, as expected. Quantitative figures for the same are quoted in [Table 4.2](#table-42)

<a name="slider-45"></a>

{% include slider.html selector="ABCDenu" %}
 
#### __Slider 4.5__: The density plots generated show the concentration of counts in each of the quadrants A, B, C and D. B is the signal dominated quadrant while A, C and D are mostly containing background events.

<a name="table-42"></a>
<table style="width:90%" align="center">
  <tr>    
    <th bgcolor="#D8DDE4"> Quadrant </th>
    <th bgcolor="#e6ffcc">Electron Data Set</th>
    <th bgcolor="#EFE89E"> Monte Carlo signal </th> 
    <th bgcolor="#8CAEDE"> Monte Carlo Background </th>  
  </tr>
                                               
  <tr>     
    <td> A </td>                                         
    <td align="center"> $(4.80\pm 0.34)\times 10^6$ </td>
    <td>$ 1.33\times 10^3$</td>
    <td> $6.09\times 10^3$</td>
  </tr>

  <tr> 
    <td>  B </td>
    <td align="center"> $(2.75 \pm 0.06)\times 10^6$ </td>
    <td> $2.49 \times 10^3$</td>
    <td> 164.25 </td>
  </tr>

  <tr> 
    <td> C </td>
    <td align="center"> $(0.28 \pm 0.34)\times 10^6$ </td>
    <td>14.24 </td>
    <td> ~0</td>   
  </tr>

  <tr>  
    <td>  D </td>
    <td align="center"> $0.05\times10^6$ </td>
    <td> 13.03</td>
    <td> ~0</td>
  </tr>

</table>

#### __Table 4.2__ : The A, B, C and D values generated in each quadrant for the data, Monte Carlo signal and background are tabulated. 

## 6. Cross Section calculation

## 7. Summary of Results


The cross-section of the process $W^{\pm} \rightarrow e^{\pm}\nu$ was calculated by accounting for all the simulated background sources with the estimated QCD background from the data. Two methods were employed to attain estimates on the QCD background contribution as detailed in [Section 5](#5-background-analysis).  
The [two cross-sections values obtained](#6-cross-section-calculation) by the two methods are consistent ~~OR not-consistent~~ with each other. 

---
