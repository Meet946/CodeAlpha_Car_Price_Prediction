# Car Price Prediction with Machine Learning

This project uses Machine Learning techniques to predict car selling prices based on various car-related features such as present price, fuel type, transmission type, kilometers driven, and ownership details.

The project demonstrates real-world applications of regression algorithms in price prediction systems.

---

## Project Objective

The main objectives of this project are:

- Analyze car-related data
- Perform data preprocessing and feature engineering
- Train machine learning regression models
- Predict car prices accurately
- Compare different regression algorithms
- Evaluate model performance using regression metrics

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Information

The dataset contains the following features:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner

---

## Machine Learning Models Used

### 1. Linear Regression
Used as a baseline regression model for price prediction.

### 2. Decision Tree Regressor
Used to capture non-linear relationships between car features and selling prices.

The Decision Tree Regressor achieved better prediction performance compared to Linear Regression.

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas

### 2. Data Cleaning
- Checked for missing values
- Removed unnecessary columns
- Created new features

### 3. Feature Engineering
- Created `Car_Age` feature from manufacturing year
- Removed `Car_Name` column
- Encoded categorical variables

### 4. Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature relationship visualization
- Price distribution analysis

### 5. Model Training
- Split dataset into training and testing sets
- Trained Linear Regression model
- Trained Decision Tree Regressor model

### 6. Model Evaluation
Models were evaluated using:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score

---

## Model Performance

| Model | R² Score |
|---|---|
| Linear Regression | Good Performance |
| Decision Tree Regressor | ~0.94 |

The Decision Tree Regressor provided higher prediction accuracy and better handled non-linear relationships in the dataset.

---

## Key Insights

- Present price strongly affects selling price
- Older cars generally have lower resale value
- Higher driven kilometers reduce car value
- Decision Tree Regressor performed better for this dataset

---
