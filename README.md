# Iodine Removal from Nuclear Waterwaste using Metal Organic Frameworks(MOFs)
Here's a polished, markdown-formatted section that you can **copy and paste directly** into your `README.md` file on GitHub:

---

## 📂 Repository Structure

This repository contains datasets used in the research on "Predicting Iodine Removal from Nuclear Wastewater Using Machine Learning Models on Metal–Organic Frameworks (MOFs)".

Each file is structured to support different preprocessing and feature engineering strategies.

| File Name | Description |
|-----------|-------------|
| `Features_in_Iodine_Adsorption.csv` | 🧪 List of features (descriptors) used for modeling, including structural, chemical, and topological properties of MOFs. |
| `Augmented_Iodine_Adsorption.csv` | 📈 Augmented dataset that combines experimental and synthesized data for iodine adsorption capacity. Enhances the training process with more diverse samples. |
| **`MOF_mean.csv`** | 🧮 Dataset with missing values imputed using mean of each feature column. Useful for symmetric distributions. |
| **`MOF_median.csv`** | 🧮 Dataset with missing values imputed using median of each feature. Ideal for handling skewed distributions. |
| **`MOF_mode.csv`** | 🧮 Dataset with missing values imputed using mode (most frequent value). Best suited for categorical data. |
