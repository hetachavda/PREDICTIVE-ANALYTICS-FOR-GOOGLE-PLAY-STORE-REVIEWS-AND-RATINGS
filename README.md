# 📱 Google Play Store App Predictions  

A **machine learning and predictive analytics project** analyzing the **Google Play Store dataset** to uncover factors influencing app ratings, user sentiment, and future app market trends.  

This project demonstrates **EDA, supervised & unsupervised learning, sentiment analysis, and time-series forecasting** to provide **business insights** for developers and investors.  

---

## 📌 Project Overview  
With millions of apps on the **Google Play Store**, competition is fierce. Success depends on **ratings, reviews, installs, and pricing strategies**.  

### Objectives  
- 🔹 Predict **app ratings**  
- 🔹 Analyze **user sentiments in reviews**  
- 🔹 Compare **Free vs Paid apps**  
- 🔹 Identify **key features influencing success**  
- 🔹 Forecast **future app trends** using time series  

---

## 📂 Datasets Used  
- **Google Play Store Apps Dataset**  
- **Google Play Store User Reviews Dataset**  
- Source: *Kaggle*  

### Preprocessing Steps  
- Handling missing values  
- Encoding categorical variables  
- Converting numerical columns  
- Merging datasets  

---

## 🔍 Exploratory Data Analysis (EDA)  

- **Correlation Heatmap:**  
  - Price ↔ Type → 0.78 (Strong)  
  - Genres ↔ Category → 0.70 (Strong)  
  - Rating → Weak correlation with individual features  

- **Sentiment Distribution (Reviews):**  
  - ✅ Positive reviews dominate  
  - ❌ Negative reviews > Neutral reviews (angry users speak louder!)  

---

## 🤖 Machine Learning Models  

### 1. **Classification – Sentiment Analysis**  
- **Model:** Random Forest Classifier  
- **Goal:** Predict whether an app review is *positive, neutral, or negative*  

### 2. **Clustering – App Rating Distribution**  
- **Model:** K-Means  
- **Goal:** Group apps into clusters (low, medium, high ratings)  
- **Insight:** Most apps rated **4.0 – 4.7**, very few below 3.0  

### 3. **Regression – Predicting Ratings**  
- **Model:** Random Forest Regressor  
- **Key Drivers:**  
  - Reviews (strongest impact)  
  - Installs & Genres (moderate impact)  
  - Price & Content Rating (lower impact)  

### 4. **Classification – Free vs Paid Apps**  
- **Model:** Logistic Regression  
- **Findings:**  
  - Paid apps have slightly higher ratings  
  - Free apps = wider range (with many low outliers)  

### 5. **Time Series Forecasting**  
- **Model:** ARIMA  
- **Goal:** Predict app category growth in the next **5 years**  
- **Insight:** Certain categories show **rising demand** → market opportunity  

---

## 📊 Key Business Insights  

- 📈 More installs + positive reviews = higher app ratings  
- 🎯 Free apps often score higher in sentiment than paid ones  
- 💰 Price matters, but **user experience & reviews matter more**  
- 📊 Popularity depends on multiple features (not just app quality)  
- 🔮 Time series shows which categories will **boom in the next 5 years**  

---

## ✅ Conclusion & Future Scope  

**Takeaways:**  
- Ratings & reviews are **critical success indicators**  
- Predictive analytics helps developers and businesses make **data-driven decisions**  
- Feature engineering & data quality are crucial for accuracy  

**Future Enhancements:**  
- Integrate **Deep Learning** for advanced sentiment analysis  
- Apply **NLP** for context-based review understanding  
- Develop **real-time dashboards** for monitoring trends  

---
  
## 👨‍💻 Contributors  
- **Heta Chavda** (NF1014555)  
- **Tapan Mewada** (NF1009571)  
- **Neel Vadadariya** (NF1010276)  
- **Nadeem Basha Syed** (NF1013767)  


---

## 📂 Tech Stack  
- **Python (Pandas, NumPy, Scikit-Learn, NLTK, Statsmodels)**  
- **Visualization:** Matplotlib, Seaborn  
- **Models:** Random Forest, Logistic Regression, K-Means, ARIMA  
- **Data Source:** Kaggle  

---
