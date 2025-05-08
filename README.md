# 📊 Customer Support Analytics Dashboard

This project explores and models customer support ticket data to uncover insights and predict Customer Satisfaction (CSAT). It includes exploratory data analysis (EDA), KPI calculations, and predictive modeling using machine learning.

---

## 📁 Project Structure

- **01_data_exploration.ipynb**  
  Initial EDA on ticket volumes, resolution times, customer behavior, and more.

- **02_kpis_analysis.ipynb**  
  Computation of key support KPIs such as:
  - Average Resolution Time
  - First Response Delay
  - Resolution Rate < 24h
  - CSAT Score
  - Channel Usage Breakdown

- **03_csat_prediction_model.ipynb**  
  Machine learning models to predict customer satisfaction:
  - Multiclass and binary classification
  - Feature importance analysis
  - Confusion matrix and performance evaluation

---

## 🧩 Key Insights

- **Resolution Time** is the strongest driver of satisfaction.
- Most tickets are marked as **Medium or Critical** priority.
- Email and Phone are the most used **channels**.
- Over 95% of tickets are resolved **after 24 hours**.
- Average CSAT is **2.99 / 5**, with balanced distribution across scores.

---

## 🔍 ML Performance Highlights

| Model Type        | Accuracy | Key Features                 |
|-------------------|----------|------------------------------|
| Multiclass CSAT   | ~20%     | Resolution Time, Age         |
| Binary CSAT       | ~57%     | Resolution Time, Age, Channel |

---

## 🛠️ Next Steps

- Improve modeling using NLP features from ticket text.
- Try balancing techniques like SMOTE for binary targets.
- Deploy as an interactive dashboard with Streamlit or Dash.

---

## 📌 Tech Stack

- **Python** (Pandas, Seaborn, Matplotlib, Scikit-learn)
- **Jupyter Notebooks** for exploration
- **Machine Learning**: Random Forest, Classification Metrics

---

## ✍️ Author

Saeideh Esmaeili  
[LinkedIn](#) | [Portfolio](#) | [Email](#)

---

> This project simulates an industry-level customer analytics workflow, suitable for portfolios in data science and analytics roles.


