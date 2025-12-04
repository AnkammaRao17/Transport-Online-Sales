
---

## 📊 **Project Overview**

The objective of this project is to:

- Clean and preprocess vehicle registration data  
- Convert date columns into usable numerical features  
- Analyze missing values  
- Build and evaluate multiple ML models:  
  - **Linear Regression** → Predict *Seat Capacity*  
  - **Logistic Regression** → Classify *Category*  
  - **Decision Tree Classifier** → Classify *Category*  
- Perform visual exploratory data analysis using Matplotlib & Seaborn  
- Compare model performances  

---

## 🧹 **Data Preprocessing**

Steps performed:

1. **Convert date columns**:  
   - `makeYear`, `fromdate`, `todate`
2. **Extract numerical features**:
   - Vehicle manufacturing year (`makeYear_num`)
   - Registration duration (`reg_duration_days`)
3. **Handle missing values** using:
   - Median imputation for numerical variables  
   - Most frequent imputation for categorical variables  
4. **OneHotEncoding** for categorical features  
5. **Standard Scaling** for numerical features  

---

## 🧪 **Machine Learning Models Used**

### ✔ **1. Linear Regression**
Predicts: **Seat Capacity**

**Metrics:**
- MAE  
- MSE  
- RMSE  
- R² Score  

---

### ✔ **2. Logistic Regression**
Predicts: **Category** (Classification)

**Metrics:**
- Accuracy  
- Classification Report  
- Confusion Matrix  

---

### ✔ **3. Decision Tree Classifier**

**Metrics:**
- Accuracy  
- Classification Report  
- Confusion Matrix  

---

## 📈 **Visualizations Included**

The project automatically generates:

- Histogram → *Seat Capacity distribution*  
- Bar chart → *Fuel type counts*  
- Boxplot → *Seat capacity spread*  
- Scatter plot → *Make year vs seat capacity*  

---

## 🧾 **Model Summary**

At the end, a summary table compares:
- Linear Regression (MAE, MSE, RMSE, R²)
- Logistic Regression (Accuracy)
- Decision Tree (Accuracy)

---

## ▶ **How to Run the Project**

### **1. Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
