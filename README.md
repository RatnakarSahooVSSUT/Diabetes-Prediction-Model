# 🩺 Diabetes Prediction Model  
### 🚀 Machine Learning Project using IBM Watson Studio (AutoAI)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-IBM%20Watson%20Studio-blue?style=for-the-badge&logo=ibm" />
  <img src="https://img.shields.io/badge/Machine%20Learning-AutoAI-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Algorithm-XGBoost-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Deployed-success?style=for-the-badge" />
</p>

---

## 📌 Project Overview
This project presents an **end-to-end machine learning solution** for predicting diabetes using patient health data.  
Built using **IBM Watson Studio AutoAI**, the system automates the entire ML pipeline—from preprocessing to deployment.

🔍 The model analyzes medical parameters and predicts whether a person is **diabetic or non-diabetic**, along with a confidence score.

---

## 🎯 Key Highlights
✔️ Fully automated ML pipeline (AutoAI)  
✔️ Multiple model generation & comparison  
✔️ Best model selected based on accuracy optimization  
✔️ Real-time deployment on IBM Cloud  
✔️ API-based prediction system  
✔️ Beginner-friendly yet industry-relevant project  

---

## 🧠 Machine Learning Workflow
Data Collection → Data Preprocessing → Feature Engineering → Model Training → Hyperparameter Optimization → Pipeline Selection → Deployment → Prediction API

---

## 🛠️ Tech Stack

| Category        | Technology Used              |
|----------------|----------------------------|
| Platform       | IBM Watson Studio           |
| ML Approach    | AutoAI                     |
| Algorithm      | XGBoost Classifier         |
| Language       | Python (Auto-generated)    |
| Deployment     | IBM Cloud                  |

---

## 📂 Input Features
The model uses the following healthcare parameters:

- Gender  
- Age  
- Hypertension (0/1)  
- Heart Disease (0/1)  
- Smoking History  
- BMI (Body Mass Index)  
- HbA1c Level  
- Blood Glucose Level  

---

## 📈 Sample Prediction

Input:
- Age: 28  
- BMI: 25.19  
- HbA1c: 6.6  
- Blood Glucose Level: 91  

Output:
- Prediction: **Non-Diabetic (0)**  
- Confidence: **91%**

---

## 🔌 API Integration

Example Request:

{
  "input_data": [
    {
      "fields": [
        "gender",
        "age",
        "hypertension",
        "heart_disease",
        "smoking_history",
        "bmi",
        "HbA1c_level",
        "blood_glucose_level"
      ],
      "values": [
        ["Male", 28, 0, 0, "never", 25.19, 6.6, 91]
      ]
    }
  ]
}

---

## ⚡ How to Use
1. Login to IBM Watson Studio  
2. Open the project workspace  
3. Navigate to deployed model  
4. Use Test Tab or API endpoint  
5. Enter input data and get predictions  

---

## 📌 Why This Project Stands Out
- Demonstrates AutoML + Deployment skills  
- Real-world healthcare application  
- No manual coding required for ML pipeline  
- Industry-level cloud deployment exposure  

---

## 🔮 Future Enhancements
- Interactive web dashboard (React / Flask)  
- Mobile app integration  
- Explainable AI (XAI) visualization  
- Integration with IoT health monitoring systems  

---

## 👨‍💻 Author

**Ratnakar Sahoo**  
B.Tech – Electronics & Telecommunication Engineering  
VSSUT Burla  

---

## 🤝 Connect With Me
<p align="left">
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://github.com/">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github" />
  </a>
</p>

---

## ⭐ Acknowledgment
- IBM Watson Studio  
- AutoAI for automated machine learning  

---

## 🌟 Show Your Support
If you like this project, consider giving it a ⭐ on GitHub!
