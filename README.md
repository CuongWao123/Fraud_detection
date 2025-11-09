# 🕵️‍♂️ Fraud Detection System

An end-to-end **Fraud Detection System** designed to identify and classify fraudulent transactions using machine learning techniques.  
This project replicates a real-world financial fraud detection workflow — from **EDA and feature engineering** to **model training, optimization, and experiment tracking**.

---

## 🚀 Project Overview
- Conducted **Exploratory Data Analysis (EDA)** to identify key patterns and correlations related to fraudulent transactions.  
- Processed large-scale tabular data using **DuckDB** and **Polars (LazyFrame)** to accelerate data analysis and reduce memory usage.  
- Addressed **class imbalance** through sampling and weighted training strategies.  
- Trained and benchmarked multiple ML models, including **Logistic Regression**, **Random Forest**, **LightGBM**, and **CatBoost**, achieving a strong **ROC-AUC score of 0.95**.  
- Used **MLflow** for experiment tracking, model versioning, and performance comparison.  
- (Optional) Integrated **DVC** for dataset version control and reproducible pipelines.

---

## 📊 Dataset
**Dataset:** [IEEE-CIS Fraud Detection (Kaggle)](https://www.kaggle.com/c/ieee-fraud-detection/data)  
- ~**590K rows** and **431 features** combining transaction and identity data.  
- File size: approximately **1.35 GB** after merging.  
- Features include numerical, categorical, and time-based variables.

> The dataset simulates real-world online transaction data, making it ideal for testing fraud detection models on imbalanced data distributions.

---

## ⚙️ Tech Stack
**Languages & Tools:**  
`Python`, `DuckDB`, `Polars`, `Pandas`, `Scikit-learn`, `LightGBM`, `CatBoost`, `MLflow`, `DVC`, `Matplotlib`, `Seaborn`

**Key Skills Demonstrated:**  
- Machine Learning (classification, feature engineering, model evaluation)  
- Data Pipeline Optimization (columnar processing, lazy evaluation)  
- Experiment Tracking & Reproducibility (MLflow, DVC)  
- Handling Imbalanced Datasets  
- EDA and Statistical Data Analysis  

---


## 📈 Results
| Model | ROC-AUC | Precision | Recall |
|-------|----------|------------|---------|
| Logistic Regression | 0.912 | 0.83 | 0.77 |
| Random Forest | 0.937 | 0.85 | 0.80 |
| LightGBM | 0.950 | 0.88 | 0.82 |
| CatBoost | **0.9537** | **0.89** | **0.84** |

✅ **Best model:** CatBoost — providing a balance of performance, interpretability, and efficiency.

---

## 🧩 Future Improvements
- Integrate **real-time fraud scoring API** for live prediction.  
- Experiment with **deep learning (TabNet / Autoencoder)** for anomaly detection.  
- Add **model explainability** using SHAP or LIME.  
- Deploy using **FastAPI** or **Streamlit** for interactive demo.

---

## 📬 Author
**Nguyen Van Cuong**  
- ✉️ [cuong.nguyenvan1150@gmail.com](mailto:cuong.nguyenvan1150@gmail.com)  
- 🌐 [GitHub: CuongWao123](https://github.com/CuongWao123)  
