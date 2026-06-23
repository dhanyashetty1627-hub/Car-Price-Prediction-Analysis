# Car-Price-Prediction-Analysis
# 🚗 Car Price Prediction with Machine Learning

## 📌 Project Overview

Car prices depend on various factors such as the brand, manufacturing year, fuel type, transmission type, kilometers driven, ownership history, and current market value. This project aims to build a machine learning model that can accurately predict the selling price of a used car based on these features.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

---

## 🎯 Objectives

* Analyze factors affecting used car prices.
* Perform data cleaning and preprocessing.
* Visualize relationships between car features and selling price.
* Build machine learning regression models.
* Compare model performance using evaluation metrics.
* Predict the selling price of a car based on input features.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains information about used cars, including:

| Feature       | Description                                |
| ------------- | ------------------------------------------ |
| Car_Name      | Name of the car                            |
| Year          | Manufacturing year                         |
| Selling_Price | Selling price of the car (Target Variable) |
| Present_Price | Current ex-showroom price                  |
| Driven_kms    | Distance driven in kilometers              |
| Fuel_Type     | Petrol, Diesel, or CNG                     |
| Selling_type  | Dealer or Individual                       |
| Transmission  | Manual or Automatic                        |
| Owner         | Number of previous owners                  |

---

## 🔄 Project Workflow

### 1. Data Collection

* Imported the car price dataset using Pandas.

### 2. Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Verified data types and dataset consistency.

### 3. Feature Engineering

* Created a new feature called **Car Age**.
* Removed unnecessary columns.
* Encoded categorical variables into numerical format.

### 4. Exploratory Data Analysis (EDA)

* Analyzed feature distributions.
* Examined relationships between variables.
* Identified important factors affecting car prices.

### 5. Data Visualization

The following visualizations were created:

* Selling Price Distribution
* Fuel Type Distribution
* Transmission Type Analysis
* Car Age vs Selling Price
* Present Price vs Selling Price
* Correlation Heatmap
* Actual vs Predicted Price Comparison

### 6. Model Building

Implemented and trained:

* Linear Regression
* Random Forest Regressor

### 7. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 📊 Results

* Successfully predicted car selling prices.
* Random Forest Regressor achieved better performance than Linear Regression.
* Present Price and Car Age were found to be significant factors influencing car prices.
* The model achieved high prediction accuracy with strong R² scores.

---

## 📈 Key Insights

* Older vehicles generally have lower selling prices.
* Cars with higher present prices tend to have higher resale values.
* Fuel type and transmission type influence market pricing.
* Vehicle ownership history impacts resale value.

---

## 📁 Repository Structure

```text
Car-Price-Prediction-With-Machine-Learning/
│
├── car_data.csv
├── Car_Price_Prediction.ipynb
├── README.md
└── Images/
```

## 🚀 How to Run

### Clone Repository

```bash
git clone <repository-link>
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebook

Open Jupyter Notebook and execute all cells sequentially.

---

## 🎓 Learning Outcomes

Through this project, the following concepts were practiced:

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Machine Learning Workflow

---

## 👩‍💻 Author

**Dhanya**

Third Year AI & Data Science Engineering Student

---

## ⭐ Project Status

Completed Internship Project – Car Price Prediction using Machine Learning.
