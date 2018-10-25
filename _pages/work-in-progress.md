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
1. [Oct.31.2018] DDL for ACC paper
1. [Nov.12.2018] DDL for TPWRS paper
1. [Nov.16.2018] DDL for TPWRS paper
1. [Nov.19.2018] DDL for TPWRS paper
1. [Dec.30.2018] submission to ARiCS
  - [ ] scenario approach
    - [ ] find support constraints
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

### Oct.21 -- Oct.27.2018
* (Mon) 
  - [x] read the section in Computational Learning Theory Chap. VC
  - [x] Reading the proof in Zhang's paper 
  - [x] Stat Learning Course
  - [^] Matrix function seminar
  - [x] LIDS seminar/Machine Learning Course
  - [^] run for 5 km (night)
  - [^] plot the 3-bus system results 
  - [^] exercise (1.5h) 
  - [^] guitar
* (Tue) 
  - [x] think about better bounds
  - [x] read about VC dimension, the textbook
  - [x] collect the key findings
  - [x] come up with the conjecture
  - [x] prepare for the LIDS tea talk
  - [^] exercise 
  - [^] guitar 
* (Wed) 
  - [x] thinking on the proof
  - [x] College of Computation Info Session
  - [x] My LIDS tea talk (0.5h) 
  - [^] Stat learning course (1.5h) 
  - [x] Machine Learning course (1.5h) 
  - [x] document the findings (2h) 
  - [^] run for 5 miles (gym) 
  - [^] exercise 
  - [^] guitar  
* (Thu) 
  - [ ] return at USPS
  - [ ] think about the proof for UC
  - [ ] CLT set for phase balancing
  - [ ] read the data-driven RO paper (1h) 
  - [ ] borrow book glass bead game (0.5h)
  - [ ] discussion with Ian (1h)
  - [ ] Large Scale Test Case
  - [ ] exercise 
  - [ ] guitar 
* (Fri) 
  - [ ] debug/analyze multi-stage sc-UC (1.5h)
  - [ ] check the sc-SCUC paper, with new outline (1h) 
  - [ ] test simulation results of the big system (2h) 
  - [ ] exercise 
  - Bus
    - [ ] review ACC paper
    - [ ] how to explain the difficulty of cc-ACOPF
* (Sat) 
  - [ ] examine the phase balancing data (1h) 
  - [ ] factor model on phase balancing (1h) 
  - [ ] guitar 
* (Sun) 
  - [ ] code running for large test cases 
  - [ ] hiking 
  - [ ] oysters 

### Next
#### Next Week
- [ ] search for Postdoc Fellowships
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
