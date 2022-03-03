# Repeated Measures Analysis

Repeated measures occur whenever the same observation is taken sequentially on the same object, usually through time. This introduces a dependency within the subject’s observations.

Some advantages of repeated measure models are:

1. Will allow to monitor how treatment effect changes over time
2. Will produce more efficient estimates than non-repeated models allowing statistical inference to be made with fewer subjects
3. Will produce tests with higher power (i.e. if an effect exists, your statistical test is more likely to detect it).

SAS can fit repeated measure designs within linear mixed models (proc mixed). This allows to accommodate for missing data and random effects.

### Model Assumptions of MMRM
-normally distributed data with specific covariance structure type (see later)
-Missing at Random (MAR) ="missingness is independent of missing outcomes given observed outcomes and covariates."
-MAR holds because missingness at Week 28 has been driven by HbA1C > 6.5% in earlier weeks and these HbA1c data are included in our model.
