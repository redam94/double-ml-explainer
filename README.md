# Double Machine Learning, explained

An interactive, scroll-driven explainer of causal identification, double/debiased machine learning, and doubly robust ad-lift estimation. Every chart is computed live in the browser from simulated data with known truth.

**Live page:** https://redam94.github.io/double-ml-explainer/

## What it covers

- **Part I · Identification.** Markov equivalence, the missing potential outcome, same data with different truths, partial-identification bounds, and what happens when bad controls (mediators, colliders, instruments) go into the model.
- **Part II · Estimating a continuous effect.** Confounding, regularization bias, partialling out, Neyman orthogonality, overfitting and cross-fitting, on weekly media spend.
- **Part III · Estimating ad lift.** Dashboard lift, propensity score matching, weighting, outcome models, doubly robust (AIPW) ATT, overlap, flexible cross-fitted learners and the DR-learner.
- **Sensitivity.** Tipping points for unmeasured confounding, benchmarked against observed covariates.
- **Part IV · Evidence beyond the sample.** Why a randomized holdout needs no identifying assumption, and how lines of evidence that fail for different reasons (model-based estimate, placebo test, placebo-corrected estimate, experiment) build a case together.

The page is a single self-contained `index.html` with no build step. Monte Carlo simulations run in a Web Worker.
