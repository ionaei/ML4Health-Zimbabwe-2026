# Machine Learning for Health Applications, Zimbabwe 2026

Welcome to the **Machine Learning for Health** module.

This course introduces the **foundations of machine learning**, with a strong focus on:

- Linear models
- Regularisation
- Model evaluation
- Ensemble methods
- Application to real-world health data

The course builds from first principles and culminates in applying machine learning methods to health-related prediction tasks.

---

## Teaching Team

<div align="center">

<table>
<tr>
<td align="center">
<img src="assets/staff/iona_biggart.jpeg" width="160"><br>
<b>Iona Biggart</b><br>
PhD student at Imperial College London, with applied focus on AI for paediatric medicine. 
</td>

<td align="center">
<img src="assets/staff/marco_reed.jpeg" width="160"><br>
<b>Marco Reed</b><br>
PhD student at Imperial College London, with applied focus on AI for paediatric medicine. 
</td>

<td align="center">
<img src="assets/staff/kevin_meck.png" width="160"><br>
<b>Kevin Meck</b><br>
Biomedical and applied medical AI engineer at Neotree. 
</td>

<td align="center">
<img src="assets/staff/aditi_rao.jpeg" width="160"><br>
<b>Aditi Rao</b><br>
Doctoral candidate at Imperial College London with Neotree
</td>
</tr>
</table>

</div>

---

# Course Overview

Machine learning is transforming modern healthcare.  
From disease prediction to risk stratification and treatment modelling, robust statistical learning methods are central to evidence-based medicine.

This course focuses on **core machine learning methods** that form the backbone of applied health data science.

We concentrate on:

### 1️⃣ Linear Models
- Linear regression
- Logistic regression
- Bias–variance tradeoff
- Regularisation (L1 / L2)
- Model interpretation
- Feature importance
- Evaluation metrics

Linear models are essential because:
- They are interpretable
- They are statistically grounded
- They often perform surprisingly well in health data

---

### 2️⃣ Ensemble Methods
- Decision trees
- Random forests
- Gradient boosting
- Model comparison

Ensemble models:
- Capture non-linear structure
- Improve predictive performance
- Handle complex feature interactions

---

### 3️⃣ Application to Health Data

The final part of the course applies these methods to:
- Clinical-style datasets
- Structured tabular health data
- Real-world prediction problems

You will:
- Preprocess datasets
- Train models
- Compare performance
- Justify modelling decisions
- Interpret results in a healthcare context

---

# Learning Objectives

By the end of this course, you should be able to:

- Understand the mathematical foundations of linear models
- Explain regularisation and its necessity
- Implement regression and classification models in Python
- Compare model performance using appropriate metrics
- Apply ensemble models to structured datasets
- Critically evaluate modelling choices in health applications

---

# Repository Structure

This repository is organised into clearly structured folders:


### 📂 lectures/
Contains:
- Lecture slides
- Supplementary notes

### 📂 labs/
Contains:
- Jupyter notebook tutorials
- Practical exercises
- Applied modelling workflows

Each lab can be run locally or opened directly in Google Colab.


### 📂 assets/
Contains images and supporting files for documentation.

---

# Running the Labs

You may run the notebooks:

### Option 1: Locally

Create a Python environment:

```bash
conda create -n mlhealth python=3.11
conda activate mlhealth
pip install -r requirements.txt

```


## Course Origins

This module has been adapted and streamlined from:

**Machine Learning for Neuroscience (ML4NS)**  
https://ml4ns.github.io/

The original ML4NS course provided a comprehensive introduction to machine learning with applications in neuroscience.

This version has been redesigned to:

- Focus more heavily on linear and ensemble methods  
- Streamline deep learning components  
- Emphasise health and clinical data applications  

We gratefully acknowledge the original ML4NS teaching materials and contributors.

---

## Acknowledgements

We thank all past contributors to the ML4NS course and the Translational Machine Intelligence Lab for foundational teaching materials.