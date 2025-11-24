
# Big Mart Sales Prediction using Machine Learning  

This project aims to predict the sales of products at different Big Mart outlets using machine learning techniques.  
The goal is to build a regression model that can accurately forecast Item_Outlet_Sales based on product features and store characteristics.

---

## 📌 Project Objective
- Predict **Item Outlet Sales** using ML models  
- Understand which product/store features influence sales  
- Build a reliable model for business decision-making  

---

## 📂 Dataset Description
The dataset contains various product and outlet details such as:

### **Product Features**
- Item_Identifier  
- Item_Weight  
- Item_Fat_Content  
- Item_Visibility  
- Item_Type  
- Item_MRP  

### **Outlet Features**
- Outlet_Identifier  
- Outlet_Size  
- Outlet_Location_Type  
- Outlet_Type  
- Outlet_Establishment_Year  

### **Target Column**
- **Item_Outlet_Sales** (Only in train dataset)

---

## 🧹 Data Preprocessing Steps
- Handling missing values  
- Correcting inconsistent categories  
- Encoding categorical columns (Label Encoding / OneHotEncoding)  
- Scaling numerical features (optional)  
- Splitting dataset into **training** and **validation** sets  

---

## 📊 Exploratory Data Analysis (EDA)
- Distribution of numerical features  
- Count plots for categorical features  
- Correlation matrix  
- Outlier detection  
- Item MRP vs Sales relationship  

---

## 🤖 Machine Learning Models Used
- Linear Regression  
- Lasso / Ridge  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor (optional)

**Evaluation Metric:**  
- R² Score  
- RMSE / MAE  

---

## 📈 Final Model Selection
The model with the best validation performance (R² score) is chosen for predicting sales on the test dataset.

---

## 🧪 Final Prediction (Test Dataset)
- Load test.csv  
- Apply same preprocessing steps  
- Use trained model to generate predictions  
- Save output as `FinalPrediction.csv`

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  

---

## 📦 Project Structure

