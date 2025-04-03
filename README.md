# 🏡 House Price Prediction using Boston Dataset

## 📌 Project Overview
This project is a **Machine Learning model** that predicts house prices using the **Boston Housing Dataset**. The dataset consists of various features such as crime rate, number of rooms, tax rate, and other socio-economic factors that influence housing prices.

We use **XGBoost Regressor** to build a predictive model and evaluate its performance using **R-squared error** and **Mean Absolute Error (MAE)**.

---

## 📂 Dataset Information
The **Boston Housing Dataset** contains **506 rows** and **14 features**, including:
- `CRIM` - Crime rate per capita
- `ZN` - Proportion of residential land zoned for large lots
- `INDUS` - Proportion of non-retail business acres
- `CHAS` - Charles River dummy variable (1 if adjacent, 0 otherwise)
- `NOX` - Nitrogen oxide concentration
- `RM` - Average number of rooms per dwelling
- `AGE` - Proportion of owner-occupied units built before 1940
- `DIS` - Weighted distance to employment centers
- `RAD` - Accessibility to radial highways
- `TAX` - Property tax rate
- `PTRATIO` - Pupil-teacher ratio
- `B` - Proportion of Black population
- `LSTAT` - Percentage of lower-income population
- `PRICE` - **Target variable (House Price in $1000s)**

---

## 🛠 Tech Stack
- **Python** 🐍
- **Pandas** (Data Preprocessing)
- **NumPy** (Mathematical Computations)
- **Matplotlib & Seaborn** (Data Visualization)
- **Scikit-learn** (Machine Learning)
- **XGBoost** (Model Training)

---

## 🔥 Model Implementation
### **1️⃣ Data Preprocessing**
- Handle missing values (if any)
- Standardize numerical features using **StandardScaler**
- Split the dataset into **80% training** and **20% testing** using `train_test_split`

### **2️⃣ Model Training**
We use the **XGBoost Regressor**, a powerful gradient boosting algorithm, to train the model.

---

##  📊 Results
🔹 Training Data  
✅ R-Squared Error: 0.999998  
✅ Mean Absolute Error: 0.0091  

🔹 Testing Data  
✅ R-Squared Error: 0.905  
✅ Mean Absolute Error: 2.07   
