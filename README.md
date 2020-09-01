# Complementary Code and Data of my Master Thesis

This repository contains the collected data and used code for the main study of my master thesis. The data is anonymized and cut into individual trials. Movement data was recorded through the eSense in-ear device. 

Several programs have been used for data preprocessing and analysis.

- SynchronySplit.ipynb: 
This file can be used to manually synchronize the recordings of two eSense devices given a distinctive audio-motion gesture. 
- TrialSplit.ipynb
Provided an excel-file containing the start and end time of individual trials, cuts whole sensor recordings of experiments into the respective trials. 
- load_data_for_analysis.ipynb and all scripts within that folder: 
Takes recordings of all trials from one study, pre-processes it and calculates the average movement energy for individual trials and a wavelet coherence analysis. These scripts were originally developed by Jamie A Ward. 
