---
layout: archive
title: "Datasets for Power System Research"
permalink: /testcase/
author_profile: true
tags:
  - data
  - benchmark
  - ieee
  - dataset
redirect_from: 
  - "/testcase.html"
---

## Test Cases for OPF-related Studies

| Name (link) | Download | Ref | OPF | Wind | Solar | DG | Contingency | TS | GMD | PWDS | PMU |Others | Notes |
|-------------|----------|-----|-----|----|-----|------|-----|------|-------|----|--------|-------|-------|
| [ACTIVSg200](https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg200/) | [URL1](https://db.bettergrids.org/bettergrids/handle/1001/437) | [[^birchfield2017]]  | Yes |    |     |      |     | Yes |       |    |        |       |  |
| [ACTIVSg500](https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg500/) |          |     |     |    |     |      |     |      |       |    |        |       |  |
| [ACTIVSg2000](https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg2000/) |          |     |     |    |     |      |     |      |       |    |        |       |  |
| [ACTIVSg10k](https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg10k/) |          |     |     |    |     |      |     |      |       |    |        |       |  |
| [ACTIVSg25k](https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg25k/) |          |     |     |    |     |      |     |      |       |    |        |       |  |
| [ACTIVSg70k](https://electricgrids.engr.tamu.edu/electric-grid-test-cases/activsg70k/) |          |     |     |    |     |      |     |      |  |    |  |       |  |
| [NREL118](ss) |          | [[^pena2019]]  |     |    |     |      |     |      |       |    |        |       |  |
|             |          |     |     |    |     |      |     |      |       |    |        |       |  |
|             |          |     |     |    |     |      |     |      |       |    |        |       |  |


Sources of Data
- [BetterGrids.org](https://db.bettergrids.org/)
- [Columbia Synthetic Power Grids](https://wimnet.ee.columbia.edu/portfolio/synthetic-power-grids-data-sets/)
- [ComplexNetWiki](https://github.com/ComplexNetTSP/ComplexNetWiki/wiki/PowerGrid-datasets)

## IEEE Standard Test Cases
Transmission Steady-State

Distribution Steady-State


## Other Cases
- Phase Identification, UCR: [dataset url](https://item.bettergrids.org/handle/1001/536)

Features I care
- look-ahead?
- renewable data?
- DG?
- Contingency

Distribution systems

- case4_dist
- case18:
  - Power flow data for 18 bus distribution system
    %    Please see CASEFORMAT for details on the case file format.
    %
    %    Data from ...
    %       W. M. Grady, M. J. Samotyj and A. H. Noyola, "The application of
    %       network objective functions for actively minimizing the impact of
    %       voltage harmonics in power systems," IEEE Transactions on Power
    %       Delivery, vol. 7, no. 3, pp. 1379-1386, Jul 1992.
    %       https://doi.org/10.1109/61.141855
- case22:
  - Power flow data for 22 bus distribution system
    %    Please see CASEFORMAT for details on the case file format.
    %
    %    Data from ...
    %       M. Ramalinga Raju, K.V.S. Ramachandra Murthy, K. Ravindra,
    %       Direct search algorithm for capacitive compensation in radial
    %       distribution systems, International Journal of Electrical Power &
    %       Energy Systems, Volume 42, Issue 1, November 2012, Pages 24-30
    %       https://doi.org/10.1016/j.ijepes.2012.03.006
- case33bw
  - %CASE33BW  Power flow data for 33 bus distribution system from Baran & Wu
    %    Please see CASEFORMAT for details on the case file format.
    %
    %    Data from ...
    %       M. E. Baran and F. F. Wu, "Network reconfiguration in distribution
    %       systems for loss reduction and load balancing," in IEEE Transactions
    %       on Power Delivery, vol. 4, no. 2, pp. 1401-1407, Apr 1989.
    %       doi: 10.1109/61.25627
    %       URL: http://doi.org/10.1109/61.25627
- case69
  - %CASE69  Power flow data for 69 bus distribution system
    %    Please see CASEFORMAT for details on the case file format.
    %
    %    Data from ...
    %       D. Das, Optimal placement of capacitors in radial distribution
    %       system using a Fuzzy-GA method, International Journal of Electrical
    %       Power & Energy Systems, Volume 30, Issues 6–7, July–September 2008,
    %       Pages 361-367
    %       https://doi.org/10.1016/j.ijepes.2007.08.004
- case85:
  - %CASE85  Power flow data for 85 bus distribution system
    %    Please see CASEFORMAT for details on the case file format.
    %
    %    Data from ...
    %       D. Das, D.P. Kothari, A. Kalam, Simple and efficient method for
    %       load flow solution of radial distribution networks, International
    %       Journal of Electrical Power & Energy Systems, Volume 17, Issue 5,
    %       1995, Pages 335-346.
    %       https://doi.org/10.1016/0142-0615(95)00050-0
- case141:
  - %CASE141  Power flow data for 141 bus distribution system
    %    Please see CASEFORMAT for details on the case file format.
    %
    %    Data from ...
    %       H.M. Khodr, F.G. Olsina, P.M. De Oliveira-De Jesus, J.M. Yusta,
    %       Maximum savings approach for location and sizing of capacitors in
    %       distribution systems, Electric Power Systems Research, Volume 78,
    %       Issue 7, July 2008, Pages 1192-1203
    %       https://doi.org/10.1016/j.epsr.2007.10.002



- NREL118  [^pena2019] 
	- NREL 118 bus system
- Wisconsin 1664-bus System
	- [dataset url](https://db.bettergrids.org/bettergrids/handle/1001/424)
	- 1 snapshot, no contingency, no renewable profiles 

[^pena2019]: Peña, Ivonne, Carlo Brancucci Martinez-Anido, and Bri-Mathias Hodge. 2018. "An Extended IEEE 118-Bus Test System with High Renewable Penetration." IEEE Trans. Power Syst.

[^birchfield2017]: A. B. Birchfield; T. Xu; K. M. Gegner; K. S. Shetye; T. J. Overbye, "Grid Structural Characteristics as Validation Criteria for Synthetic Networks," in IEEE Transactions on Power Systems, vol. 32, no. 4, pp. 3258-3265, July 2017.