# vcog_hps_ad

This repository contains packages, scripts, and notebooks for the following article [A signature of cognitive deficits and brain atrophy that is highly predictive of progression to Alzheimer’s dementia](https://doi.org/10.1101/352344).

Click the following link to reproduce the analysis with simulated data on binder: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/HanadS/vcog_hps_ad/master?filepath=%2Fvcog_hpc_prediction_simulated_data.ipynb)  

Here is a brief description of each item in the repository:
* **adas13_mixed_effects.ipynb** -  a Jupyter notebook that gives the linear mixed effects models for cognitive trajectories of different groups
* **adni_bl_vbm_pipeline_20171201.m** - an Octave script that runs a segmentation pipeline from SPM12 inside a NIAK container
* **adni_csv_merging.ipynb** - a Jupyter notebook that merges ADNI spreadsheets together
* **adni_filter_mci_csv.ipynb** - a Jupyter notebook that filters eligible MCI subjects
* **cog_hpc_prediction.ipynb** - a Jupyter notebook containing analyses that give a  highly predictive signature (HPS) of Alzheimer's disease dementia using cognitive features that were derived from real data
* **vbm_hpc_prediction.ipynb** - a Jupyter notebook containing analyses that give a highly predictive signature (HPS) of Alzheimer's disease dementia using structural features that were derived from real data
* **vbm_subtypes_glm.ipynb** - a Jupyter notebook that provides univariate tests between vbm subtypes and diagnosis
* **vbm_subtypes_pipeline.m** - an Octave script to build subtypes of grey matter atrophy and extract weights from structural T1 images
* **vcog_hpc_prediction.ipynb** - a Jupyter notebook containing analyses that give a highly predictive signature (HPS) of Alzheimer's disease dementia from cognitive and structural brain features that were derived from real data
* **vcog_hpc_prediction_simulated_data.ipynb** - a Jupyter notebook containing analyses that give a highly predictive signature (HPS) of Alzheimer's disease dementia from cognitive and structural features using *simulated data*
* **simulation_script.py** - a Python script that generates simulated data from raw data 
* **simulated_data.csv** - a comma separated value file that contains simulated data 
 

 
 

 
 
  








