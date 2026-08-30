# Car Dekho Data Analysis

A minor project developed as part of the VOIS DIY program, focused on exploring and analyzing used-car data from Car Dekho.

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Car Dekho dataset to understand the factors and patterns associated with used-car selling prices.

The analysis focuses on factors such as:

- Car Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Transmission
- Seller Type
- Owner

## 🧹 Data Preprocessing

The dataset was prepared before analysis by:

- Checking for missing/null values
- Checking duplicate records
- Identifying outliers
- Handling outliers using the IQR method
- Preparing the cleaned dataset for analysis

## 📊 Exploratory Data Analysis

The project analyzes the following relationships:

1. **Year vs Selling Price**
2. **Kms Driven vs Selling Price**
3. **Present Price vs Selling Price**
4. **Fuel Type vs Selling Price**
5. **Transmission vs Selling Price**

These analyses help identify trends and relationships in used-car pricing.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## 📁 Project Structure

```text
Car-Dekho-Data-Analysis/
│
├── Car_Dekho_Analysis.ipynb
├── car_data.csv
└── README.md
