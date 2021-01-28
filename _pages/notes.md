---
layout: archive
title: "Notes (on Everything Attractive)"
permalink: /notes/
author_profile: true
---

{% include base_path %}

### Some Topics
- [Collection of Excellent Courses](https://github.com/xb00dx/Online-Courses)
- [Optimization](/optimization/)
- [Programming](/programming/)
- [Software](/software/) 
- [Power System](/ps/)

### LaTeX

LaTeX figures:

- use tikz package
- use inkscape + psfrag package
  - plot figure using `inkscape`, export as `.eps` file
  - in latex source code, use `psfrag` package to replace the strings with latex equations or references
  - `\usepackage{pstool}` to enable compiling using pdflatex
  - compiling command: `pdflatex --shell-escape YOURTEX.tex`

### Markdown
- [equations in github pages](https://stackoverflow.com/questions/26275645/how-to-support-latex-in-github-pages)
- personall chose kramdown over redcarpet 
- [latex equations in github markdown](https://stackoverflow.com/questions/11256433/how-to-show-math-equations-in-general-githubs-markdownnot-githubs-blog)


$$a^2 + b^2 = c^2$$

[python style guide](https://www.python.org/dev/peps/pep-0008/)

### Control Theory
- [LMI Methods in Optimal and Robust Control](http://control.asu.edu/MAE598_frame.htm)