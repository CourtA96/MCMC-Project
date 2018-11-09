# MCMC-Project

## Introduction

In their paper entitled "Measurements of Omega and Lambda from high-redshift supernovae", S. Perlmutter et al used data from the Supernova Cosmology Project to calculate the matter density of the universe, Omega_matter (Omat). The data gives the luminosity (m) for different amounts of redshift (z), and m is a function of Omat and another parameter M. The data is given in the figure below. The value they calculated was approximately 0.28(+/-)1. This project uses the data from their paper to calculate Omega_matter using Markov Chain Monte Carlo (MCMC) methods. EMCEE and Gibbs samplers were used and compared to each other.

The project file is entitled "Finding the Value of Omega Matter" and is a jupyter notebook.

## Results

The histograms of results of the EMCEE and Gibbs samplers:

The values of Omega_matter were taken to be the samples of EMCEE and Gibbs with the highest log-likelihood and their variances were taken to be the variances of the Omat after the burnin period. They are approximately 0.30 plus or minus 0.05, but change each time the samplers are run. A plot of the lines of best fit is given below:
