# ✈️ Flight Price Detection

## 📌 About the Dataset

This project focuses on **predicting the price of airline tickets** based on various travel-related features.  
The dataset reflects real-world airline pricing strategies and helps analyze how factors like airline, route, duration, and stops impact ticket prices.

This dataset is well-suited for **regression-based machine learning tasks** and is a great resource for **feature engineering**, **EDA**, and **model evaluation**.

---

## 📊 Features

Below are the key features in the dataset:

- 🛫 `Airline` – Name of the airline (e.g., IndiGo, Air India)  
- 📅 `Date_of_Journey` – The date of the journey  
- 🌆 `Source` – City of departure  
- 🏙️ `Destination` – City of arrival  
- 🛣️ `Route` – Route taken by the flight  
- ⏰ `Dep_Time` – Departure time  
- ⏱️ `Arrival_Time` – Arrival time  
- ⌛ `Duration` – Total flight time  
- 🔁 `Total_Stops` – Number of stops in the journey  
- 🧾 `Additional_Info` – Miscellaneous information (e.g., No info, In-flight meal not included)  
- 💰 `Price` – **Target variable**: Flight ticket price (in INR)

---

## 🧠 Models Used

I implemented and compared multiple regression models to predict flight ticket prices:

- 📐 Linear Regression  
- 💠 Support Vector Regression (SVR)  
- 📍 K-Nearest Neighbors (KNN) Regressor  
- 🌲 Decision Tree Regressor 
- 🌳 **Random Forest Regressor** ✅

---

## 📈 Best Performance

The **Random Forest Regressor** achieved the highest accuracy and generalization ability, making it the most reliable model for this task.  
It handled non-linear relationships and feature interactions effectively without much tuning.

---

## 🚀 Project Goals

- ✈️ Understand the impact of flight features on ticket pricing  
- 🧪 Build and train multiple **regression models**  
- 📊 Perform **feature analysis**, **EDA**, and **data preprocessing**  
- 📈 Compare model performances and select the most accurate and robust model

---

This project demonstrates how machine learning can be used to understand complex pricing behavior in the airline industry and provides insights into key drivers of cost.  
Further improvements could include hyperparameter tuning, ensemble stacking, or deployment via a web app.
