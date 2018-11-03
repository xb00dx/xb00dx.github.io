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
  - [ ] sample average approx
  - (Oct.31) Bertsimas's Robust
    - [ ] data-driven robust
    - [ ] others?
  - [ ] Nemirovski's Robust
    - convex approx
      - [ ] markov bound
      - [ ] chebshev bound
      - [ ] other bounds
    - [ ] more advanced methods in his books
1. [Dec.31.2018] cc-ACOPF restriction DDL
  - [ ] think on how to explain the difficulty (Oct.20)
  - [ ] understand the restriction paper (Oct.18)
  - [ ] implement the restriction method (Oct.31)
  - [ ] problem formulation of cc-ACOPF (Oct.31)
  - [ ] ask for comments on the problem formulation (Nov.15)
  - [ ] preliminary results (Nov.15)
  - [ ] more simulations (Dec.15)
  - [ ] paper writing (Dec.31)

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

### Oct.28 -- Nov.03.2018
* (Thu) 
  - [ ] formulation of cc-UC, without congestion
  - [ ] review paper
  - [ ] read intro to stat learning 
  - [ ] finish proof for the no-congestion case
  - [ ] search for Postdoc Fellowships  
  - [ ] exercise 
  - [ ] guitar 
* (Fri) 
  - [x] read intro to stat learning (1h)
  - [x] control@mit 
  - [^] read data-driven RO paper (3h)
  - [^] exercise (1.5h)
* (Sat) Nov.03
  - [ ] read intro to stat learning (1h)
  - [ ] examine (z,u,v) formulation and results (1h)
  - [ ] read intro to stat learning (1h)
  - [ ] running (1h) 
  - [ ] examine the phase balancing data (1h) 
  - [ ] factor model on phase balancing (1h)  
  - [ ] CLT set for phase balancing (1h)
  - [ ] figure out a case that data-driven RO can help 
  - [ ] email YY about the bound (1h) 
  - [ ] BSO 
* (Sun) Nov.04
  - [ ] read intro to stat learning (1h)
  - [ ] finish writing on the cc-UC thm (1h)
  - [ ] finish writing on the cc-UC proof (1h)
  - [ ] finish theoretical analysis on the cc-SCUC paper (1h)
  - [ ] finish simulation on the 3bus simulation (2h)
  - [ ] visualize the 3-bus results (2h) 
  - [ ] read the inner approximation algorithm (1h)
* (Mon) Nov.05 
  - [ ] large system set-up (1.5h)
  - [ ] read intro to stat learning (1h)
  - [ ] simulation analysis on the 3-bus system (1h)
  - [ ] Stat Learning (1.5h)
  - [ ] question for Sasha (0.5h)
  - [ ] exercise (1.5h)
  - [ ] Machine Learning (1.5h) 
* (Tue) Nov.06 
  - [ ] large-scale test case (1.5h)
  - [ ] read intro to stat learning (1h)
  - [ ] data-driven RO paper (2h) 
  - [ ] read Vishal's code (1h) 
  - [ ] implement one data-driven RO (1h)
  - [ ] read Dongchan's paper again (1.5h)
* (Wed) Nov.07 
  - [ ] read intro to stat learning (1h)
  - [ ] data-driven RO paper (2h) 
  - [ ] Stat Learning (1.5h)
  - [ ] exercise (1.5h) 
  - [ ] Machine Learning (1.5h)
  - [ ] possible applications of inner approx (1h)
  - [ ] proof of strong SOCP formulation (1.5h) 
* (Thu) Nov.08 
  - [ ] read intro to stat learning (1h)
  - [ ] analyze large-scale test case (2h)
  - [ ] proof of strong SOCP formulation (1.5h) 
  - [ ] possible applications of inner approx (1h)
  - [ ] read Dongchan's paper again (1.5h)
* (Fri) Nov.09 
  - [ ] get ready with meeting with Dongchan (0.5h)
  - [ ] Meeting with Dongchan (1h)
* (Sat)
  - [ ]  
        

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
