# Battery State of Health (SoH) Estimation — Transfer Learning

This project was carried out as part of a final year internship (PFE) on 
the estimation of the State of Health (SoH) of lithium-ion batteries, 
conducted at the Laboratoire Universitaire des Sciences Appliquées de 
Cherbourg (LUSAC).

---

## Associated Publication

This work led to a scientific article accepted at IEEE AAIEE 2026 :  
"Autoencoder-Based Signal Correction for Improved State-of-Health 
Estimation in Lithium-Ion Batteries"

---

## Description

- Data Preprocessing : anomaly treatment on time-series data from 
the NASA PCoE dataset
- ML Modeling : SoH estimation using Machine Learning regression models
- Analysis and Evaluation : model performance comparison and results 
interpretation using SHAP (MAPE, R², MSE)
- Deep Learning and Domain Adaptation : application of two Transfer 
Learning approaches (supervised and unsupervised) to improve performance

---

## Data

A description of the dataset is available in the data folder.  
See data/README.md for more details.

---

## Code

All implementation details are available in the notebooks folder.  
See the notebooks for the full code and experiments.

---

## Technologies

Python, TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, SHAP.
