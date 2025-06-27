# 🚆 Smart Deal Recommendation System for Commuters and Students

This project builds a smart recommendation system that offers personalized, cost-effective deals to commuters and students based on their travel patterns, demographics, preferences, and external factors like weather and time of day.

## 🧠 Problem Statement
Urban commuters and students often miss out on relevant local deals. This system leverages machine learning to suggest offers that align with their context — increasing redemption rates and convenience.

## 📊 Dataset
- 12,600+ rows
- Features include: trip purpose, travel companion, weather, temperature, time of day, user demographics, and previous visit behaviors.
- Target variable: `redeemed` (whether the offer was redeemed or not)

## 🧹 Preprocessing
- Handled missing values using logical imputation
- Encoded categorical variables via One-Hot Encoding
- Outlier detection and scaling using `RobustScaler`
- Feature selection using `VarianceThreshold` and Random Forest importance scores

## ⚙️ ML Models Used
- ✅ **Random Forest Classifier** (best performing — Accuracy: ~74.7%)
- Logistic Regression
- Multinomial Naive Bayes
- Gradient Boosting
- Support Vector Classifier (SVC)
- XGBoost Classifier

## 🧪 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix

## 📈 Results
Random Forest and XGBoost both achieved an accuracy of ~74.7% with balanced precision-recall across classes.

## 🚀 Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn (for EDA and visualization)

## 📌 Future Improvements
- Add user authentication and real-time geolocation
- Integrate with live deal APIs
- Deploy as a mobile app or web dashboard

---

### 🔗 Connect With Me
Feel free to check out the [LinkedIn Post](https://www.linkedin.com/posts/yash1th011_smartdealrecommendations-activity-7344303556373508099-LP9X?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD1bMZgBgDjjqddr3c0e7UqSMqnym2mBC5k) or connect to discuss improvements or collaboration!

