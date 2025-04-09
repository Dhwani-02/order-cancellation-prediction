# order-cancellation-prediction
Machine learning project to predict order cancellations and analyze customer behavior in e-commerce.
# 🧾 Order Cancellation Prediction

This project aims to predict whether an e-commerce order will be **Cancelled** or **Completed**, based on customer behavior, product details, and order information.

## 📊 Project Overview

Understanding why orders get cancelled is crucial for improving customer satisfaction and reducing business losses. This project uses machine learning to:
- Analyze patterns in cancellations
- Identify key influencing factors (e.g., product type, shipping, age group)
- Build a predictive model for real-time risk detection

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn
- Pickle (for model deployment)

## 🧠 Models Built

- **Logistic Regression** (Baseline)
- **Random Forest Classifier** (Best performer)

## 🔍 Key Insights

- Highest cancellations in **Smartphones** and **Tablets**
- Older age group customers cancel more frequently
- **Standard shipping** and **Credit Card** payments show higher cancellation rates
- Poor or neutral ratings are linked to more cancellations

## ✅ Business Recommendations

- Improve **standard shipping** experience
- Make the **website more readable** for older users
- Investigate potential issues with **credit card payments**
- Use the model to **flag risky orders** early and take proactive steps

## 🚀 Model Deployment

The best-performing model (Random Forest) is saved using `pickle` and can predict the cancellation status of new orders based on key features.

Sample code for prediction:
```python
loaded_model.predict(sample_input)
loaded_model.predict_proba(sample_input)
