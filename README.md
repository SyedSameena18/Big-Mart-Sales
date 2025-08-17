# 🛒 Big Mart Sales Prediction

A Machine Learning project to predict the sales of Big Mart products based on various features like item type, weight, visibility, outlet size, etc.  
This project helps understand **data preprocessing, regression models, and evaluation metrics**.

## 📌 Project Workflow
1. Import Libraries 
2. Load Dataset  
3. Exploratory Data Analysis (EDA)  
   - Check dataset shape and info  
   - Handle missing values  
   - Visualize sales distribution  
4. Data Preprocessing  
   - Encoding categorical variables  
   - Feature scaling (if needed)  
5. Model Building  
   - Linear Regression  
   - Random Forest Regressor  
   - (Optional) XGBoost Regressor  
6. Model Evaluation  
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)  
7. Prediction on Test Data

## 📊 Dataset
- The dataset can be downloaded from [Kaggle – Big Mart Sales Dataset](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data).  
- It contains **8523 rows** and **12 features** including:  
  - Item_Weight  
  - Item_Fat_Content  
  - Item_Visibility  
  - Outlet_Size  
  - Outlet_Location_Type  
  - Item_Outlet_Sales -Target variable 

##  👾 Models Used
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

## 📈 Results
- Linear Regression: R² ≈ 0.50  
- Random Forest Regressor: R² ≈ 0.60–0.65  
- XGBoost : R² ≈ 0.65–0.70  

## ⚙️ Installation & Usage
Clone the repository:
```bash
git clone https://github.com/YourUsername/big-mart-sales-prediction.git
cd big-mart-sales-prediction
