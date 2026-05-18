# Bayesian MMM Challenge Solution

This repository contains my solution for the HAMS Data Science challenge.

## Files

- `hams_mmm_solution.ipynb`: main notebook
- `MMM_test_data.csv`: dataset
- `requirements.txt`: required Python packages

## Approach

I used a simple Bayesian Marketing Mix Model with PyMC.  
Marketing carry-over was modeled using a geometric adstock transformation with alpha = 0.5.  
The model estimates channel effects, evaluates prediction performance, and derives ROI estimates using a counterfactual approach.

## Limitations

This is a simple first version. It does not include seasonality, trend, saturation, promotions, pricing, or external events.