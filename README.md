# Chimera Model For Covid19

In this repository, we present the necessary codes and results to perform a validation (Sensitivity, uncertainty, and identifiability analyses) and parameter estimation of the CHIMERA discrete-type model using the [GSUA_CSB toolbox](https://github.com/drojasd/GSUA-CSB) in Matlab2020a. Also, we used as a study case the COVID-19 real data from two localities: Hubei-China (from January 21 to April 8, 2020) and Colombia (from March 6 to November 11).
We identified some relevant differences in parameters for social behavior in both localities that suggest Hubei presented a proficient control over the population to avoid disease spread. Conversely, the outbreak in Colombia exhibits a slow decay because of the relaxation in some control strategies.
In the notebook [1](https://alexacl95.github.io/ChimeraModelForCovid19/HTML/GeneralSA.html), we present the sensitivity analysis for the general model, i.e., using the estimation intervals defined for the model.
In notebooks [2](https://alexacl95.github.io/ChimeraModelForCovid19/HTML/ChinaValidation.html) and [3](https://alexacl95.github.io/ChimeraModelForCovid19/HTML/ColombiaValidation.html), we present the parameter estimations (model fitting) for Hubei and Colombia, respectively. Following the structure proposed in those codes, the codes could be implemented for other data and localities. 
In notebook [4](https://alexacl95.github.io/ChimeraModelForCovid19/HTML/Discussion.html) we summarize the results and perform a discussion.

## Conclusion

The basic-structure we proposed allowed us to built a discrete mathematical model that describes the COVID-19 transmission for two affected very different localities: Hubei and Colombia. We could identify that the strict policies in Hubei helped to finish the first outbreak; conversely,  Colombia has not finished it because of the relaxation in its policies. Finally, it will be important that future research investigate a way to estimate parameters during simultaneous outbreaks for different localities.

[![DOI](https://zenodo.org/badge/320119494.svg)](https://zenodo.org/badge/latestdoi/320119494)

Cite this work as: Catano-Lopez, Alexandra and Rojas-Díaz, Daniel (2021). Chimera Model For Covid19 (https://www.github.com/alexacl95), GitHub. Retrieved January 07, 2021. doi: 10.5281/zenodo.4425704
