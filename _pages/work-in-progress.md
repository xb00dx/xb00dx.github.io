---
permalink: /work-in-progress/
title: "Work in Progress"
excerpt: ""
author_profile: true
redirect_from: 
  - "/wip/"
  - "/wip.html"
---

### Upcoming Deadlines

1. [Oct.31.2018] cc-SCUC DDL
1. [Nov.12.2018] DDL for TPWRS paper
1. [Nov.16.2018] DDL for TPWRS paper
1. [Nov.19.2018] DDL for TPWRS paper
1. [Dec.30.2018] submission to ARiCS
  - [x] scenario approach
    - [x] find support constraints


Case studies
1. 3 bus, 1 gen, 1 wind, 2 loads, load profiles, wind profiles, no contingency
  - two snapshots
  - 1 generator, 1 dispatchable wind, 2 loads
  - decision variables: u[t], g[t]
  - plots showing
  1. u[1]~g[1] and u[2]~g[2], constraints within a snapshot
  2. g[1]~g[0] and g[2]~g[1]
  - deterministic constraints shown in black
  - colored constraints related with wind uncertainties, plot each constraints using YALMIP's solution
  - color each wind scenarios, corresponding to colored constraints
  - upper bound #support ones --> #scenarios --> actual support ones
2. 118-bus system (NREL)
3. Larger system, with real-world data?
- [ ] formulations of cc-ACOPF (SOCP for radial networks)

### Nov.11 -- Nov.18.2018
* (Mon) Nov.12 
  - [x] think about the look-ahead dispatch (1.5h)
  - [ ] understand Dongchan's method on power flow feasibility region (1h)  
  - [X] docs different representations of power flow equations (1h)
  - [X] get tickets (BSO) (0.5h)
  - [x] plot prior and posterior epsilon (1h)
  - [x] collect and plot results of the 3-bus system (1h)
  - [x] review TPS paper (1h) 

## References to be added
### Chance-constrained Optimization

### cc-SCED

### cc-SCUC
- Sundar, Kaarthik, Harsha Nagarajan, Line Roald, Sidhant Misra, Russell Bent, and Daniel Bienstock. "Chance-Constrained Unit Commitment with N-1 Security and Wind Uncertainty." IEEE Transactions on Control of Network Systems (2019).

### cc planning


## Others
- using nomencl package in LaTeX: https://tex.stackexchange.com/questions/62061/problem-with-the-nomenclature
