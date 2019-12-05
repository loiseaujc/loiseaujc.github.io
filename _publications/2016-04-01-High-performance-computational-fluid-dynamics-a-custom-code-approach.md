---
title: "High-performance computational fluid dynamics: a custom-code approach"
collection: publications
permalink: /publication/2016-04-01-High-performance-computational-fluid-dynamics-a-custom-code-approach
date: 2016-04-01
venue: 'Eur. J. Phys.'
paperurl: 'https://doi.org/10.1088%2F0143-0807%2F37%2F4%2F045001'
citation: ' J. Fannon,  J.-Ch. Loiseau,  P. Valluri,  I. Bethune,  L. \&apos;{O}, &quot;High-performance computational fluid dynamics: a custom-code approach.&quot; Eur. J. Phys., 2016.'
---
[Access paper here](https://doi.org/10.1088%2F0143-0807%2F37%2F4%2F045001){:target="_blank"}

**Abstract :**
We introduce a modified and simplified version of the pre-existing fully parallelized three-dimensional Navier–Stokes flow solver known as TPLS. We demonstrate how the simplified version can be used as a pedagogical tool for the study of computational fluid dynamics (CFDs) and parallel computing. TPLS is at its heart a two-phase flow solver, and uses calls to a range of external libraries to accelerate its performance. However, in the present context we narrow the focus of the study to basic hydrodynamics and parallel computing techniques, and the code is therefore simplified and modified to simulate pressure-driven single-phase flow in a channel, using only relatively simple Fortran 90 code with MPI parallelization, but no calls to any other external libraries. The modified code is analysed in order to both validate its accuracy and investigate its scalability up to 1000 CPU cores. Simulations are performed for several benchmark cases in pressure-driven channel flow, including a turbulent simulation, wherein the turbulence is incorporated via the large-eddy simulation technique. The work may be of use to advanced undergraduate and graduate students as an introductory study in CFDs, while also providing insight for those interested in more general aspects of high-performance computing.
