# 📞 Bank Telemarketing Prediction using Machine Learning

## 🔍 Project Overview  
This project predicts whether a customer will subscribe to a term deposit after a telemarketing campaign. Using machine learning techniques, we analyze customer demographics, past interactions, and campaign-related factors to enhance prediction accuracy.  

## 📌 Problem Statement  
The objective is to develop a predictive model that classifies customer responses (Yes/No) based on various attributes.  

### **Dataset Features:**  
- **Independent Variables:** Customer demographics, previous interactions, campaign details, and economic indicators.  
- **Target Variable:** Whether the customer subscribed to the term deposit (`yes` or `no`).  

## 🛠️ Tools & Technologies Used  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Imbalanced-learn  
- **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest  

## 🔄 Project Workflow  
### **1. Data Preprocessing & Feature Engineering**  
✅ Loaded the dataset and checked for missing values.  
✅ Encoded categorical features using **LabelEncoder** and **One-Hot Encoding**.  
✅ Handled class imbalance using **SMOTE** to ensure fair model training.  

### **2. Exploratory Data Analysis (EDA)**  
✅ Visualized feature distributions and correlations using **seaborn** and **matplotlib**.  
✅ Identified key trends affecting customer subscription decisions.  

### **3. Model Training & Evaluation**  
✅ Split the dataset into training and testing sets.  
✅ Trained multiple classification models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest   
✅ Evaluated models using **accuracy, precision, recall, F1-score, confusion matrix**.  
✅ Achieved the best performance with **Random Forest** after hyperparameter tuning.  

### **📊 Final Model Performance**  
✅ **Accuracy:** **95%**  
✅ **F1-score:** **95%**  

## 📈 Conclusion  
✅ **Key Features:** Customer demographics and previous campaign interactions had a major impact on predictions.  
✅ **Best Model:** **Random Forest** achieved the highest accuracy and balanced precision-recall.  
✅ **SMOTE Impact:** Improved model performance by addressing class imbalance.
