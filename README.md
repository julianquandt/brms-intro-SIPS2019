# One to rule them all: A beginner’s guide to fitting Bayesian mixed-effects models in Stan using brms @ SIPS 2019

Johannes Algermissen & Julian Quandt

Abstract: In statistics classes, students often learn a zoo of different models, without grasping how those all link together. In consequence, they often fit several models, one for each research question. Hierarchical/ multi-level/ mixed-effects models constitute a unifying framework that allows to address many questions in a single model, including questions that are not easily answered with standard ANOVAs (e.g. trial-by-trial effects). However, this increased flexibility comes at the costs of more complex computation.
We will discuss the logic and benefits/ pitfalls of using mixed-effects models, and then introduce Markov chain Monte Carlo (MCMC) as a particularly suited fitting algorithm. We will introduce the R package brms, an easy-to-handle wrapper for fitting Bayesian mixed-effects models using MCMCs in the language Stan.

Pre-requisites: Basic familiarity with R, preferably even with the R package lme4 (linear mixed-effects models). We will not go beyond introductory topics.

No need to bring your laptop, as we will not do any real-time analyses (too time-consuming). All the material is already created and will be available on github (the latest during the session).


The first part of the session will focus mostly on why you might want to use a) mixed models and b) a Bayesian approach. This will be very high-level (not very mathy, but focused on the principled approach that distinguishes mixed models from repeated measures-ANOVA and other standard models as implemented e.g. in SPSS). We will mostly talk about the advantages of using those two approaches.
In the second part, we will go over a detailed example of how a relatively simple data set can be analyzed via a Bayesian mixed-effects models in Stan via brms, going over the code, model diagnostics and checks, and interpreting the output. There will be ample opportunity to ask questions. If time allows, we will also show the breadth of brms, going into not-so-standard models.

Link to the slides will follow soon.

Preliminary schedule:
Philosophy of mixed models a.k.a. how to best analyze repeated-measures data?
Bayesian vs. Frequentist philosophy of statistics
Markov chain Monte Carlo (MCMC) algorithms
Brms Practical


# Repository Overview

The repository contains the slides, an example file as Rmarkdown and the rendered html version working through the examples from the lecture with some more explanation on how to do them yourself in `brms`.
