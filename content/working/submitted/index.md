---
title: "Nonparametric Deconvolution Models"
authors: ["A. Chaney", "A. Verma", "**Y. S. Lee**", "B. Engelhardt"]
date: "2020-03-17"
publication_types: ["3"]
abstract: "We describe nonparametric deconvolution models (NDMs), a family of Bayesian nonparametric models for collections of data in which each observation is the average over the features from heterogeneous particles. For example, these types of data are found in elections, where we observe precinct-level vote tallies (observations) of individual citizens' votes (particles) across each of the candidates or ballot measures (features), where each voter is part of a specific voter cohort or demographic (factor). Like the hierarchical Dirichlet process, NDMs rely on two tiers of Dirichlet processes to explain the data with an unknown number of latent factors; each observation is modeled as a weighted average of these latent factors. Unlike existing models, NDMs recover how factor distributions vary locally for each observation. This uniquely allows NDMs both to deconvolve each observation into its constituent factors, and also to describe how the factor distributions specific to each observation vary across observations and deviate from the corresponding global factors. We present variational inference techniques for this family of models and study its performance on simulated data and voting data from California. We show that including local factors improves estimates of global factors and provides a novel scaffold for exploring data."
links:
  - name: "arXiv"
    url: "https://arxiv.org/abs/2003.07718"
#doi: "10.1101/2021.05.20.444911"
featured: false
---
