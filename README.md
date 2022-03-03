# Repeated Measures Analysis

Repeated measures occur whenever the same observation is taken sequentially on the same object, usually through time. This introduces a dependency within the subject’s observations.

Some advantages of repeated measure models are:

1. Will allow to monitor how treatment effect changes over time
2. Will produce more efficient estimates than non-repeated models allowing statistical inference to be made with fewer subjects
3. Will produce tests with higher power (i.e. if an effect exists, your statistical test is more likely to detect it).

SAS can fit repeated measure designs within linear mixed models (proc mixed). This allows to accommodate for missing data and random effects.

### Model Assumptions of MMRM
- normally distributed data with specific covariance structure type(CS, UN, TOEP, AR(1), VC) .
- Missing at Random (MAR) ="missingness is independent of missing outcomes given observed outcomes and covariates."
