# Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning

# Bluebook Bulldozer Price Regression 📉🚜

## 📌 Project Overview
This project is an **end-to-end machine learning model** for predicting the **sale price of bulldozers** using structured data. It is based on the **Bluebook for Bulldozers Kaggle dataset**, where we build and evaluate regression models to estimate bulldozer prices based on various features such as machine usage, age, and equipment type.

## 🚀 Key Features
- **Data Preprocessing & Feature Engineering**
  - Handling missing values and categorical data
  - Extracting useful features from timestamps
  - Exploratory Data Analysis (EDA) with visualizations
- **Model Development & Training**
  - Implementing various regression models (Linear Regression, Random Forest, XGBoost)
  - Hyperparameter tuning using GridSearchCV
- **Model Evaluation & Performance Metrics**
  - Root Mean Squared Log Error (RMSLE)
  - Cross-validation for robust performance
- **Deployment Readiness**
  - Saving and loading models with `joblib`
  - Making price predictions for unseen bulldozers

## 📂 Dataset
The dataset comes from Kaggle’s **Bluebook for Bulldozers** competition.
- **Training set:** Bulldozer sales data from **1989–2011**
- **Validation set:** Sales data from **2012**
- **Test set:** Bulldozers sold in **2013** (price to be predicted)

📌 [Dataset Link](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data)

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - Pandas, NumPy (Data Processing)
  - Matplotlib, Seaborn (Visualization)
  - Scikit-Learn (Modeling & Evaluation)
  - XGBoost (Boosting Algorithm)
  - Joblib (Model Saving & Loading)

## 📜 How to Run
1. Clone the repository:
   ```bash
      git clone https://github.com/ShamScripts/Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning.git
      cd Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning
   ```
2. Install dependencies:
   ```bash
      pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
       jupyter notebook end-to-end-bluebook-bulldozer-price-regression.ipynb
   ```

## 📊 Results & Insights
- **Feature Importance Analysis** helped identify key predictors for price estimation.
- **XGBoost** provided the best performance with **lowest RMSLE**.
- **Tuned hyperparameters** improved prediction accuracy significantly.

## 📬 Connect with Me
If you're interested in ML, data science, or want to collaborate, feel free to reach out!
- **GitHub:** [ShamScripts](https://github.com/ShamScripts)
- **LinkedIn:** [Shambhavi Jha](https://www.linkedin.com/in/shambhavi-jha)
- **Email:** f20230009@dubai.bits-pilani.ac.in

🔍 *Let's make data-driven decisions smarter!* 🚀

