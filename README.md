# 💳 AI Fraud & Anomaly Detection System

## 📌 Project Overview
A high-performance Machine Learning pipeline built to detect fraudulent financial transactions in massive, highly-imbalanced datasets (IEEE-CIS). The project utilizes GPU acceleration to process over 500,000 records and features an interactive security dashboard.

## 🚀 Technical Architecture
* **Environment:** Google Colab (T4 GPU Accelerated)
* **Data Engineering:** Pandas, Numpy (Custom Memory Downcasting saving 50%+ RAM)
* **Machine Learning:** XGBoost (`scale_pos_weight` for extreme class imbalance)
* **Evaluation:** Area Under Precision-Recall Curve (AUPRC)
* **UI/UX:** Plotly Gauge Charts & IPython Widgets

## ⚙️ Key Features
1. **Big Data Pipeline:** Direct Kaggle API integration bypassing local storage limits.
2. **Automated Feature Engineering:** Label encoding and null-value purging.
3. **Interactive Simulator:** A built-in dashboard allowing users to multiply transaction amounts and watch the AI's risk score react in real-time.

## 📊 Results
The model successfully prioritized the minority fraud class, achieving an **82% Recall** rate on fraudulent transactions without relying on synthetic data generation (SMOTE).
