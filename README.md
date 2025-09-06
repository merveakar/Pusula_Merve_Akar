Merve Akar
05422206614
merveakar2506@gmail.com


# 🩺 Physical Medicine & Rehabilitation Dataset Analysis

A complete end-to-end analysis pipeline for the Physical Medicine & Rehabilitation dataset, including **Exploratory Data Analysis (EDA)**, **data preprocessing**, and **model-ready dataset generation**.

---

## 📌 Project Overview

This project analyzes and preprocesses healthcare data consisting of **2235 observations and 13 features**.  
The main goal is to prepare the dataset for predictive modeling of the target variable:  
**`TedaviSuresi (Treatment Duration)`**

---

## 🎯 Objectives
- Perform **comprehensive EDA** to understand data patterns, distributions, and anomalies  
- Apply **data preprocessing** techniques to clean and standardize the dataset  
- Produce a **model-ready dataset** suitable for machine learning  

---

## 📊 Dataset Information

| Column           | Description |
|------------------|-------------|
| HastaNo          | Patient ID (anonymized) |
| Yas              | Patient age |
| Cinsiyet         | Gender |
| KanGrubu         | Blood type |
| Uyruk            | Nationality |
| KronikHastalik   | Chronic diseases (comma-separated) |
| Bolum            | Department/Clinic |
| Alerji           | Allergies |
| Tanilar          | Diagnoses |
| TedaviAdi        | Treatment name |
| **TedaviSuresi** | **Treatment duration (TARGET)** |
| UygulamaYerleri  | Application sites |
| UygulamaSuresi   | Application duration |

---

## 📁 Project Structure

```
Pusula_Merve_Akar/
│
├── 📊 Data Files
│   └── Talent_Academy_Case_DT_2025.xlsx
│
├── 🔧 Core Modules
│   ├── config.py
│   ├── data_loader.py
│   ├── eda_analyzer.py
│   ├── data_preprocessor.py
│   └── main_pipeline.py
│
├── 📓 Notebook
│   └── EDA_Analysis_Complete.ipynb
│
├── 📋 Documentation
│   ├── README.md
│   └── Documentation.md
│
└── 📂 Output
    ├── plots/
    ├── reports/
    ├── models/
    ├── processed_data_[timestamp].csv
    └── train_test_splits_[timestamp].csv
```

---

## 🔍 Features

### EDA
- Target variable distribution & outlier detection  
- Numerical & categorical feature analysis  
- Correlation analysis & feature relationships  
- Missing value detection & visualization  
- Data quality checks (uniqueness, consistency, completeness)  

### Preprocessing
- Missing value imputation (Simple, KNN)  
- Outlier treatment (IQR, Z-score)  
- Categorical encoding (Label, One-Hot, Auto)  
- Feature scaling (Standard, MinMax, Robust)  
- Feature engineering  
- Train/test splitting with stratification  

---

## 🚀 Quick Start

### Run Complete Pipeline
```bash
python main_pipeline.py
```

### Or in Jupyter Notebook
```bash
jupyter notebook EDA_Analysis_Complete.ipynb
```

---

## ⚙️ Installation

### Requirements
- Python 3.7+
- See `requirements.txt`

### Setup
```bash
pip install -r requirements.txt
```

---

## 📊 Outputs

- **Plots** → `/output/plots/`  
- **Reports** → `/output/reports/`  
- **Processed Data** → `/output/processed_data_[timestamp].csv`  
- **Model Artifacts** → `/output/models/`  

---

## 🎯 Model-Ready Data Includes:
✅ No missing values  
✅ Encoded categorical variables  
✅ Scaled numerical features  
✅ Outlier treatment applied  
✅ Feature engineering completed  
✅ Train/test splits prepared  

---

## 🤝 Contributing

You can extend the project by:  
- Adding new EDA methods  
- Improving preprocessing strategies  
- Testing different ML models on the processed data  

---

## 📝 License

This project was created for the **Talent Academy Case Study (2025)**.  
It is intended for **educational and evaluation purposes only**.
