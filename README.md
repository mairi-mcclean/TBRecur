# TBRecur

## Code to reproduce transcriptomic signature and clinical covariate models used. 


- TBSigProfiler.Rmd contains the code used for calculating Singscore GSEA scores and original gene signatures scores (Sweeney-3,MAMS-6,RISK-6,RISK-16,Tabone,Long-10). Requires user to clone the TBSigProfiler repo and set as working directory. 

- Vargas_signature_calculation.ipynb contains code to reproduce the reduced model from Vargas et al [https://doi.org/10.1371/journal.pcbi.1010770]
-- /fun and /vargas_final-ML-model/opt_score_rocauc contain functions required to run the notebook.

- Analysis_main.Rmd contains the main functions and workflow to reproduce study results (C-index discrimination, Firth's penalised regression) for signature and clinical covariates.

- LMM_clinical_covariates.Rmd contains the code used to run linear mixed models for the clinical covariates, including model selection (LRT and Variance components test)


Code under BDS-3 Clause License
