# STA365-HW9
this repository provides solutions to Homework 9 in Bayesian model selection and variable selection.

Q1
Demonstrates a two‐pass Gaussian Copula approach by fitting marginals individually and then modeling the correlation of latent normal variables.
It uses PyMC’s LKJ prior to recover the correlation matrix from non‐normal data.

Q2
Shows Bayesian variable selection using spike‐and‐slab in a multivariate regression and compares it to a diffuse Normal prior.
It also illustrates horseshoe shrinkage to handle sparse coefficients effectively.

Q3
Focuses exclusively on the horseshoe prior for a multivariate regression with strong shrinkage.
It highlights how local and global scales adaptively push irrelevant coefficients toward zero.
