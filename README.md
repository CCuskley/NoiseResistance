# Noise Resistance in communication: Quantifying Uniformity and Optimality
Code for 'Noise Resistance in communication: Quantifying Uniformity and Optimality". This repository contains three R Scripts used for the publication, each is explained below. Preprint available at https://psyarxiv.com/wpvq4/

If you use this code, please cite the work:

Cuskley, C., Bailes, R., & Wallenberg, J. (2020). Noise resistance in communication: Quantifying uniformity and optimality. https://doi.org/10.31234/osf.io/wpvq4

## Calculating DORM and UIDO

The script `dormUido.R` calculates the DORM (deviaton of rolling means) of an array of information content values alongside using UIDO (uniform information density optimization) to estimate the optimally uniform ordering of information content in the array.

## DORM/UIDO Validation

The script `dormLengthSim.R` tests DORM and UIDO on arrays of varying lengths drawn from both Zipfian and Uniform distributions, using the zipfR package: https://cran.r-project.org/web/packages/zipfR/index.html. 

## Simulating noise in PYCCLE

The script `uidSentSim.R` simulates clustered and single unit noise for asymmetric, random, actual, and UIDO-optimised versions of ten-word sentences from the Penn York Computer-annotated Coprus of Large amount of English (PYCCLE) https://github.com/uoy-linguistics/pyccle.
