# 🛒 Predicting Banana Reorders with Instacart Data

This project uses the [Instacart Market Basket Analysis dataset](https://www.instacart.com/datasets/grocery-shopping-2017) to predict whether a customer's order will include a **banana**, the most commonly ordered product on the platform.

## 📊 Objectives

- Wrangle and join multiple relational datasets
- Engineer meaningful features for classification
- Apply machine learning to a real-world retail dataset
- Practice binary classification using a Random Forest model

## 🧰 Tools & Libraries

- Python
- pandas, NumPy, matplotlib
- scikit-learn (`RandomForestClassifier`, `train_test_split`)
- Google Colab + Google Drive integration

## 🧹 Data Cleaning & Wrangling

- Loaded and joined `orders`, `products`, `order_products__prior`, and `order_products__train`
- Merged prior purchases with customer metadata to create a complete training dataset
- Target: whether or not an order included **bananas**
- Created features like:
  - Time of day of the order
  - Number of items per order
  - Previous banana purchases by the customer
  - Morning vs. afternoon orders

## ⚙️ Modeling

- Built a Random Forest model to classify banana orders
- Training accuracy: **~86.8%**
- Validation accuracy: **~84.5%**
- Established baseline accuracy at ~85.7% based on class distribution

## 📁 Project Structure


