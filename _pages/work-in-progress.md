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

### Next
#### Next Week
- [ ] Large Scale Test Case
- [ ] code running for large test cases
- [ ] check the sc-SCUC paper, with new outline (1h) 
- [ ] test simulation results of the big system (2h) 
- [ ] debug/analyze multi-stage sc-UC (1.5h)
- [ ] implement phase balancing with factor CLT model (1h)
- [ ] compare results of factor CLT with previous box set (0.5h)
- [ ] implement data-driven robust optimization 
- [ ] relaxation is tight for tree networks
- [ ] simulation results of the big system
- [ ] debug the sc-UC code for large-scale system (1h)
- [ ] read the data-driven robust paper

#### High Priority
- [ ] read Ahmad's paper
- [ ] watch the video by Shabir Ahmad
- [ ] read Dan Wu's paper
- [ ] read all slides for Bertsimas' course

#### Low Priority
- [ ] download the references of stat learning course
- [ ] check the proof by Bertismas
- [ ] inner approximation of power flow feasibility region
- [ ] S-procedure 
1. PES GM paper?
  - if can solve the cross-terms in ENR, then write this
  - or, write data-driven robust optimal topology ?? LASSO, regularizer, robust opt view of the results 
  - otw, chance-constrained something?
