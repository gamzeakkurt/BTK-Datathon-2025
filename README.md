# BTK-Datathon-2025 ROC Stars Solution

# Predicting Session Value in E-Commerce 🛒

### Problem Definition

On an e-commerce platform, each user session can include multiple actions—viewing products, adding or removing items from the cart, and completing purchases. Estimating the **monetary value of each session** (`session_value`) is critical for:

* Understanding which sessions are most profitable
* Prioritizing high-value customers
* Detecting anomalies (e.g., unusually high or zero-value sessions)
* Optimizing business strategies like remarketing and personalized offers

However, predicting session value is challenging because:

* Many sessions include only product views without purchases
* Event sequences can be inconsistent (e.g., a purchase without adding items to the cart)
* User behavior varies widely—from one-time visitors to loyal repeat customers

### Project Objective

The goal of this project is to **predict the session value for each user session** using behavioral and event-based features. Our approach includes:

* Conducting **Exploratory Data Analysis (EDA)** to understand user, session, and product-level activity
* **Detecting anomalies** such as unusual sessions, order inconsistencies, or suspicious behavior
* **Feature engineering** from session sequences to capture meaningful patterns
* Training **machine learning models** (CatBoost and AutoGluon) to predict session value

This notebook combines **data exploration, anomaly detection, feature engineering, and machine learning modeling** to generate actionable insights for session-level revenue prediction.



If you want, I can also make an **even more concise, punchy version** specifically for GitHub’s "About" section so it reads well in a few sentences. Do you want me to do that?
