# Gold Rate Prediction Using Machine Learning

## Project Overview

Gold is one of the most valuable commodities in the global financial market. The price of gold changes frequently due to various economic factors such as inflation, currency exchange rates, stock market trends, and global economic conditions.

This project focuses on predicting gold prices using machine learning techniques. By analyzing historical financial data and identifying patterns, the model predicts future gold prices. These predictions can help investors, analysts, and researchers make better financial decisions.

---

## Objectives

- Analyze historical gold price data
- Identify important factors affecting gold prices
- Build a machine learning model to predict gold prices
- Evaluate the performance of the prediction model
- Understand relationships between financial indicators and gold prices

---

## Dataset Description

The dataset used in this project contains historical financial data related to gold prices and other economic indicators.

Important features in the dataset include:

- **Date** – The date of the recorded financial data
- **SPX** – Standard & Poor's 500 Index value
- **GLD** – Gold ETF price (Target Variable)
- **USO** – United States Oil Fund price
- **SLV** – Silver ETF price
- **EUR/USD** – Currency exchange rate between Euro and US Dollar

These features help the model understand how different economic indicators influence gold prices.

---

## Technologies Used

The following tools and technologies were used in this project:

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## Machine Learning Model

The machine learning model used in this project is:

- **Random Forest Regressor**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Project Workflow

### 1. Data Collection

The dataset containing historical gold price information is loaded.

### 2. Data Preprocessing

- Handling missing values
- Cleaning the dataset
- Preparing data for model training

### 3. Exploratory Data Analysis

Data visualization techniques are used to understand relationships between variables.

Examples include:

- Correlation heatmap
- Distribution plots
- Feature relationship analysis

### 4. Feature Selection

Important features influencing gold prices are selected for training the model.

### 5. Model Training

The dataset is divided into:

- **Training Dataset**
- **Testing Dataset**

The Random Forest Regressor model is trained using the training data.

### 6. Model Evaluation

The performance of the model is evaluated using accuracy metrics.

### 7. Prediction

The trained model predicts gold prices based on financial indicators.

---

## Project Structure

```
GoldRatePrediction
│
├── GoldRatePrediction.ipynb
├── dataset.csv
├── README.md
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/Poojita40/GoldRatePrediction.git
```

2. Open the notebook in **Google Colab** or **Jupyter Notebook**

3. Upload the dataset if required

4. Run all the cells in the notebook

5. The model will train and generate gold price predictions

---

## Results

The Random Forest Regression model predicts gold prices by learning patterns from historical financial data. The model demonstrates that machine learning techniques can be effectively used for financial forecasting.

---

## Conclusion

Gold price prediction is an important financial forecasting problem. Using machine learning, historical market data can be analyzed to generate useful predictions. This project demonstrates how predictive models can support better financial analysis and decision-making.

---

## Author

**Poojita Lakkakula**

GitHub: https://github.com/Poojita40
