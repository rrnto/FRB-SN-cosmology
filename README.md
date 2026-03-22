# Cosmological Model-Independent Constraints on the Baryon Fraction in the IGM

This project implements a model-independent approach to constrain the
baryon fraction in the intergalactic medium (IGM) using fast radio
bursts (FRBs) and Type Ia supernovae.

Luminosity distances are reconstructed from Pantheon data via Gaussian
Process regression and combined with FRB dispersion measures. Bayesian
inference is used to estimate parameters while accounting for
observational uncertainties.

## Files

- `model_independent_frbs01.ipynb` — Analysis pipeline (GP
reconstruction + inference)
- `lcparam_full_long.txt` — Pantheon SNe dataset used in the notebook
