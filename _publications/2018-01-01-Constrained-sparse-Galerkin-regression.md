---
title: "Constrained sparse Galerkin regression"
collection: publications
permalink: /publication/2018-01-01-Constrained-sparse-Galerkin-regression
date: 2018-01-01
venue: 'J. Fluid Mech.'
citation: ' J.-Ch. Loiseau,  S. Brunton, &quot;Constrained sparse Galerkin regression.&quot; J. Fluid Mech., 2018.'
---
Use [Google Scholar](https://scholar.google.com/scholar?q=Constrained+sparse+Galerkin+regression){:target="_blank"} for full citation

**Abstract :**
The sparse identification of nonlinear dynamics (SINDy) is a recently proposed data-driven modelling framework that uses sparse regression techniques to identify nonlinear low-order models. With the goal of low-order models of a fluid flow, we combine this approach with dimensionality reduction techniques (e.g. proper orthogonal decomposition) and extend it to enforce physical constraints in the regression, e.g. energy-preserving quadratic nonlinearities. The resulting models, hereafter referred to as Galerkin regression models, incorporate many beneficial aspects of Galerkin projection, but without the need for a high-fidelity solver to project the Navier–Stokes equations. Instead, the most parsimonious nonlinear model is determined that is consistent with observed measurement data and satisfies necessary constraints. Galerkin regression models also readily generalize to include higher-order nonlinear terms that model the effect of truncated modes. The effectiveness of such an approach is demonstrated on two canonical flow configurations: the two-dimensional flow past a circular cylinder and the shear-driven cavity flow. For both cases, the accuracy of the identified models compare favourably against reduced-order models obtained from a standard Galerkin projection procedure. Finally, the entire code base for our constrained sparse Galerkin regression algorithm is freely available online.
