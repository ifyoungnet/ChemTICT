# ChemTICT
Interpretable machine learning deconstructs the structural essence of TICT&amp;PICT fluorophores
# Overview
This repository is not an independent software or package, it provides the original code and dataset for the project "<i>Interpretable Machine Learning Deconstructs the Structural Essence of TICT and PICT Fluorophores</i>". This project addresses the challenge of accurately distinguishing whether the charge transfer in D-π-A type molecules exhibits TICT or PICT, while also providing accurate and practical AI-guided rules for the rational design of fluorophores with TICT and PICT.

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
o	tf2.yml (Deep learning Environment configuration File)
o	SOTA_comparison.ipynb (MolMapNet Training & Interpretation Code)
4.	Best model:
o	AtomPair.ipynb (Calculate Atompair fingerprint)
o	AtomPairfinal_model.pkl (Best Model in pkl Format)
o	best_model.ipynb (Example Code for Predicting Compound 1 and Compound 2, where 1 represents TICT and 0 represents PICT)
5.	Video:
o	Demonstrations of the training and model interpretation process to save researchers' setup time.
