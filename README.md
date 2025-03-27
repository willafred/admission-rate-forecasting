# Forecasting COPD and asthma demand for clinical impact in a South-East Asian setting: A climate-informed forecast combination framework
This file describes the various code used to generate the different models. The following describes the use of each file:

| File Name | File Description |
| --------- | ---------------- |
|01 data exploration caa 080225.Rmd | Generation of overall dataframe, and calling of API to extract environmental data |
|02 eda caa 080225.Rmd | Exploratory Data Analysis for the dataframe |
|03a models (cases).Rmd | Model functions used to generate results for raw admission cases for Asthma and COPD patients |
|03b models (subgroups).Rmd | Model functions used to generate results for admission rates for Asthma and COPD patient subgroups |
|03c models analysis 2 (exog, overall rate).Rmd | Model functions used to generate results for overall admission rates using exogenous variables |
|03d models analysis 2 (nonexog, overall rate).Rmd | Model functions used to generate results for overall admission rates without exogenous variables |
|04a combinations_270225.Rmd | Model functions used to generate forecast combinations |
|04b combinations caa 050325.Rmd | Model functions used to generate forecast generations for exogenous / non-exogenous or aggregated / total discharge rate analysis |
|05a plotting 090325.Rmd | Relevant functions to generate plots for main analysis for admission cases and subgroup admission rates for diseases |
|05b plotting.Rmd | Relevant functions to generate plots for second analysis for admission rates contrasting the use of exogenous / non-exogenous cases, and aggregated / total discharge rates |
|06a S1 generation 090325.Rmd| Functions used to generate data for Supplementary Information S1 |
|06b S2 generation 090325.Rmd| Functions used to generate data for Supplementary Information S2 |
|06c S3 generation 110325.Rmd| Functions used to generate data for Supplementary Information S3 |
