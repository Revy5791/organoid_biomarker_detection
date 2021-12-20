# organoid_biomarker_detection
### ECBM 4060 - Intro to Genomic information science & Technology final report
## Prediction of Drug Response Based on Cancer Biomarkers Using Improved Network-Based Machine Learning Models
Project members:
Yumei Chen, Ziang Chen, Suwan Ding, Jiajun Li, Stuart Park

## Requirements
python 3, lifelines, gseapy

## Code
python: contains run_ssGSEA.ipynb, multiple_pathway_prediction.ipynb and single_pathway_prediction.ipynb

utilities: parse functions which will be used in run_ssGSEA.ipynb, multiple_pathway_prediction.ipynb and single_pathway_prediction.ipynb

data: all the preclinical and cancer patient data used in this project

## Instructions
Run "run_ssGSEA.ipynb" first to generate pathway level expression profiles using gseapy for organoid and TCGA data.

Then run "single_pathway_prediction.ipynb" or "multiple_pathway_prediction.ipynb" to predict drug response in cancer patients.

Results will be saved in python/results/COAD/organoid or TCGA (run_ssGSEA.ipynb), python/results/COAD/single_pathway_predictions, python/results/COAD/multi_pathway_predictions

When you run the code on your local computer, you need to change directory in all the code files.
