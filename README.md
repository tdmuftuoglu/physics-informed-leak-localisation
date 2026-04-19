# physics-informed-leak-localisation
A hybrid physics-guided ML tool for robust leak detection and uncertainty quantification in hydraulic systems.

# Beyond the Analytic Baseline: Physics-Informed Hybrid Framework for Leak Localisation 
### (University of Pretoria Case Study)

This repository provides a reproducible Google Colab pipeline for leak localisation and sizing in water distribution pipes using a physics-informed hybrid machine learning framework. The methodology combines steady-state hydraulic priors with multi-scale feature extraction and conformal uncertainty quantification. 

---

## How to Use (Google Colab) 
This project is designed for interactive execution in Google Colab using a single monolithic script. 

1. **Open the Notebook:** Open the provided `.ipynb` file in Google Colab.
   
2. **Run the Code:** The framework is contained within a single cell. Click the **"Play"** button to execute.

3. **Interactive Data Upload:** The script will automatically prompt you to upload the required `.npy` data files.
  
4. **Automatic Results:** Diagnostic plots, feature rankings, and error analyses will be generated and downloaded automatically.

---

## Outputs 
The framework automatically generates several diagnostic figures to evaluate model performance, such as:

* Bootstrap Analysis on Analytic Estimator
* Baseline vs Hybrid Model Parity Plots 
* Error Budget Decomposition 
* Conformal Prediction Intervals 
* Feature Importance Analysis 
* Signal Analysis (Time Series & PSD) 

---

## Acknowledgments & Data Source
The experimental data used in this framework was generated and provided by the Centre for Asset Integrity Management, Department of Mechanical and Aeronautical Engineering, University of Pretoria. We gratefully acknowledge the original authors for making their dataset openly available:

**Van Der Walt, JC; Heyns, PS; Wilke, DN (2020). Single section of pipe for leak detection. figshare. Dataset. https://doi.org/10.6084/m9.figshare.12973148.v2**

---

## Citation 
If you use this code or methodology in your research, please cite the original author and the repository:

**Müftüoğlu, T. D. (2026). Beyond the analytic baseline: a physics-informed hybrid framework for leak localisation and sizing in water distribution pipes, with quantified model-error and measurement-noise budgets. 

