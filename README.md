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
  <img width="1919" height="759" alt="Screenshot 2025-07-20 182942" src="https://github.com/user-attachments/assets/f8443804-2a67-46ef-839e-28f296587228" />
  <img width="1917" height="875" alt="Screenshot 2025-07-20 182924" src="https://github.com/user-attachments/assets/194c2ea7-021c-4fbb-8545-e9c7de405443" />
  
- **🔮 Churn Prediction:** Customer-level risk assessment and recommendations
  <img width="1880" height="863" alt="Screenshot 2025-07-20 183005" src="https://github.com/user-attachments/assets/36cc66fc-4175-4a72-a094-ad15ab331a77" />
  <img width="1918" height="874" alt="Screenshot 2025-07-20 183024" src="https://github.com/user-attachments/assets/65e902e0-bbaf-4cca-a9e3-00f9780ecc9f" />

- **📈 Analytics:** Contract, payment, and lifecycle analysis
  <img width="1538" height="873" alt="Screenshot 2025-07-20 183058" src="https://github.com/user-attachments/assets/18982a20-e0c1-4b5d-9b14-c44018c71b67" />
  <img width="1524" height="567" alt="Screenshot 2025-07-20 183112" src="https://github.com/user-attachments/assets/7e377a83-81a6-46fb-9f8f-482ab22e51da" />

- **🤖 Model Comparison:** Performance metrics and ROC curves
  <img width="1898" height="870" alt="Screenshot 2025-07-20 183130" src="https://github.com/user-attachments/assets/bbd0c8fc-6058-4d9e-8857-52eb517cd5e5" />
  <img width="1905" height="867" alt="Screenshot 2025-07-20 183155" src="https://github.com/user-attachments/assets/a8e0b944-9c64-4a29-824a-bf14d66fa541" />

- **ℹ️ About:** System overview and business value
  <img width="1903" height="870" alt="Screenshot 2025-07-20 183211" src="https://github.com/user-attachments/assets/bea57601-65bd-44e3-ba51-5028d1855df8" />


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
## 👤 Author

**Developed by:**  
- Sankalp Tiwari  
- [LinkedIn](www.linkedin.com/in/sankalp-tiwari-350545203)  
- [GitHub](https://github.com/Sankalp-Dev06)