# 📊 Regression Analysis – Predicting Diamond Prices

## 📝 Project Overview
This project applies **Multivariate Regression Modeling** to predict **diamond prices** based on various features such as **carat, cut, color, and clarity**.

### 📌 Dataset Overview
- **Total Observations:** 53,940  
- **Independent Variables:**
  - `carat`: Weight of the diamond  
  - `cut`: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)  
  - `color`: Diamond color (J (worst) to D (best))  
  - `clarity`: Clarity grade (I1 (worst) to IF (best))  
  - `x, y, z`: Length, Width, Depth (mm)  
  - `depth`: Total depth percentage  
  - `table`: Width of the diamond’s top relative to its widest point  

- **Dependent Variable:**  
  - `price`: Diamond price in USD  

---

## 📊 Modeling Approach
### **1️⃣ Data Preprocessing**
✅ **One-Hot Encoding** → Converted categorical variables (`cut`, `color`, `clarity`) into numerical form.  
✅ **Feature Scaling** → Standardized numerical values for improved model performance.  
✅ **Train-Test Split** → 80% training, 20% testing dataset.  

### **2️⃣ Regression Model**
✅ **Equation Representation:**  
   \[
   \text{price} = \beta_0 + \beta_1(\text{carat}) + \beta_2(\text{cut}) + ... + \beta_n(\text{table})
   \]

✅ **Model Evaluation Metrics:**
   - **Adjusted R²:** Measures model fit  
   - **MAE (Mean Absolute Error):** Measures prediction error  
   - **RMSE (Root Mean Squared Error):** Evaluates model accuracy  

---

## **📊 Key Results**
- **Adjusted R²:** **0.87** *(Model explains 87% of price variation)*  
- **RMSE:** **750** *(Lower RMSE indicates better accuracy)*  
- **Feature Importance:**  
   - `carat` is the strongest predictor of price.  

---

## **📂 Files Included**
📌 `diamonds_regression.ipynb` → Jupyter Notebook for model implementation.  
📌 `Regression-Report.pdf` → Detailed report on methodology & results.  
📌 `Regression-Presentation.pptx` → PowerPoint summary of key insights.  

---

## 🚀 **How to Run**
1. Clone the repository:
   ```sh
   git clone https://github.com/jayp881998/Statistical-Modeling-Best-Practices.git
