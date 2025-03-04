# 📊 Customer Churn Prediction – Logistic Regression, Naïve Bayes & Ensemble Models

## 📝 Project Overview
This project builds **Customer Churn Prediction Models** using **Logistic Regression, Naïve Bayes, and Voting Ensemble** to predict whether a customer will churn based on historical data. 

### 📌 Dataset Overview
- **Total Observations:** 3,333  
- **Independent Variables:**
  - `AccountWeeks` → Number of weeks customer has had an active account  
  - `ContractRenewal` → 1 if customer recently renewed contract, 0 if not  
  - `DataPlan` → 1 if customer has data plan, 0 if not  
  - `DataUsage` → Gigabytes of monthly data usage  
  - `CustServCalls` → Number of calls into customer service  
  - `DayMins` → Average daytime minutes per month  
  - `DayCalls` → Average number of daytime calls  
  - `MonthlyCharge` → Average monthly bill  
  - `OverageFee` → Largest overage fee in the last 12 months  
  - `RoamMins` → Average roaming minutes per month  

- **Dependent Variable (Target)**:  
  - `Churn`: 1 if the customer canceled service, 0 if they remained.  

---

## 📊 Modeling Approach
### **1️⃣ Exploratory Data Analysis (EDA)**
✅ **Data Cleaning & Feature Selection**  
✅ **Pandas-Profiling Report for Initial Insights**  
✅ **Correlation Matrix & Feature Importance Analysis**  

### **2️⃣ Classification Models**
✅ **Logistic Regression** → A baseline model with regularization.  
✅ **Naïve Bayes Classifier** → Probabilistic classification method.  
✅ **Voting Ensemble Model** → Combines multiple classifiers for better performance.  

### **3️⃣ Model Evaluation**
✅ **Confusion Matrix & Classification Report** → Evaluates accuracy, precision, recall, F1-score.  
✅ **ROC-AUC Curve** → Measures model effectiveness in predicting churn.  
✅ **Comparison of Logistic Regression, Naïve Bayes, and Voting Ensemble Models**.  

---

## **📊 Key Results**
- **Logistic Regression Accuracy:** **80%**  
- **Naïve Bayes Accuracy:** **78%**  
- **Voting Ensemble Accuracy:** **83%**  
- **Best Model:** **Voting Ensemble performed the best in balancing precision and recall.**  

---

## **📂 Files Included**
📌 `churn_forecasting.ipynb` → Jupyter Notebook with all model implementations.  
📌 `Churn-Project-Report.pdf` → Detailed methodology and results.  
📌 `Churn-Presentation.pptx` → PowerPoint summary of findings.  

---

## 🚀 **How to Run**
1. Clone the repository:
   ```sh
   git clone https://github.com/jayp881998/Statistical-Modelling-Best-Practices.git
