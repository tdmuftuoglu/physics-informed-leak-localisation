# physics-informed-leak-localisation
A hybrid physics-guided ML tool for robust leak detection and uncertainty quantification in hydraulic systems.

# Beyond the Analytic Baseline: Physics-Informed Hybrid Framework for Leak Localisation 
### (University of Pretoria Case Study)

This repository provides a reproducible Google Colab pipeline for leak localisation and sizing in water distribution pipes using a physics-informed hybrid machine learning framework. The methodology combines steady-state hydraulic priors with multi-scale feature extraction and conformal uncertainty quantification. This work is associated with the scientific study: 

---

## How to Use (Google Colab) 
This project is designed for interactive execution in Google Colab using a single monolithic script. 


1. **Open the Notebook:** Open the provided `.ipynb` file in Google Colab.
   
2. **Run the Code:** The framework is contained within a single cell. Click the **"Play"** button to execute.

3. **Interactive Data Upload:** The script will automatically prompt you to upload the required `.npy` data files.
  
4. **Automatic Results:** Diagnostic plots, feature rankings, and error analyses will be generated and downloaded automatically.

---

## Outputs / Üretilen Çıktılar
The framework automatically generates several diagnostic figures to evaluate model performance, such as:

* Bootstrap Analysis on Analytic Estimator
* Baseline vs Hybrid Model Parity Plots 
* Error Budget Decomposition 
* Conformal Prediction Intervals 
* Feature Importance Analysis 
* Signal Analysis (Time Series & PSD) 

---

## Citation / Atıf
If you use this code or methodology in your research, please cite the original author and the repository:


**Müftüoğlu, T. D. (2026). Beyond the analytic baseline: a physics-informed hybrid framework for leak localisation and sizing in water distribution pipes, with quantified model-error and measurement-noise budgets.


}
