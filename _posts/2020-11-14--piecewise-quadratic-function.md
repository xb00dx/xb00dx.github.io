---
title: 'Modeling Piecewise Quadratic Objective Function'
date: 2020-11-14
permalink: /posts/2020/11/piecewise-quadratic/
tags:
  - math
  - optimization
  - convex
---

The generator offers are piecewise linear marginal cost function. 
Motivated by the electricity market example



## Problem Description

### Piecewise Linear Function

### Piecewise Quadratic Function

### General Convex Piecewise Function


## Solutions

### Solution 1: introducing binary variables

### Solution 2: define black-box type objective functions

### Solution 3: formulate epigraph with additional variables


## A simple example

### Example

$$f(x) = 
\begin{cases}
x^2,& \text{if}\,0 \le x < 1 \\
10 x^2 - 9,& \text{if}\, 1 \le x
\end{cases}
$$


### YALMIP code


## More Thoughts


### Limitations


Thanks Dr. Johan Löfberg for suggestions.