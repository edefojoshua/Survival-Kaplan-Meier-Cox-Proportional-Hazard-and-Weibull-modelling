# Survival-Kaplan-Meier-Cox-Proportional-Hazard-and-Weibull-modelling
This R code demonstrated a complete survival analysis workflow in R using the lung dataset from the survival package. It began by loading the required libraries and exploring the dataset structure. Non-parametric survival estimation was performed using the Kaplan–Meier estimator, including stratified analyses by sex and performance status with visualisation and confidence intervals.

A Cox proportional hazards model was then fitted to assess the effects of sex, age, and Eastern Cooperative Oncology Group.(ECOG) performance status on survival time. Model diagnostics included tests of the proportional hazards assumption using Schoenfeld residuals, baseline hazard estimation, and survival function visualisation.

Finally, a parametric Weibull survival model was estimated. Model fit was assessed using Q–Q plots and residual analysis. Survival and hazard functions were derived and plotted for multiple patient profiles to illustrate covariate-specific risk patterns over time.

