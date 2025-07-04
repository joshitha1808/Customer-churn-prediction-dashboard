# 📊 Customer Churn Prediction and Dashboard

This project focuses on identifying customers who are likely to churn (i.e., stop using the service) using machine learning techniques. The insights are visualized using **Power BI**, with initial data exploration done in **Excel** and the churn prediction model built in **Python using Google Colab**.

---

## 🔍 Problem Statement

Customer churn significantly impacts the revenue of subscription-based businesses. Predicting churn helps companies retain customers by taking proactive steps. This project aims to:
- Predict whether a customer will churn using historical data
- Analyze and visualize churn patterns
- Provide actionable insights via dashboards

---

## 🧰 Tools and Technologies

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Google Colab**
- **Power BI**
- **Microsoft Excel**

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `customer_churn_model.ipynb` | Google Colab notebook for model building and evaluation |
| `churn_data.xlsx` | Raw data with initial Excel-based analysis |
| `churn_dashboard.pbix` | Interactive Power BI dashboard showing churn insights |
| `README.md` | Project documentation (this file) |

---

## 📌 Key Features

- Cleaned and prepared customer churn dataset
- Model training using Logistic Regression / Decision Tree
- Performance metrics: Accuracy, Confusion Matrix, Precision, Recall
- Feature importance plotted to show key churn indicators
- Power BI dashboard with filters, KPIs, and visual trends

---

## 📊 Power BI Dashboard Overview

The Power BI dashboard includes:
- Overall churn rate
- Churn by contract type, tenure, payment method
- Interactive filters for customer demographics
- Visual KPIs to support business decisions

---

## 🧠 Machine Learning Workflow (Python - Google Colab)

1. **Data Preprocessing**  
   - Handled missing values  
   - Converted categorical variables using one-hot encoding

2. **Modeling**  
   - Used Logistic Regression and Decision Tree  
   - Evaluated with confusion matrix, accuracy, precision, recall

3. **Insights**  
   - Identified top churn indicators like contract type, tenure, monthly charges

---

## 📈 Results

- Model achieved high recall, ensuring most churn cases are identified
- Churn rate is highest among customers with month-to-month contracts
- Dashboard helps stakeholders quickly understand churn drivers

---

## 🚀 How to Run

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com) and run all cells
2. Open `churn_dashboard.pbix` in Power BI Desktop to explore insights
3. Use `churn_data.xlsx` for initial data reference and summaries

---

## ✅ Future Enhancements

- Deploy model using Streamlit for web interface
- Automate dashboard refresh with Power BI service
- Add real-time churn prediction using live customer data

---

## 📬 Contact

For questions or collaboration opportunities, feel free to connect!
