# Bank Marketing & Customer Behavior Analysis

### IBM Internship Project — Data Analytics & Machine Learning

Predicting customer subscription to term deposits using the Bank Marketing dataset, with exploratory data analysis, machine learning models, and an interactive Power BI dashboard.

---

## 📌 Project Overview

Banks spend significant resources on telemarketing campaigns to promote financial products such as term deposits. However, only a small percentage of customers actually subscribe, resulting in low campaign efficiency and high marketing costs.

This project analyzes customer demographics, financial information, and telemarketing campaign data to identify the factors influencing subscription, and builds predictive models to help make future campaigns more targeted and cost-effective.

## 🎯 Objectives

- Understand customer demographics and financial characteristics
- Analyze marketing campaign performance
- Identify factors affecting customer subscription
- Perform exploratory data analysis (EDA)
- Build and compare predictive machine learning models
- Generate actionable business recommendations
- Visualize insights through an interactive dashboard

## 📊 Dataset

| Attribute | Details |
|---|---|
| Source | [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing) |
| Records | 45,211 |
| Features | 16 input features |
| Target Variable | `y` (Yes / No — term deposit subscription) |
| Missing Values | None |
| Duplicate Records | None |

## 🔍 Key Insights

- Only **11.7%** of customers subscribed to a term deposit — a significant class imbalance
- **Call duration** is the strongest predictor of subscription (correlation: 0.39)
- **Students (28.7%)** and **retired customers (22.8%)** have the highest subscription rates
- Customers with **tertiary education** and **single marital status** subscribe more
- Higher account balance and **fewer contact attempts** correlate with higher conversion — quality over quantity

## 🤖 Machine Learning Models

Three classification models were trained and compared:

| Model | Notes |
|---|---|
| Logistic Regression | Simple, interpretable baseline |
| Decision Tree | Max depth = 6 |
| Random Forest | 200 estimators — best overall precision/recall balance |

Evaluation metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC (accuracy alone is misleading due to class imbalance).

## 📈 Dashboard

An interactive **Power BI dashboard** visualizes subscription rates by occupation, education, marital status, monthly trends, and campaign performance — enabling stakeholders to explore the data in real time.

## 🗂️ Repository Structure

```
├── README.md
├── IBM_Internship_Bank_Marketing_Report.docx        # Full written report
├── Bank_Marketing_Analysis_and_Prediction.ipynb      # EDA + ML notebook
├── IBM_project_dashboard.pbix            # Power BI dashboard file
├── IBM_Internship_Bank_Marketing_Dashboard.png       # Dashboard screenshot
└── Bank_Marketing_Dataset.csv                        # Dataset
```

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **Power BI** (interactive dashboard)
- **Microsoft Word** (project report)

## 💡 Business Recommendations

1. Prioritize marketing toward students, retired individuals, and single, well-educated customers
2. Reduce repeated calling — focus on call quality and relevance instead
3. Use the Random Forest model to score and prioritize leads before each campaign
4. Use a different messaging strategy for blue-collar and married customers (e.g., emphasizing long-term financial security)

## 👤 Author

**Shakshi Singh**
IBM Internship — Data Analytics & Machine Learning

---

*This project was completed as part of an IBM internship program.*
