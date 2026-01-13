# Shopping-Behavior-Analysis-Using-Machine-Learning
This project predicts e-commerce revenue based on user behavior using a k-nearest neighbors classifier. By analyzing user interactions such as product views and session durations, it classifies purchase likelihood. Model performance is evaluated using sensitivity and specificity metrics.

##  Project Overview

This project uses machine learning to predict whether an online user will make a purchase based on their browsing behavior. It applies a **k‑nearest neighbors (KNN)** classifier to analyze session data such as page views, session duration, bounce rates, and visitor type. The model is evaluated using **sensitivity** and **specificity**, offering a balanced view of performance.

---

##  Why This Matters

Understanding user behavior is critical for e‑commerce optimization. By predicting purchase likelihood, businesses can tailor experiences, boost conversion rates, and improve marketing ROI. This project translates raw clickstream data into actionable business insights.

---

##  Features

Predicts e‑commerce purchase likelihood with machine learning  
Uses KNN classifier for simplicity and interpretability  
Measures performance using true positive and true negative rates  
Easy‑to‑run Python script with minimal dependencies

---

##  Dataset

This project uses the **Online Shoppers Purchasing Intention Dataset**, which contains clickstream data such as:
- Number of pages visited
- Duration on different page types
- Bounce and exit rates
- Visitor type (new or returning)
- Whether a purchase was made

> Dataset source: UCI Machine Learning Repository.

---

##  Requirements

Make sure you have:

- Python 3.x  
- scikit‑learn  
- pandas  
- numpy

Install dependencies with:

```bash
pip install -r requirements.txt
