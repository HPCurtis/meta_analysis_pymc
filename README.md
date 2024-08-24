# Basic meta analysis in PyMC
The following code is a Bayesian hierarchical model meta-analysis implemented in Python using the PyMC probabilistic programming framework. The purpose of this example is to convert an example from a great applied meta-analysis resource and example produced within the brms framework by [Harrer et al. 2021](https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/bayesian-ma.html) to provide a rigorous meta-analysis example of meta-analysis implemented in PyMC, of which there are few examples. Ultimately, the aim is to expand again to more complicated examples for PyMC users.


# File structure

- README.md
  - The file you are reading. 
- [meta_analysis.ipynb](meta_analysis.ipynb)
  - ipython notebook for the meta analysis example.
- Stan
  - [brms_model.stan](stan/brms_model.stan): Stan file generated from the equivalent model produced using brms 2.21.0.
- data
  - ThirdWave.rda: .rda file for the analysis.

# References
Harrer, M., Cuijpers, P., Furukawa, T.A., & Ebert, D.D. (2021). Doing Meta-Analysis with R: A Hands-On Guide. Boca Raton, FL and London: Chapmann & Hall/CRC Press. ISBN 978-0-367-61007-4.