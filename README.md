# 🏨 Hotel Booking Cancellation Prediction using Machine Learning

## 📌 Project Overview
This project focuses on analyzing hotel booking data and predicting whether a booking will be canceled or not using Machine Learning techniques.

The dataset includes features like lead time, customer details, booking information, and pricing (ADR). Using Exploratory Data Analysis (EDA) and ML models, we identify patterns and make accurate predictions.

---

## 🎯 Objectives
- Analyze the dataset and understand key features  
- Perform data cleaning and preprocessing  
- Handle missing values and remove irrelevant columns  
- Perform EDA using visualizations  
- Identify factors affecting booking cancellations  
- Build multiple ML models  
- Evaluate models using performance metrics  
- Select the best model  
- Perform predictions on new data  

---

## 📊 Dataset Information
- Dataset: Hotel Booking Dataset  
- Records: ~119,000  
- Features: 30+  
- Target Variable: `is_canceled`  
  - 0 → Not Canceled  
  - 1 → Canceled  

---

## 🧹 Data Preprocessing
- Removed unnecessary columns (name, email, phone, credit card, etc.)  
- Filled missing values:
  - `children` → 0  
  - `country` → mode  
  - `agent` → 0  
- Dropped `company` column (too many missing values)  
- Encoded categorical variables using Label Encoding  
- Split data into training and testing sets  
- Applied feature scaling  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Booking Cancellation Distribution
![Cancellation](Screenshots/Booking_Cancellation.jpeg)

### 🔹 Hotel Type vs Cancellation
![Hotel](Screenshots/Hotel_type_vs_cancellation.jpeg)

### 🔹 Monthly Booking Trend
![Monthly](Screenshots/Monthly_Bookings.jpeg)

### 🔹 ADR Distribution
![ADR](Screenshots/ADR_Distribution.jpeg)

### 🔹 Average Lead Time vs Cancellation
![Lead Time](Screenshots/Avg_Lead_Time_vs.jpeg)

### 🔹 Lead Time vs ADR (Scatter Plot)
![Scatter](Screenshots/Lead_time_vs_ADR.jpeg)

---

## 🤖 Machine Learning Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest ⭐  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

---

## 📈 Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- ROC Curve & AUC Score  

---

## 📊 Model Comparison
![Comparison](Screenshots/Model_Comparison.jpeg)

👉 Random Forest performed the best among all models.

---

## 📉 ROC Curve
![ROC](Screenshots/ROC_curve.jpeg)

👉 AUC Score ≈ **0.96 (Excellent Performance)**

---

## ⭐ Feature Importance
![Feature](Screenshots/Top_10_Imp_Feature.jpeg)

👉 Important features:
- Deposit Type  
- Lead Time  
- Country  
- ADR  

---

## 🔮 Prediction
The trained model predicts whether a booking will be canceled.

Example Output:

---

## 🏆 Conclusion
- Machine Learning models successfully predicted booking cancellations  
- Random Forest achieved the highest performance  
- Lead time and deposit type are key influencing factors  
- The model can help hotels reduce revenue loss  

---

## 🚀 Future Scope
- Use advanced models like XGBoost, LightGBM  
- Perform hyperparameter tuning  
- Handle class imbalance (SMOTE)  
- Deploy using Flask/Streamlit  
- Use real-time data  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 👨‍💻 Author
**Muneesh Sharma**  
M.Tech Data Science @ LPU  

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub!
