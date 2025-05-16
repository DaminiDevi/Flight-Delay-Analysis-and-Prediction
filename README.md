# ✈️ Flight Delay Analysis & Prediction

**Author:** Mayanglambam Damini Devi  
**Institution:** The Assam Kaziranga University  
**Year:** 3rd Year B.Tech CSE (Data Science)  
**Passionate about:** Learning new tools, building data-driven solutions, and continuous exploration in AI & ML.

---

## 📌 Project Overview

This project focuses on **analyzing** and **predicting** flight delays using real-world U.S. domestic flight data. With millions of flight records, the goal is to understand the key reasons behind delays and cancellations, and to build a **predictive model** that can forecast whether a flight will be significantly delayed.

---

## 🔍 Objectives

- Perform **EDA (Exploratory Data Analysis)** on flight delay data.
- Identify **patterns, trends, and causes** of flight delays and cancellations.
- Apply **feature engineering** to extract meaningful variables.
- Build a **classification model** to predict significant flight delays.

---

## 📁 Dataset

Dataset used: `DelayedFlights.csv`  
Contains detailed information about flights in the U.S., including:

- Flight schedule & time info
- Airline & airport codes
- Delay types: Carrier, Weather, NAS, etc.
- Cancellations and reasons
- Distances, arrival, and departure delays

---

## 📊 Key Analysis Performed

- Most delayed airlines and airports
- Delay distribution by month, day, and hour
- Cancellation trends and reasons
- Top routes with delays
- Delay type comparisons (weather, carrier, NAS)
- Day-of-week and weekend vs weekday analysis

---

## ⚙️ Feature Engineering

- `FL_DATE`: Constructed from Year, Month, Day
- `DepHour`: Extracted from scheduled departure time
- `FlightDuration`: Estimated from scheduled times
- `Is_Weekend`: Indicates Saturday or Sunday
- `Quarter`: Based on month
- `SignificantDelay`: Target variable (delay > 15 minutes)

---

## 🧠 Model Building

- **Model Used**: Logistic Regression
- **Libraries**: `scikit-learn`, `pandas`, `matplotlib`, `seaborn`
- **Process**:
  - Data cleaning and transformation
  - Train-test split
  - Feature scaling
  - Model training and evaluation

---

## 📈 Results

- Achieved ~70% accuracy in predicting significant delays
- Confusion matrix and classification report used for performance analysis
- Found key influence from: `DepHour`, `Distance`, `FlightDuration`

---

## 🛠 Tech Stack

- **Python 3.13**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualizations
- **Scikit-learn** – ML modeling and metrics
- **Jupyter Notebook** – Interactive development

---

## 📌 Project Highlights

- ✅ Cleaned and transformed a large, real-world dataset
- ✅ Performed in-depth EDA and data visualization
- ✅ Engineered multiple useful features
- ✅ Built and evaluated a classification model
- ✅ Extracted actionable insights from airline operations data

---

## 💡 About Me

Hi! I'm **Mayanglambam Damini Devi**, a third-year student at **The Assam Kaziranga University**, majoring in **Data Science**.  
I'm deeply passionate about exploring new tools, learning emerging technologies, and applying data to solve real-world problems.


