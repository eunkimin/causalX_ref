causalX: causal inference with eXamples and simulated eXperiments
==========

This repository documents the theory and examples of causal inference methods. The main approach is econometrics and statistics, but adds machine learning or Bayesian flavor when needed. The format is Jupyter Notebook, `.ipynb`. The (tentative) list of contents is as follows.

### Randomized Experiments
- Experimental ideal and A/B tests
- Improving experiments
	- Outliers
	- Multiple test correction
	- Bootstrap
	- Relevant treatment effect estimators: ATE, ATET, ATEN, ATE(%)
	- Conditional ATE, heterogeneous treatment effect (HTE), uplift
- Threats to experimental ideal

### Solution: Quasi-experimental approach
- IV 2SLS estimation (LATE)
	<!-- - LATE == ATET -->
- Regression Discontinuity

### Solution: Observational approach
- Panel Regression (First-diff and fixed-effects)
- Unconfoundedness
	- regression
	- matching, propensity score matching, inverse probability weights
		- Propensity model tuning and covariate balance
	- Doubly Robust (DR), Double Machine Learning (DML)
		- What if both models are wrong in DR
- Matched DID, panel DR
- Time series: Synthetic control

This repo will use examples from common data source or simulated data. 
