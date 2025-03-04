# 📊 Regularization – LASSO, Ridge, and Elastic Net for Energy Use Forecasting

## 📝 Project Overview
This project applies **Regularization Techniques** (LASSO, Ridge, and Elastic Net) on the `EnergyUse-Heating.csv` dataset. The objective is to predict **total heating load** based on multiple features while avoiding overfitting.

### 📌 Dataset Overview
- **Total Observations:** 768  
- **Independent Variables:**
  - `X1` → Relative Compactness  
  - `X2` → Surface Area  
  - `X3` → Wall Area  
  - `X4` → Roof Area  
  - `X5` → Overall Height  
  - `X6` → Orientation  
  - `X7` → Glazing Area  
  - `X8` → Glazing Area Distribution  

- **Dependent Variable (Target)**:  
  - `y` → Heating Load  

---

## 📊 Modeling Approach
### **1️⃣ Data Preprocessing**
✅ **Outlier Removal** → Used Tukey’s Method to remove outliers.  
✅ **Feature Scaling** → Standardized numerical values.  
✅ **Train-Test Split** → 80% training, 20% testing.  

### **2️⃣ Regularization Models**
✅ **LASSO Regression** → Shrinks coefficients to zero for feature selection.  
✅ **Ridge Regression** → Penalizes large coefficients but does not eliminate variables.  
✅ **Elastic Net Regression** → Combines both LASSO and Ridge benefits.  

### **3️⃣ Model Evaluation**
✅ **Adjusted R²** → Measures model fit while considering regularization.  
✅ **Mean Absolute Error (MAE) & RMSE** → Evaluates prediction performance.  
✅ **Feature Importance Analysis** → Identifies the most significant predictors.  

---

## **📊 Key Results**
- **LASSO Model Selected Features:** Reduced 2 unimportant variables.  
- **Ridge Regression RMSE:** **Lower than LASSO, but slightly higher complexity.**  
- **Elastic Net Provided Best Tradeoff:** Accuracy vs. Feature Selection.  

---

## **📂 Files Included**
📌 `energyuse_regularization.ipynb` → Jupyter Notebook with all models.  
📌 `Regularization-Report.pdf` → Detailed methodology and results.  
📌 `Regularization-Presentation.pptx` → Summary of findings.  

---

## 🚀 **How to Run**
1. Clone the repository:
   ```sh
   git clone https://github.com/jayp881998/Statistical-Modelling-Best-Practices.git
