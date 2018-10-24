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
      $B$: number of background events,
      $\epsilon$: efficiency of selecting signal events
      and 
      $\int Ldt$: integrated luminosity measures the number of $pp$ collisions resulting in the collected data


### Data Sets and Simulations

A table of used Monte Carlo simulations is available below for reference.

|      Monte Carlo Physics Process     |                           Description                           |
|:------------------------------------:|:---------------------------------------------------------------:|
|           $Z\rightarrow ee$          |      $Z^0$ decaying to a positive and a negative electrons      |
|         $Z\rightarrow \mu\mu$        |         $Z^0$ decaying to a positive and a negative muon        |
|        $Z\rightarrow \tau\tau$       | $Z^0$ decaying into a positive and negative tau (rarer process) |
|            Drell-Yan $ee$            |       Drell-Yan electron simulation with $8<m_{ll}<15$ GeV      |
|            Drell-Yan $ee$            |      Drell-Yan electron simulation with $15<m_{ll}<40$ GeV      |
|          Drell-Yan $\mu\mu$          |         Drell-Yan muon simulation with $8<m_{ll}<15$ GeV        |
|          Drell-Yan $\mu\mu$          |        Drell-Yan muon simulation with $15<m_{ll}<40$ GeV        |
|          $W\rightarrow e\nu$         |                        $b$ veto, no jets                        |
|          $W\rightarrow e\nu$         |                       $b$ veto, with jets                       |
|          $W\rightarrow e\nu$         |                       with $b$, with jets                       |
|         $W\rightarrow \mu\nu$        |                        $b$ veto, no jets                        |
|         $W\rightarrow \mu\nu$        |                       $b$ veto, with jets                       |
|         $W\rightarrow \mu\nu$        |                       with $b$, with jets                       |
|        $W\rightarrow \tau\nu$        |                        $b$ veto, no jets                        |
|        $W\rightarrow \tau\nu$        |                       $b$ veto, with jets                       |
|        $W\rightarrow \tau\nu$        |                       with $b$, with jets                       |
|        $tt\rightarrow leptons$       |                Top quark pair decaying to leptons               |
| $H\rightarrow ZZ\rightarrow leptons$ |                $Z$ boson pair decaying to leptons               |

Further, a table of the used **real data** sets are presented below.


| ATLAS Data Set |                               Description                               |
|:--------------:|:-----------------------------------------------------------------------:|
|  Electron data | ATLAS data at 8 TeV filtered to contain at least one electron per event |
|    Muon data   |   ATLAS data at 8 TeV filtered to contain at least one muon per event   |


### Variable Names

To make it easier to read, a table with all the variables that we refer to in this website is available below. Hyperlinks to this table will be given when one first refers to a variable in the text.

| Variable Name |                                       Physical Quantity                                       | Formula | Measured |
|:-------------:|:---------------------------------------------------------------------------------------------:|:-------:|:--------:|
|       $n$       |                                 Number of leptons in an event                                 |    -    |    Yes   |
|      $type$     |                                        Electron or Muon                                       |    -    |    Yes   |
|      $\eta$      |                                        Pseudo-rapidity                                        |   $\eta\equiv -\mathrm{ln}\[ tan\(\theta/2\)\] $   |    Yes   |
|      $\phi$      |                                        Azimuthal angle                                        |    -    |    Yes   |
|       $p_T$      |                                 Transverse momentum of lepton                                 |    -    |    Yes   |
|       $E_T$      |                                       Transverse energy                                       |    -    |    No    |
|       $E$       |                                        Energy of lepton                                       |    -    |    Yes   |
|     $P_\mathrm{T}^\mathrm{cone}$    |  Scalar sum of track pTs in a  cone of R=0.3 around lepton, not including the lepton itself |    -    |    Yes   |
|     $E_\mathrm{T}^\mathrm{cone}$    | Scalar sum of track ETs in a cone of R=0.2 around lepton, not including the lepton ET itself |    -    |    Yes   |
|     $E_\mathrm{T}^\mathrm{miss}$    |                                   Missing transverse energy                                   |    -    |    Yes   |
|    $\phi_\mathrm{miss}$    |                                  Missing transverse momentum                                  |    -    |    Yes   |
|     $\Delta\phi$    |                               Difference between phi and missphi                              |   $\phi^\mathrm{miss}-\phi$   |    No    |
|       $M$       |                               Rest frame mass of the lepton pair                              |   [Yes](Zmumu.md#theory)   |    No    |
|       $m_T$      |                                 Transverse mass of lepton pair                                |   [Yes](Wmunu#theory)   |    No    |
