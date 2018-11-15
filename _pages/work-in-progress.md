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

### Nov.11 -- Nov.18.2018
* (Mon) Nov.12 
  - [x] think about the look-ahead dispatch (1.5h)
  - [ ] understand Dongchan's method on power flow feasibility region (1h)  
  - [X] docs different representations of power flow equations (1h)
  - [X] get tickets (BSO) (0.5h)
  - [x] plot prior and posterior epsilon (1h)
  - [x] collect and plot results of the 3-bus system (1h)
  - [x] review TPS paper (1h) 
* (Tue)
  - [ ] proof of strong SOCP formulation (1h)
  - [ ] get ready the 118-bus system (1h)
  - [ ] test run the 118-bus system (1h)
  - [ ] sort up the thinking on Look-ahead dispatch (1h)
  - [ ] Seminar: learning regularizers (1.5h)
  - [ ] meeting with Dr. Xie about look-ahead (1h)
  - [ ] Seminar: (1.5h) 
  - [ ] plot the relationship among N,k,beta
  - [ ] sort writings of theoretical analysis (2h)
  - [ ] result analysis of the 3-bus system (2h)
  - [ ] trivia
    - [ ] a list of postdocs and fellowships (2h)
    - [ ] reply Alex 
    - [ ] check travel grant 
    - [ ] flight ticket to Hawaii
    - [ ] text Xiangtian 
    - [ ] email for Ben Hobbs' meeting 
* (Wed)
  - [ ] MIT Energy Initiative Workshop (5h)
  - [ ] think on the GenGame formulation, get ready for Hobb's meeting (2h)
  - [ ] check the 118-bus test case (2h)
  - [ ] check the two papers by Hobbs on MPEC, in the reviewed paper (2h)
  - [x] download the lecture slides
    - [x] baldick's market lecture
    - [x] baldick's market power lecture 
* (Thu)
  - [ ] re-implement Dongchan's method (2h)
  - [ ] seminar (1h)
  - [ ] 118-bus analysis (2h)
  - [ ] Sra's seminar (1.5h) 
* (Fri)
  - [ ] think about price of anarchy (2h) 
  - [ ] think about inner approx with different formulations (2h)
  - [ ] ss
* (Sat) 
  - [ ] write about the 118-bus simulation results (3h)
  - [ ] apply Dongchan's method, using a different form of AC power flow 
* (Sun) 
  - [ ] finalize the cc-SCUC paper, sent to Dr. Xie (2h)
  - [ ] data-driven RO paper (2h)  
  - [ ] read Vishal's code (1h) 
* (Mon)
  - [ ] meet Ben Hobbs (1h)

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
