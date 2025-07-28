# CodeAlpha_Sales_Prediction_using_Python

# 📊 Sales Prediction using Python
This project demonstrates how to forecast product sales based on advertising spend using Python. It involves data preprocessing, exploratory data analysis, linear regression modeling, and performance evaluation — all aimed at understanding how marketing investments impact sales outcomes.

# Overview
Sales prediction is essential for marketing and financial planning. This project leverages a classic advertising dataset to forecast sales based on spending across various media channels: TV, Radio, and Newspaper.

# Objective
- Predict future sales based on advertising spend across TV, Radio, and Newspaper.
- Clean and prepare the dataset for model training.
- Visualize relationships between features and target variable.
- Build a **Linear Regression** model to forecast sales.
- Evaluate the model using performance metrics and residual analysis.
- Deliver actionable insights to optimize marketing strategy.

# Dataset
- **Source**: [Kaggle - Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Features**:
  - `TV` – Advertising spend on TV
  - `Radio` – Advertising spend on Radio
  - `Newspaper` – Advertising spend on Newspapers
- **Target**: `Sales` – Product sales influenced by the above spend

# Libraries Used
- pandas  
- numpy  
- seaborn  
- matplotlib  
- scikit-learn  

# Project Workflow
1. **Data Loading**
   - Loaded advertising dataset via KaggleHub.
2. **Data Preprocessing**
   - Filled missing values using column means.
   - Separated features (`TV`, `Radio`, `Newspaper`) and target (`Sales`).
3. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap and pairplots.
   - Distribution and scatterplots for spend vs sales.
4. **Modeling**
   - Trained a **Linear Regression** model.
   - Used train-test split to validate performance.
5. **Evaluation**
   - Metrics used:
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
     - R² Score
   - Residual plots and prediction comparison visuals.
6. **Insights**
   - Radio spend had the highest impact on sales.
   - Newspaper spend contributed the least to sales.
   - Recommendation: Focus more on impactful channels like Radio and TV.

# How to Run the Project
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook: `CodeAlpha_Task4_Sales_Prediction_Project.ipynb`
3. Ensure access to the dataset (auto-downloaded via KaggleHub)
4. Go to **Runtime > Run all**
5. View analysis, plots, and model predictions

# Real-World Applications
- Marketing strategy optimization  
- Budget allocation for ad channels  
- Data-driven ROI planning for campaigns  
- Performance monitoring of media spend  

# Author
**K.R.Sanjaysaravanan**  
CodeAlpha Intern

⭐ If this project helped you understand sales forecasting with Python, give it a star!

