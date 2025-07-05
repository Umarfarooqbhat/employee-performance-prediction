# Employee Performance Prediction using Machine Learning

This project was completed as part of my **Data Science Internship at Teach For India**.  
It builds a machine learning model to predict employee performance using past metrics such as demographic data, awards, and training records.

---

## 📁 Project Structure
├── data/ # Raw or cleaned dataset
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── models/ # Saved model files (optional)
├── visuals/ # Plots: heatmap, ROC, confusion matrix, etc.
├── Employee_Analysis.ipynb # Main notebook
├── README.md # Project documentation
---

## 🎯 Objective
To develop a predictive ML model that classifies employees as high or low performers using features like:
- Age, education, department, gender
- Training count
- Previous year’s rating
- Length of service
- Awards won

---

## 📊 EDA & Preprocessing Highlights
- Cleaned missing values and encoded categorical features
- Correlation matrix via heatmap
- Feature scaling using multiple scalers:
  - StandardScaler
  - MinMaxScaler
  - RobustScaler
  - MaxAbsScaler

---

## 🤖 ML Models Evaluated
- **XGBoost**
- **LightGBM**
- **CatBoost** (Best Performing)

---

## ✅ Why CatBoost?
- Natively supports categorical variables  
- High accuracy, precision, F1, and AUC  
- Robust to overfitting  
- Delivered the most consistent results on test data

---

## 📈 Evaluation Metrics
- Confusion Matrix
- ROC-AUC Curve
- Precision, Recall, F1 Score
- Accuracy Score

---

## 📌 Business Recommendations
- Focus on retraining or upskilling employees predicted to underperform  
- Recognize impact of past awards and training programs  
- Use prediction insights alongside HR reviews for better decision-making

---

## 📁 Project Deliverables
- Cleaned Jupyter Notebook
- Visualizations (heatmaps, ROC, confusion matrices, etc.)
- Summary Report (PDF/DOCX)
- GitHub-ready README

---

## 🙋‍♂️ Author

**Umar Farooq Bhat**  
📧 umarfarooqbhat94@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/umar-bhat-data/)

*Internship Project at Teach For India (2025)*

---

