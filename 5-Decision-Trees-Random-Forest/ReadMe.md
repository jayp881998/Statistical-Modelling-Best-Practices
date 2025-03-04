# 📊 Decision Trees & Random Forest – Wheat Classification

## 📝 Project Overview
This project applies **Decision Tree and Random Forest Classification Models** on the `WheatData.csv` dataset. The objective is to classify wheat samples into three categories: **Kama, Rosa, and Canadian**.

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
✅ **Feature Scaling** → Standardized numerical values.  
✅ **Train-Test Split** → 80% training, 20% testing.  

### **2️⃣ Classification Models**
✅ **Decision Tree Classifier** → Builds a tree-based model using Gini/Entropy criteria.  
✅ **Random Forest Classifier** → Uses multiple trees for robust classification.  

### **3️⃣ Model Evaluation**
✅ **Confusion Matrix & Classification Report** → Evaluates accuracy, precision, recall, F1-score.  
✅ **Feature Importance Analysis** → Identifies the most significant predictors.  
✅ **Comparison of Decision Tree vs. Random Forest** → Determines the best-performing model.  

---

## **📊 Key Results**
- **Decision Tree Accuracy:** **82%**  
- **Random Forest Accuracy:** **90%**  
- **Best Model:** **Random Forest performed better due to its ability to reduce overfitting.**  

---

## **📂 Files Included**
📌 `wheat_decision_trees.ipynb` → Jupyter Notebook with Decision Tree & Random Forest implementations.  
📌 `Decision-Trees-Report.pdf` → Detailed methodology and results.  
📌 `Decision-Trees-Presentation.pptx` → PowerPoint summary of findings.  

---

## 🚀 **How to Run**
1. Clone the repository:
   ```sh
   git clone https://github.com/jayp881998/Statistical-Modelling-Best-Practices.git
