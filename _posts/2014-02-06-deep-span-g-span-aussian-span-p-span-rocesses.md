---
title: Deep <span>G</span>aussian <span>P</span>rocesses
abstract: |-
  In this talk we will introduce deep Gaussian process (GP) models. Deep GPs are a deep probabilistic model based on Gaussian process mappings. The data is modelled as the output of a multivariate GP. The inputs to that Gaussian process are then governed by another GP. A single layer model is equivalent to a standard GP or the GP latent variable model (GPLVM). We will motivate these models by considering applications in personalized health.\
  \
  We perform inference in the model by approximate variational marginalization. This results in a strict lower bound on the marginal likelihood of the model which we use for model selection (number of layers and nodes per layer). Deep belief networks are typically applied to relatively large data sets using stochastic gradient descent for optimization. Our fully Bayesian treatment allows for the application of deep models even when data is scarce. Model selection by our variational bound shows that a five layer hierarchy is justified even when modelling a digit data set containing only 150 examples. In the seminar we will briefly review dimensionality reduction via Gaussian processes, before showing how this framework can be extended to build deep models.
venue: Oxford University Statistics Department
linkpdf: http://staffwww.dcs.shef.ac.uk/people/N.Lawrence/talks/deep_oxford14.pdf
mp3: http://staffwww.dcs.shef.ac.uk/people/N.Lawrence/talks/deep_oxford14.mp3
year: '2014'
month: 2
day: '6'
layout: talk
key: Lawrence:oxford14
categories:
- Lawrence:oxford14
authors:
- firstname: Neil D.
  lastname: Lawrence
published: 2014-02-06
---