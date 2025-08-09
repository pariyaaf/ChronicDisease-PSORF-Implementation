# PSORF: Particle Swarm Optimization + Random Forest for Chronic Disease Classification

Implementation of the PSO–RF hybrid framework (PSORF) for classifying chronic diseases.  
This repo reproduces the core pipeline described in the referenced paper (link below), including **feature selection via PSO**, **Random Forest** classification, and **data-quality steps** (EM Imputation, SMOTE).

---

## 📎 Reference (Original Paper)
> Akansha Singh, Nupur Prakash, Anurag Jain.  
> **Particle Swarm Optimization–Based Random Forest Framework for the Classification of Chronic Diseases**. *IEEE Access*, 2023.  
> DOI: **10.1109/ACCESS.2023.3335314**

---

## 🧠 Method Overview
- **Feature Selection:** Particle Swarm Optimization (PSO) to search for an informative feature subset.
- **Classifier:** Random Forest (RF) with tuned hyperparameters.
- **Data Quality:**  
  - **EM Imputation** for missing values  
  - **SMOTE** for class imbalance
- **Evaluation:** Accuracy, Precision, Recall, F1, ROC-AUC (per dataset).

---

## 🗂️ Project Structure
