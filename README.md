# Repeated Measures Analysis
Repeated measures occur whenever the same observation is taken sequentially on the same object, usually through time. This introduces a dependency within the subject’s observations.

### Why repeated Measures Analysis?
- Within-subject variability is lower than between-subject variability and so there can be greater precision in estimating effects by taking repeated measures on individual subjects.
- Cross-over designs are a special case of repeated measures, also known as within-subjects designs, use the same subjects with every condition of the research, including the control. 
- Cross-over designs require less subjects than parallel group designs.
- Parallel group repeated measures designs are well suited for studying long term effects of treatments and changes over time. 
- Repeated measures models are efficient in utilizing all data and gaining precision.

### Example
|                  | Attributes           
| ---------------- | -------------------
| Population       | HIV patients who were intolerant to zidovudine therapy (Abrams et. al., NEJM, 1994)
| Disposition      | 230 patients startified by disease severity
| Design           | Parallel Group with 3 Treatment Arms: A ddC, B ddl Colin
| Duration         | 5 visits: at baseline, 2 months, 6 months, 12 months and 18 months
| Primary Endpoint | Change in CD4 count over time, CHG=Change from Baseline CD4

### Some advantages of repeated measure models are:
1. Will allow to monitor how treatment effect changes over time
2. Will produce more efficient estimates than non-repeated models allowing statistical inference to be made with fewer subjects
3. Will produce tests with higher power (i.e. if an effect exists, your statistical test is more likely to detect it).

SAS can fit repeated measure designs within linear mixed models (proc mixed). This allows to accommodate for missing data and random effects.

### Model Assumptions of MMRM
- normally distributed data with specific covariance structure type(CS, UN, TOEP, AR(1), VC) .
- Missing at Random (MAR) ="missingness is independent of missing outcomes given observed outcomes and covariates."
