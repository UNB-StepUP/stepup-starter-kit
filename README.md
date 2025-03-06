# StepUP Starter Kit

This repository contains example code for the 2025 IJCB StepUP Footstep Recognition Competition.

Please ensure you have downloaded the competition dataset before continuing.


# Dataset Download

The competition dataset can be downloaded from OneDrive [here](https://unbcloud-my.sharepoint.com/:f:/g/personal/q4k8p_unb_ca/EgGl2JeFJDNLiw35gBh5sjkBowFrY5-ACjhU3FRvmDXVRg?e=50yjW4).

Download and extract the dataset to a known location on your computer. You will need to specify the folder path to the dataset when running this example code.


# Installation

Example code is provided in python as a jupyter notebook. All required dependencies are documented in the provided `requirements.txt` file.

Run the following command to install project requirements:

```bash
pip install -r ./requirements.txt
```


# Running the Starter Kit

The starter kit is provided as a jupyter notebook. 

Modify the `dataset_root` path found in cell 2 as appropriate for your environment, then run the notebook to train and evaluate the provided baseline model.

You are free to use and modify this code as needed during the competition.


# Submitting your Results on CodaBench

All competition submissions must be made on [CodaBench](https://www.codabench.org/competitions/5872/). Your submission should be packaged as a single zipfile containing two items:

1. `scores.txt` - which contains a similarity score for each probe set test case, and 
2. `threshold.txt` - which contains a single numeric decision threshold.

A utility function is provided at the bottom of the notebook to create this zipfile (see `package_predictions_for_submission()`).
