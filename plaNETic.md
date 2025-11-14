---
layout: page
title: The plaNETic framework
---

plaNETic is a neural network-based Bayesian internal structure modelling framework for small exoplanets with masses between 0.5 and 15 Mearth. 
The code efficiently computes posteriors of a planet's internal structure based on its observed planetary and stellar parameters. 
It uses a full grid accept-reject sampling algorithm with neural networks trained on the interior model of the [BICEPS code](https://ui.adsabs.harvard.edu/abs/2024A%26A...681A..96H/abstract) as a forward model. 
Furthermore, it allows for different choices in priors concerning the expected abundance of water (formation inside vs. outside of iceline) and the planetary Si/Mg/Fe ratios (stellar vs. iron-enriched vs. free).  

For a more detailed description of the features of the code, we refer to [Egger et al. 2024](https://ui.adsabs.harvard.edu/abs/2024arXiv240618653E/abstract), where the code was first introduced and applied to a planetary system.
