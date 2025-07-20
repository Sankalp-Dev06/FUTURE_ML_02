# Chun Prediction

A professional machine learning system for predicting customer churn using telco customer data, featuring a bold black and red themed analytics dashboard.

---

## 🗂️ Project Structure

```
Chun_prediction/
├── config/                # Configuration files (config.py)
├── data/
│   ├── raw/               # Original dataset (telco_dataset.csv)
│   └── processed/         # Cleaned and split data (train/test/cleaned)
├── models/                # Trained models, encoders, and summaries
├── notebooks/             # Jupyter notebooks for EDA and model training
├── src/
│   └── data_processor.py  # Data processing pipeline
├── streamlit_app/
│   └── app.py             # Main Streamlit web application
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone <repo-url>
cd Chun_prediction
```

### 2. Install Dependencies

It is recommended to use a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Prepare the Data

Place your raw dataset in `data/raw/` as `telco_dataset.csv`.

### 4. Process the Data

```bash
python src/data_processor.py
```

This will generate cleaned and split data in `data/processed/`.

### 5. Train Models (Optional)

Use the Jupyter notebooks in `notebooks/` for data exploration and model training:

```bash
jupyter notebook
```

### 6. Launch the Web Application

```bash
streamlit run streamlit_app/app.py
```

---

## 📊 Features

- **Automated Data Processing:** Cleaning, encoding, scaling, and splitting.
- **Multiple ML Models:** Logistic Regression, Random Forest, XGBoost.
- **Model Comparison:** Evaluate and compare model performance.
- **Interactive Dashboard:** Executive metrics, analytics, and churn prediction.
- **Real-Time Prediction:** Assess churn risk for individual customers.
- **Business Insights:** Visualizations and actionable recommendations.
- **Professional UI:** Bold black and red theme, responsive design.

---

## 📁 Key Folders & Files

- `config/config.py` — Centralized configuration (paths, features, parameters)
- `data/raw/telco_dataset.csv` — Input dataset
- `data/processed/` — Cleaned, train, and test data
- `models/` — Saved models, encoders, and summaries
- `notebooks/` — EDA and model training notebooks
- `src/data_processor.py` — Data cleaning and feature engineering script
- `streamlit_app/app.py` — Main Streamlit dashboard

---

## 🖥️ Streamlit Dashboard Pages

- **🏠 Executive Dashboard:** KPIs, churn stats, revenue at risk
- **🔮 Churn Prediction:** Customer-level risk assessment and recommendations
- **📈 Analytics:** Contract, payment, and lifecycle analysis
- **🤖 Model Comparison:** Performance metrics and ROC curves
- **ℹ️ About:** System overview and business value

---

## ⚙️ Requirements

- Python 3.7+
- Streamlit
- pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, joblib
- Jupyter (for notebooks)

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📣 Business Value

- **Early Churn Detection:** Proactive retention strategies
- **Cost Optimization:** Focus on high-value customers
- **Revenue Protection:** Prevent loss and increase LTV
- **Data-Driven Decisions:** Actionable insights for business growth

---
