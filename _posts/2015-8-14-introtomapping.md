---
layout: post
published: true
title: "Display of Geographic Data"
mathjax: false
featured: true
comments: true
headline: Students
categories: 
  - statistics
tags: statistics
---

* Meeting on 14 August, 2014 at 4:00, Jepson 120, Gonzaga.
* In attendance: Nate Burch, Gary Chang, Ta-Tao Chuang, Joe Dumoulin, William Murphy, Rollie Parrish, and Vivek Patil.

* What happened: Vivek Patil talked about how static and interactive maps can be created with few lines of code. His presentation is available at [http://patilv.com/INRUG-IntroToMapping/IntroToMapping.html](http://patilv.com/INRUG-IntroToMapping/IntroToMapping.html) and the code for the presentation and the visualizations shown in it can be accessed from his GitHub repository at [https://github.com/patilv/INRUG-IntroToMapping](https://github.com/patilv/INRUG-IntroToMapping)

Our next meeting is on Sep 25, 2015, Friday, at 4:00 pm, Gonzaga. Room: Jepson 120. The presenter is **Joe Dumoulin, Head of Research at NextIT** and he will talk about **Bayesian Graphical Models in R** <br>

**Abstract**

Statistical methods for Machine Learning often boil down to a couple of methods for reducing complexity in order to effectively model a problem.  The goal is typically to generate a model that can support one or more queries and provide likely answers in the presence of varying degrees of uncertainty.  In this discussion we'll look at one method of constructing, evaluating and querying using one of these methods: Bayesian Graphical Models.

Bayesian Graphical Models are based on the idea that a directed acyclic graph can be used to represent a joint probability distribution of many variables.  When a multivariate system can be modeled this way, the graphical structure of the problems lets us perform many types of queries based on evidence.  

The idea of Bayesian Graphical Models is to try to represent an efficient model (for querying and inference) of the joint probability over the variables while still providing an effective statistical model.  The general description of the model as a directed acyclic graph makes it possible to represent many different types of models by adding or removing edges on the graph.

This discussion is based on material from the following sources:

1. Probabilistic Graphical Models, Koller & Friedman, MIT Press, 2009.
2. [Dr Koller's excellent coursera course on Graphical Models](https://www.coursera.org/course/pgm)
3. Graphical Models in R, Søren Højsgaard, David Edwards, & Steffen Lauritzen, Springer, 2012.
4. [Graphical Models and Bayesian Networks, Tutorial at UseR! 2014 - Los Angeles, Søren Højsgaard](http://people.math.aau.dk/~sorenh/misc/2014-useR-GMBN/bayesnet-slides.pdf)
5. [The R package gRain](https://cran.r-project.org/web/packages/gRain/gRain.pdf)
6. [The software package Hugin and the R package RHugin](https://github.com/rforge/rhugin/blob/master/trunk/inst/doc/RHugin.pdf)

