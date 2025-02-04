# eCommerce-Product-Recommendation
This repository contains an eCommerce Product Recommendation system that predicts whether a customer will reorder a product or not. The model is trained using The Instacart Online Grocery Shopping Dataset (2017), which includes customer purchase behavior across multiple orders.

📌 Project Overview
In online grocery shopping, predicting customer reorders is crucial for:
1.Enhancing user experience with personalized recommendations
2.Improving inventory management
3.Increasing customer retention and sales
This project leverages machine learning techniques to predict whether a user will reorder a product in their next purchase based on their past behavior.
📂 Dataset
The dataset used is the Instacart Online Grocery Shopping Dataset (2017), which contains:
1.82K+ grocery orders
2.5K+ customers
3.49K+ unique products
Metadata on purchase history, order sequences, and user behavior
⚙️ Features Used
The model utilizes the following features to make predictions:
1.User behavior: Number of previous orders, reorder ratio, days since prior order
2.Product attributes: Popularity, department, aisle category
3.Order history: Add-to-cart order, purchase frequency, time of order
🚀 Model Performance
ROC AUC : 79.1946%
