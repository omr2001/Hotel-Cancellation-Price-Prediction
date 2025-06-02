# 🏨 Hotel Booking Cancellation & Price Prediction

## 📊 Project Overview

This project focuses on analyzing hotel booking data to understand customer behavior, identify cancellation patterns, and predict prices using machine learning techniques. The dataset includes reservation information for city and resort hotels. By cleaning the data, performing exploratory data analysis (EDA), and building predictive models, we derive actionable insights to improve booking strategies and revenue management.

---

## 🚀 Objectives

- 📌 Identify factors leading to hotel booking cancellations.
- 💰 Predict booking prices (ADR - Average Daily Rate) based on reservation details.
- 🧠 Build classification and regression models using machine learning.
- 📊 Create clear and impactful visualizations to support business decisions.

---

## 🧰 Tools & Technologies

- **Languages & Libraries**: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Folium
- **Techniques**: Feature Engineering, EDA, Data Preprocessing, ML Modeling
- **Models Used**: Random Forest, Decision Tree, Logistic Regression, Naive Bayes, K-Nearest Neighbors

---

## 📁 Dataset

The dataset is sourced from a public repository of hotel booking data and includes the following features:
- Hotel type (City or Resort)
- Booking dates
- Number of guests
- Special requests
- Lead time
- Previous cancellations
- Customer segmentation
- Pricing (ADR)

---

## 🔍 Exploratory Data Analysis (EDA)

- Removed null values and invalid entries (e.g., bookings with zero guests)
- Performed geospatial analysis using **Folium** and **Choropleth maps**
- Separated city and resort hotels for deeper comparative insights
- Visualized seasonal pricing trends, cancellation rates, and customer behavior

---

## 🛠 Feature Engineering

- Encoded categorical variables (One-Hot, Label Encoding)
- Extracted date-based features: arrival month, day, year
- Created new features like total guests and lead time bins
- Removed outliers based on domain knowledge and visualization (boxplots, violin plots)

---

## 🤖 Model Building

### 🔹 Cancellation Prediction (Classification)
- Target: `is_canceled`
- Models: Logistic Regression, Random Forest, Decision Tree, KNN, Naive Bayes
- **Best Accuracy**: 0.95 using **Random Forest**
---

## 📈 Key Insights

- Cancellations were highly correlated with longer lead times and absence of deposit.
- City hotels had more cancellations but higher occupancy during weekdays.
- Resort hotels showed seasonal peaks with higher ADR during summer.
- Previous cancellations and special requests were significant features in predicting cancellation likelihood.

---

## 🧠 Business Value

- Helps hotels **minimize revenue loss** by identifying risky bookings early.
- Enhances **pricing strategy** using machine learning for dynamic ADR prediction.
- Supports marketing teams to **target high-conversion segments** based on patterns in cancellations and stays.
