# 🫀 Heart Disease Prediction Web App

This is a machine learning web app that predicts whether a person has heart disease based on various medical parameters. The app is built using **Streamlit** and uses the **Gaussian Naive Bayes** classifier for prediction.

---

## 📁 Dataset

The model is trained on a dataset containing 13 features such as:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Max Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia

🎯 **Target variable**: `target` (1 = has heart disease, 0 = no heart disease)

---
pip install -r requirements.txt
streamlit
pandas
numpy
scikit-learn
joblib

---
streamlit run app.py

---
🧠 Model Details
Algorithm: Gaussian Naive Bayes

Performance Metrics:

Precision: 0.82

Recall: 0.76

F1-Score: 0.79

Confusion Matrix

---
📦 Files
File	Description
app.py	Streamlit UI code
heart_model.pkl	Trained machine learning model
heart.csv	Dataset used
requirements.txt	List of dependencies
heart project (1).ipynb	Jupyter notebook with data analysis and model training

---
👨‍💻 Author
Developed by Jaya bijore


---
📝 License
This project is open source and available under the MIT License.

---
## ⚠️ Disclaimer

This project is created solely for educational and learning purposes.  
It is not intended for real-world medical diagnosis, decision-making, or commercial use.

Always consult professional healthcare providers for actual medical conditions or advice.








