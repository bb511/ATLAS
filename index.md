---
layout: default
title: ATLAS
use_math: true
---


## Introduction to the experiment

$W^{\pm}$ and $Z^0$ bosons are produced via proton-proton, $pp$, collisions by the ATLAS experiment at the Large Hardron Collidor (LHC), Cern. The 2012 ATLAS run at 8TeV, produced data which is made available for educational purposes by the [ATLAS Open Data project](https://cheatham1.gitbooks.io/openatlasdatatools/content/). The experiment is fundamental in order to verify the electroweak results predicted by the Standard Model. The production cross section of $W^{\pm}$ and $Z^0$ events are measured in this experiment. $W^{\pm}$ and $Z^0$ bosons are detected due to their decay into leptons ($e^{\pm}, \mu^{\pm}$) and neutrinos ($\nu$). These decays form characteristic experimental signatures which enable the measurement of physical parameters[[1]](https://arxiv.org/pdf/hep-ph/0412146.pdf). The aim is to measure the overall production cross section $\sigma$ of this process which can be expressed as, 
\begin{equation}
	\sigma = \frac{N - B}{\epsilon \int Ldt}
\end{equation}

where $N$ number of selected events,
      $B$: number of background events which are measured using theory and estimated from data,
      $\epsilon$: efficiency of selecting signal events
      and 
      $\int Ldt$: integrated luminosity measures the number of $pp$ collisions resulting in the collected data




### Variable Names

| Variable Name |                                       Physical Quantity                                       | Formula | Measured |
|:-------------:|:---------------------------------------------------------------------------------------------:|:-------:|:--------:|
|       $n$       |                                 Number of leptons in an event                                 |    -    |    Yes   |
|      $type$     |                                        Electron or Muon                                       |    -    |    Yes   |
|      $\eta$      |                                        Pseudo-rapidity                                        |   $\eta\equiv -\mathrm{ln}\[ tan\(\theta/2\)\] $   |    Yes   |
|      $\phi$      |                                        Azimuthal angle                                        |    -    |    Yes   |
|       $p_T$      |                                 Transverse momentum of lepton                                 |    -    |    Yes   |
|       $E_T$      |                                       Transverse energy                                       |    -    |    No    |
|       $E$       |                                        Energy of lepton                                       |    -    |    Yes   |
|     $P_\mathrm{T}^\mathrm{Cone}$    |  Scalar sum of track pTs in a  cone of R=0.3 around lepton, not including the lepton itself |    -    |    Yes   |
|     $E_\mathrm{T}^\mathrm{Cone}$    | Scalar sum of track ETs in a cone of R=0.2 around lepton, not including the lepton ET itself |    -    |    Yes   |
|     $E_\mathrm{T}^\mathrm{miss}$    |                                   Missing transverse energy                                   |    -    |    Yes   |
|    $\phi_\mathrm{miss}$    |                                  Missing transverse momentum                                  |    -    |    Yes   |
|     $\Delta\phi$    |                               Difference between phi and missphi                              |   $\phi^\mathrm{miss}-\phi$   |    No    |
|       $M$       |                               Rest frame mass of the lepton pair                              |   [Yes](Zmumu.md#theory)   |    No    |
|       $m_T$      |                                 Transverse mass of lepton pair                                |   [Yes](Wmunu#theory)   |    No    |
