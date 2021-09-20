# How-much-has-the-data-informed-your-isotope-mixing-model
The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
=====================
The package BayeSens provides functions for non-parametric calculation of the Hellinger distance, parametric calculation of the Hellinger distance; data cloning ; and calculating posterior shrinkage . Refer to the vignette for more help. (type once the package is loaded, type vignette('BayeSens') in R).

To install this package open R and type: 
install.packages("devtools")
library("BayeSens")

The contributions of different food sources to animal diets is often a
mystery. Isotopes provide a means to estimate those contributions,
because different food sources often have different isotopic signatures.
We would typically use a Bayesian mixing model to estimate the
proportional contributions of different food sources to samples taken
from the animal.

Isotope mixing models are fitted within a Bayesian framework. This means
that the end results (AKA ‘posterior distributions’) are influenced by
the data, the model and the prior distributions. Priors are specified
for each parameter in the model, including the source contributions.


If you want to apply this tool for isotope mixing models, then see vignette("isotope-mixing-example")
