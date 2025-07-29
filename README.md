# Bayesian Statistics – Final Project

This project was conducted as part of the **Bayesian Statistics** course at **ENSAE Paris**, during the 3rd year.

---

## Project Overview

The goal of this project was to apply **Bayesian inference techniques** to a regression setting, with a focus on **Gibbs sampling** for variable selection and posterior estimation.

More precisely, we implemented a **Bayesian variable selection model** and used **Gibbs sampling** to estimate the posterior distribution over the regression coefficients. The initialization step was handled via **Lasso regression**, which guided the prior inclusion probabilities.

---

## Repository Structure

- `gibbs_sampling.py`  
  Main Python script that implements the **Gibbs sampling algorithm** for Bayesian variable selection. It includes:
  - Prior setup
  - Posterior sampling steps
  - Trace plotting and diagnostics

- `Gibbs brut.ipynb`  
  Jupyter notebook that performs:
  - Data preprocessing and exploration
  - Lasso regression for coefficient sparsity estimation
  - Initialization of the Gibbs sampler
  - Final Bayesian regression and **prediction of the growth rate**

---

## Methods and Tools

- **Bayesian linear regression**
- **Gibbs sampling** for posterior inference
- **Lasso (L1) regularization** for initialization
- Posterior diagnostics and coefficient interpretation

---

## Dependencies

This project uses standard scientific Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `seaborn`

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## Results

- Sparse regression results with posterior distributions over included features.
- Comparison between frequentist Lasso estimates and Bayesian estimates.
- Bayesian inference enables uncertainty quantification for both model parameters and predictions.

---

## Authors

- **Florent Lin**
- **Arthur Sabre**
- **Baptiste Ferrere**

Final-year students at ENSAE Paris  

---

## Feedback

Feel free to open an issue or pull request for suggestions or improvements!
