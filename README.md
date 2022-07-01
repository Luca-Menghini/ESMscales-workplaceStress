# Workplace stress in real time: Three parsimonious scales for the experience sampling measurement of stressors and strain at work
The present repository includes some of the supplementary materials of the article:

Menghini, L., Pastore, M., Balducci, C. (2022). Workplace stress in real time: Three parsimonious scales for the experience sampling measurement of stressors and strain at work, accepted for publication in the European Journal of Psychological Assessment.

The present Github repository is associated with the **[Open Science Framework (OSF) repository osf.io/87a9p](https://osf.io/87a9p)**. Here, we included the R code, and the full and brief reports of both data pre-processing and data analysis, whereas the remaining supplementary materials (including the data used in the study) are available from OSF.

Below, we list and describe the full set of supplementary materials. Click on the highlighted link to visualize the reports.

## Supplementary materials
- `S1_PowerAnalysis`: Reproducible R code&sup1; and generated **[full report](https://Luca-Menghini.github.io/ESMscales-workplaceStress/S1_PowerAnalysis/S1_powerAnalysis_fullReport.html)** of the a priori power analysis of the multilevel confirmatory factor analysis used to evaluate the factor structure of the three scales. A more synthetic PDF report is [available at this link](https://Luca-Menghini.github.io/ESMscales-workplaceStress/S1_PowerAnalysis/S1_powerAnalysis_shortReport.pdf).

- `S2_dataProcessing`: R code and generated **[full report](https://Luca-Menghini.github.io/ESMscales-workplaceStress/S2_dataProcessing/S2_dataProcessing_report.html)** of the data pre-processing steps implemented to aggregate and recode single raw data files into the processed data `S5`. In compliance with the GDPR, only processed data without participants' personal information are publicly available, and they can be used to reproduce the `S3` outcomes.

- `S3_dataAnalysis`: Reproducible R code&sup2; and generated **[full report](https://Luca-Menghini.github.io/ESMscales-workplaceStress/S3_dataAnalysis/S3_dataAnalysis_fullReport.html)** of the analytical procedures described in the article. The folder also includes shorter PDF reports with details on [multilevel confirmatory factor analysis](https://Luca-Menghini.github.io/ESMscales-workplaceStress/S3_dataAnalysis/S3.1_MCFAdetails.pdf), and a supplementary analysis of [time trends, measurement reactivity, and sensitivity to job task features](https://Luca-Menghini.github.io/ESMscales-workplaceStress/S3_dataAnalysis/S3.2_SensitivityToContextualFactors.pdf) for each scale.

- `S4_scopusSearch` ([available from OSF](https://osf.io/8tcpv)): Results of the Scopus search of experience sampling methods studies on job stressors and strain.

- `S5_processedData` ([available from OSF](https://osf.io/87a9p/files/osfstorage)): GDPR-compliant processed data generaded by running the `S2` script on the raw data files. These can be used to reproduce the data analysis report in `S3` by using the associated Rmd script.

- `S6_ESMprotocol&scales` ([available from OSF](https://osf.io/87a9p/files/osfstorage)): Detailed description of the experience sampling methods protocol used in the study, including the JSON protocol used with the [Sensus mobile application](https://predictive-technology-laboratory.github.io/sensus/), and the evaluated scales (Italian items and English translations).


### Notes
1. The chunks of R code in the first part of the Rmd script are set with `eval = FALSE` to save computational time while generating the report. To reproduce the full report, set `eval = TRUE` or contact the first author to obtain the `TDS_PARAMETERS.RData`, `TCS_PARAMETERS.RData`, and `MDMQ_PARAMETERS.RData` files (too large to be shared here).
