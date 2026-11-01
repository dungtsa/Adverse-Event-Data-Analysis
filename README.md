# correctedData — Corrected Data Files

**Study:** Chen et al. (2023), *Cancers* 15:2521.  
"Early Adverse Event Derived Biomarkers in Predicting Clinical Outcomes in Patients with Advanced NSCLC Treated with Immunotherapy."  
DOI: 10.3390/cancers15092521 | PMID: 37173987

The previously released public data files (`clin.dataX.csv`, `AE.dataX.csv`) 
contain errors introduced during the public data preparation process. These include
incorrect survival times and event status for several patients, a completely missing
patient row (Cohort B), and systematic misclassification of early adverse events due
to use of an incorrect time origin (cycle-start proxy instead of true On Treatment Date).
The files in this folder provide corrected versions derived directly from the original
study data.
The chen2023_replication_correctedData.html is the update of analysis.
The chen2023_landmark_day30.html is sensitivity analysis by landmark analysis.
