# Airbnb-Anomaly-Detection
Anomaly detection in Airbnb listings using Isolation Forest and DBSCAN, with data visualization in Python.

# 🏘️ Airbnb Anomaly Detection Using Machine Learning

This project detects pricing and review anomalies in Airbnb listings using unsupervised machine learning techniques like Isolation Forest and DBSCAN. The goal is to identify unusual patterns that may indicate errors, fraud, or outlier behavior.

## 🔍 Problem Statement
Airbnb listings often contain unusual spikes in prices, inconsistent availability, or review anomalies. This project aims to detect such outliers to improve data reliability and support better platform monitoring.

## 📁 Data
Used one-month samples from Airbnb’s open datasets:
- `listings.csv` – property details
- `calendar.csv` – daily pricing and availability
- `reviews.csv` – user review metadata

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Unsupervised ML: Isolation Forest, DBSCAN

## 📊 Key Features
- Cleaned and merged large datasets from multiple Airbnb data sources
- Performed EDA to understand pricing and review distributions
- Applied anomaly detection models to flag listings with abnormal pricing or review behavior
- Visualized findings using Matplotlib

## ✅ Outcome
Successfully identified listings with pricing outliers and review anomalies that could affect trust on the platform. The approach is scalable and adaptable to other short-term rental datasets.

