Project title:
Proof-of-Concept Machine Learning Workflow for Predicting Double-Shear Strength in 15-5PH Aerospace Fasteners

Scientific question:
Can Ridge Regression predict job-level mean double-shear strength of 15-5PH aerospace fasteners using internal manufacturing records?

Dataset:
Raw dataset derived from internal manufacturing records and is not publicly released.  A processed/anonymized CSV is included in the data folder to reproduce the workflow.

Run order:
01_data_acquisition.ipynb → 02_eda_featurization.ipynb → 03_modeling.ipynb → 04_results_visualization.ipynb

Key result:
Ridge Regression reduced validation MAE from 1.678 ksi for the mean baseline to 0.561 ksi using lot-grouped validation.