# 🚗 Car Price Prediction using Machine Learning

A machine learning project that predicts the selling price of used cars based on various features such as car age, present price, kilometers driven, fuel type, seller type, transmission, and ownership history. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and prediction.

---

## 📌 Project Overview

Predicting the resale value of a used car is an important problem in the automobile industry. This project uses machine learning algorithms to estimate a car's selling price based on its characteristics.

The project includes data cleaning, visualization, feature engineering, model training, performance evaluation, and business insights to help buyers, sellers, and dealerships make informed pricing decisions.

---

## 🎯 Objectives

- Clean and preprocess the car dataset.
- Perform exploratory data analysis (EDA).
- Engineer useful features for prediction.
- Encode categorical variables.
- Train regression models to predict car prices.
- Compare model performance.
- Evaluate models using regression metrics.
- Identify the most important factors affecting car prices.

---

## 📂 Dataset

**Dataset Name:** `car data.csv`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Project Workflow

### 1. Data Collection

- Loaded the dataset using Pandas.

### 2. Data Cleaning

- Checked missing values
- Removed duplicate records
- Verified data types
- Removed unnecessary columns
- Renamed columns where necessary

### 3. Feature Engineering

- Created a new feature:
  - **Car_Age = Current Year − Manufacturing Year**
- Removed the original **Year** column after feature creation.

### 4. Data Preprocessing

- Encoded categorical variables using Label Encoding.
- Selected relevant features for prediction.

### 5. Exploratory Data Analysis (EDA)

Performed:

- Summary statistics
- Correlation analysis
- Price distribution analysis
- Relationship between present price and selling price
- Car age analysis
- Fuel type comparison
- Transmission analysis

### 6. Data Visualization

Visualizations included:

- Correlation Heatmap
- Histogram
- Scatter Plot
- Box Plot
- Feature Importance Plot
- Actual vs Predicted Price Plot

### 7. Model Building

Implemented the following regression models:

- Linear Regression
- Random Forest Regressor

### 8. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📊 Results

The Random Forest Regressor outperformed the Linear Regression model by achieving a higher R² Score and lower prediction error, making it the preferred model for predicting used car prices.

---

## 📈 Key Insights

- Present Price is the most influential feature affecting the selling price.
- Older vehicles generally have lower resale values.
- Cars with fewer kilometers driven tend to have higher resale prices.
- Fuel type significantly influences resale value.
- Manual and automatic transmission vehicles show different pricing trends.
- Random Forest captured the complex relationships in the data more effectively than Linear Regression.

---

## 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/Car-Price-Prediction.git
```

### Navigate to the project directory

```bash
cd Car-Price-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **Car_Price_Prediction.ipynb** and run all cells.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 👩‍💻 Author

**Dharshini R**

**B.Tech – Artificial Intelligence and Data Science**

---
