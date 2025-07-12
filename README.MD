# 🏥 Medical Appointment No-Show Analysis

This project explores factors that influence whether a patient attends or misses a scheduled medical appointment. Using real data from over 100,000 appointments in Brazil, I applied Python and machine learning to identify trends and make predictions.

---

## 🔧 Tools & Libraries
- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- scikit-learn (Random Forest, train-test split, metrics)

---

## 💡 Key Insights So Far
- **Patients who received an SMS reminder** were more likely to attend their appointment
- **Longer wait times** between scheduling and appointment date increased no-show risk
- **Very young and elderly patients** had higher show-up rates than middle-aged adults


---

## 🤖 ML Model
- Trained a Random Forest Classifier to predict no-shows using patient and appointment features
- Achieved solid baseline performance (accuracy ~75%)
- Most influential features: `days_waited`, `sms_received`, and `age`

### Feature Importance Visualization
![Feature Importance](images/feature_importance_noshow.png)

---

## 📁 Dataset
- [Kaggle: Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

---