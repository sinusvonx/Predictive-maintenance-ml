# 🔧 Predictive Maintenance with Machine Learning

This project is a reproduction of a machine learning system I developed during my time at **Bosch**. The original version predicted maintenance needs for sintering and debinding furnace systems. This public version recreates the workflow with synthetic data and simplified logic, suitable for demonstration and portfolio purposes.

---

## 🔍 Original Bosch Project (Background)

- Machines: Industrial furnace lines
- Problem: No fixed maintenance schedule → unpredictable downtimes
- Goal: Predict maintenance need based on sensor and runtime data
- Complexity at Bosch:  
    - Real-time sensor streaming  
    - Sensor drift correction and denoising  
    - Time-windowing for sensor series  
    - Feature importance over multivariate interactions  
    - Integration with live dashboards and backend systems  

---

## 📊 Project Summary

| Step | Description |
|------|-------------|
| 📁 Data | Synthetic dataset (5,000 samples) with 20+ realistic features |
| 📈 Models | Random Forest & XGBoost with hyperparameter tuning |
| 🧠 Explainability | SHAP for global & local model insights |
| 🎯 Target | Binary classification: failure within next 30 days |
| 📉 Metrics | Accuracy, Precision, Recall, F1, ROC AUC, Confusion Matrix |

---

## 🛠️ Stack

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`, `shap`
- `joblib` for model saving

---

## 🚀 How to Run

1. Clone this repository  
2. Install the requirements  
3. Run the Jupyter notebook  
4. Explore the SHAP visualizations

```bash
pip install -r requirements.txt
```

```python
# Run the notebook step-by-step
```

---

## 📁 Structure

```
predictive-maintenance-ml/
├── data/
│   └── synthetic_predictive_maintenance.csv
├── notebook.ipynb
├── models/
│   └── rf_model.pkl
│   └── xgb_model.pkl
├── README.md
├── requirements.txt
```
