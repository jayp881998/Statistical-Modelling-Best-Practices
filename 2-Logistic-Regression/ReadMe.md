# 📊 Logistic Regression – Predicting Wheat Type

## 📝 Project Overview
This project builds a **Logistic Regression Model** to classify wheat types using the `WheatData.csv` dataset. The goal is to predict **whether a wheat sample belongs to "Kama," "Rosa," or "Canadian"** based on physical measurements.

### 📌 Dataset Overview
- **Total Observations:** 210  
- **Independent Variables:**
  - `A` → Area  
  - `P` → Perimeter  
  - `C` → Compactness  
  - `LK` → Length of kernel  
  - `WK` → Width of kernel  
  - `A_coef` → Asymmetry coefficient  
  - `LkG` → Length of kernel groove  

- **Dependent Variable (Target)**:  
  - `target`: 0 (Kama), 1 (Rosa), or 2 (Canadian)  

---

## 📊 Modeling Approach
### **1️⃣ Data Preprocessing**
✅ **Data Cleaning & Feature Selection**  
✅ **Feature Scaling** → Standardized numerical values  
✅ **Train-Test Split** → 80% training, 20% testing  

### **2️⃣ Logistic Regression Model**
✅ **Equation Representation:**  
   \[
   P(y) = \frac{1}{1 + e^{-(\beta_0 + \beta_1x_1 + \beta_2x_2 + ... + \beta_nx_n)}}
   \]
✅ **Model Evaluation Metrics:**
   - **Confusion Matrix & Classification Report**  
   - **Precision, Recall, and F1-Score**  
   - **ROC-AUC Curve**  

---

## **📊 Key Results**
- **Accuracy:** **87%**  
- **Best Features:** Area, Perimeter, and Kernel Length  
- **ROC-AUC Score:** **0.92**  

---

## **📂 Files Included**
📌 `wheat_logistic.ipynb` → Jupyter Notebook with model implementation.  
📌 `Logistic-Regression-Report.pdf` → Detailed report with results.  
📌 `Logistic-Regression-Presentation.pptx` → Summary of findings.  

---

## 🚀 **How to Run**
1. Clone the repository:
   ```sh
   git clone https://github.com/jayp881998/Statistical-Modelling-Best-Practices.git
