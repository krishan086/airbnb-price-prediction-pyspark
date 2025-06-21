# 🏠 Airbnb Price Prediction using PySpark MLlib

This project demonstrates how to build a **machine learning pipeline** using **Apache Spark (PySpark)** for predicting Airbnb listing prices based on features like room type, location, number of reviews, and more. It is a beginner-friendly end-to-end ML project built in **Google Colab**, ideal for Data Engineering learners exploring **Big Data** and **distributed ML**.

---

## 📌 Project Overview

- **Goal**: Predict the price of Airbnb listings using a regression model.
- **Tech stack**: PySpark, Spark MLlib, Google Colab
- **Type**: Supervised Machine Learning (Regression)

---

## 🗃️ Dataset Description

The dataset used is an Airbnb listings dataset containing features like:

| Column Name              | Description                        |
|--------------------------|------------------------------------|
| `neighbourhood_cleansed`| Location of the property           |
| `room_type`              | Type of room (Entire, Private etc)|
| `price`                  | Price per night                    |
| `bedrooms`               | Number of bedrooms                 |
| `bathrooms`              | Number of bathrooms                |
| `number_of_reviews`     | Count of reviews                   |

> 📁 Files:
> - `airbnb_price_prediction.ipynb`: Jupyter notebook with all code
> - `airbnb_data.csv`: Raw dataset

---

## ⚙️ Tech Stack

- 🐍 Python (Colab)
- 🔥 PySpark (`SparkSession`, `DataFrame`, `MLlib`)
- 🧪 MLlib for:
  - Feature engineering (`VectorAssembler`, `StringIndexer`)
  - Regression (`LinearRegression`)
  - Pipeline construction

---

## 🛠️ Project Structure
📦airbnb-price-prediction/
┣ 📄 airbnb_price_prediction.ipynb
┣ 📄 airbnb_data.csv
┗ 📄 README.md
