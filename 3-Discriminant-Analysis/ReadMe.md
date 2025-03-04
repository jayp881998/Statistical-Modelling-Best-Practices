# 📊 Discriminant Analysis – LDA & QDA for Wheat Classification

## 📝 Project Overview
This project implements **Linear Discriminant Analysis (LDA) and Quadratic Discriminant Analysis (QDA)** on the `WheatData.csv` dataset. The objective is to classify wheat samples into three categories: **Kama, Rosa, and Canadian**.

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
✅ **SMOTE Applied** → Balances dataset before training models.  
✅ **Feature Scaling** → Standardized numerical values.  
✅ **Train-Test Split** → 80% training, 20% testing.  

### **2️⃣ Discriminant Analysis Models**
✅ **Linear Discriminant Analysis (LDA)** → Finds linear boundaries between classes.  
✅ **Quadratic Discriminant Analysis (QDA)** → Finds quadratic boundaries for classification.  

### **3️⃣ Model Evaluation**
✅ **Confusion Matrix & Classification Report** → Evaluates accuracy, precision, recall, F1-score.  
✅ **Comparison of LDA vs. QDA** → Identifies best-performing model.  

---

## **📊 Key Results**
- **LDA Accuracy:** **85%**  
- **QDA Accuracy:** **88%**  
- **Best Model:** **QDA performed slightly better due to non-linearity in data**.  

---

## **📂 Files Included**
📌 `wheat_LDA_QDA.ipynb` → Jupyter Notebook with LDA & QDA implementations.  
📌 `Discriminant-Analysis-Report.pdf` → Detailed report on methodology & results.  
📌 `Discriminant-Analysis-Presentation.pptx` → PowerPoint summary of findings.  

---

## 🚀 **How to Run**
1. Clone the repository:
   ```sh
   git clone https://github.com/jayp881998/Statistical-Modelling-Best-Practices.git
