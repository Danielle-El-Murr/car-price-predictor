# 🚗 Car Price Prediction using Linear Regression  

## 📌 Overview  
This project is all about predicting car prices based on different factors like the **car's brand, mileage, year, engine size, and fuel type**. The goal is to build a model that can estimate car prices accurately using **Linear Regression**.  

I worked on this project while going through a **Udemy machine learning course**, but I didn’t just follow along—I made sure to **understand every step, tweak things, and test different ideas**. I focused on **data preprocessing, feature selection, and checking OLS assumptions** to make sure the model performs well.  

This project helped me **strengthen my understanding of regression models**, feature engineering, and how to **evaluate model performance beyond just accuracy**.  

---

## 📊 Dataset  
- **Source**: cars.csv 
- **Number of records:** 4345  
- **Features Used:**  
  - **Numerical:** Year, Mileage, Engine Size, Price  
  - **Categorical:** Brand, Body, Engine Type, Registration, and Model
- **Goal:** Train a model to predict car prices based on available features.  

---

## 🛠 Tech Stack  
- **Python** 🐍  
- **Pandas, NumPy** (for data cleaning & manipulation)  
- **Matplotlib, Seaborn** (for visualizing trends)  
- **Scikit-Learn** (for building and evaluating the model)  

---

## 🚀 The Journey (Steps I Took)  
1️⃣ **Understanding the Problem** – I started by defining the goal: **Can I predict car prices based on specific features?** I looked at what factors typically affect car prices and made sure the dataset had those.  

2️⃣ **Preprocessing the Data** – Real-world data is never perfect, so I:  
   - Handled **missing values** by imputing them where needed.  
   - Removed **outliers** (e.g., cars priced way too low or high compared to similar ones).  
   - Scaled **numerical features** to make sure no feature dominated the regression.  

3️⃣ **Checking OLS Assumptions** – Since I was using **Linear Regression**, I needed to make sure the dataset met key assumptions:  
   - **Linearity** – Checked if the relationship between price and features was linear.  
   - **Homoscedasticity** – Made sure the variance of residuals was consistent.  
   - **Multicollinearity** – Checked if any independent variables were highly correlated and might mess with the model.  

4️⃣ **Handling Categorical Data** – Since ML models can’t process text, I converted categorical features like **Brand, Engine Type, and Body** into **dummy variables**.  

5️⃣ **Building & Evaluating the Model** – Finally, I trained a **Linear Regression model** using Scikit-Learn and evaluated it using:  
   - **R² Score** – Measures how well the model explains variance in price.  
   - **Residual Analysis** – Checked how well the model fits by analyzing the prediction errors.  

---

Overall, the model performed **decently well**, but there were some challenges:  
✅ It worked well for **popular brands, expensive cars and newer cars**.  
⚠️ It struggled with **cheaper cars and outliers**.  

---

## 🔮 Future Improvements (What I Want to Try Next)  
While the Linear Regression model worked okay, I want to:  
- **Test different models** like **Polynomial Regression, Decision Trees, and Random Forests** to compare results.  
- **Tune hyperparameters** to see if I can improve predictions.  
- **Add more features** like car model, damage, location, or previous owners to improve predictions. 

---

## 🏗 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
