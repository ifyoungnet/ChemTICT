# ChemTICT
Interpretable machine learning deconstructs the structural essence of TICT&amp;PICT fluorophores
# Overview
This repository is not an independent software or package, it provides the original code and dataset for the project "<i>***Interpretable Machine Learning Deconstructs the Structural Essence of TICT and PICT Fluorophores***</i>". This project addresses the challenge of accurately distinguishing whether the charge transfer in D-π-A type molecules exhibits TICT or PICT, while also providing accurate and practical AI-guided rules for the rational design of fluorophores with TICT and PICT.

## Key features
1. The First AI-Oriented Approach for TICT & PICT Exploration.
2. The unity of theoretical design and algorithmic guidance.

# System Requirements
This project is not limited to a specific hardware platform. Theoretically, it can run as long as the dependencies specified in the corresponding folder (`.yml`environment configuration file) are met.
Suggested hardware configuration is as follows: RAM: 16+ GB, CPU: 8+ cores, 3.3+ GHz per core; GPU (Optional): NVIDIA 3090Ti or higher`.

# Content of each folder
1.	<b>Dataset</b>: The datasets used in this project. 
2.	<b>Machine learning</b>:
- `Create you env for ML.yml` (Configuration file of machine learning environment)
-	`ML model training and interpretation.ipynb` ( Code for machine learning model training & interpretation)
-	`Simplified model training and visualization.ipynb` (Code for simplified model)
3.	<b>Deep learning</b>:
- `Create your env for DL.yml` (Configuration file of deep learning)
- `DL model training and interpretation.ipynb` (Code for deep learning training & interpretation)
4.	<b>Best model</b>:
-	`AtomPairfinal_model.pkl` (Best model in .pkl format)

5.	<b>Videos</b>:
- Vedios logging the main training process of our models.

6.	<b>Demos</b>:
-	See "How to use" section!

# How to use
## Predict new molecules using our best model
-	Step 1: Run `Demo1 Calculate descriptors.ipynb`(The example input file is: `Inputs of Demo1.csv`; the example output file is: `Outputs of Demo1.csv`);
-	Step 2: Run `Demo2 Call the best model and prediction.ipynb`(The example input file is: `Outputs of Demo1.csv`; the example output file is: `Outputs of Demo2.csv`);






  
