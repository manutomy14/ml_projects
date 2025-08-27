# 📊 Customer Churn Prediction with Machine Learning

This project presents a complete machine learning pipeline for predicting customer churn in the telecom sector. By analyzing customer behavior, service usage, and payment patterns, the model identifies individuals at risk of leaving — empowering businesses to take proactive retention measures.

---

## 📌 Problem Overview

Customer churn poses a major challenge to telecom providers, directly impacting revenue and customer lifetime value. The goal of this project is to build predictive models that classify whether a customer is likely to churn, using features such as tenure, contract type, internet service, and payment method.

---

## 🔧 Workflow Summary

### 1. 📂 Data Loading & Inspection
- Imported structured CSV data containing customer attributes and churn labels  
- Handled missing values, standardized formats, and removed irrelevant columns

### 2. 📊 Exploratory Data Analysis (EDA)
- Explored distributions of categorical and numerical features  
- Visualized churn patterns and feature correlations

### 3. ⚙️ Preprocessing
- Applied label encoding and one-hot encoding for categorical variables  
- Addressed class imbalance using SMOTE (Synthetic Minority Oversampling)  
- Ensured consistent data types and cleaned anomalies

### 4. 🧠 Feature Engineering
- Selected impactful features based on correlation and domain relevance  
- Scaled numerical features and handled outliers

### 5. 🤖 Model Training & Evaluation
- Trained Decision Tree, Random Forest, and XGBoost classifiers  
- Used cross-validation and train/test splits for robust evaluation  
- Assessed models using accuracy, precision, recall, F1-score, and confusion matrix

---

## ✨ Key Takeaways

- Tenure, contract type, and payment method emerged as strong churn indicators  
- SMOTE significantly improved model fairness across classes  
- Random Forest and XGBoost delivered the most balanced performance

---



## 🌀 Notes

- The notebook is modular and well-commented for easy understanding  
- Visualizations are designed for clarity and storytelling  
- Code is structured for reproducibility and future extension

---

## 🤝 Contributions

Suggestions, improvements, and alternative modeling approaches are welcome!  
Feel free to open an issue or submit a pull request.

---

## 📬 Contact

For questions or collaboration, reach out via [GitHub Profile](https://github.com/manutomy14)
