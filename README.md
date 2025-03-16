# Drug Prediction Using Decision Tree

## 📌 Overview
This project focuses on predicting the appropriate drug for a patient based on their medical attributes such as age, blood pressure, and cholesterol levels. The model is built using a Decision Tree classifier, which helps in classifying patients into different drug categories.

## 🔍 Purpose
The primary goal of this project is to:
- Develop a machine learning model that can prescribe the correct drug for a patient.
- Utilize a **Decision Tree** classifier to interpret medical data effectively.
- Demonstrate how medical conditions influence drug prescriptions.

## 📊 Dataset
The dataset consists of patient attributes such as:
- **Age**
- **Blood Pressure (BP)**
- **Cholesterol Level**
- **Drug Type (Target Variable)**

Each patient is categorized into one of multiple drug types based on these attributes.

## 🏗️ Model Used
The **Decision Tree Classifier** is used to build the predictive model. The tree splits the data based on key attributes, reducing entropy at each step to determine the best drug prescription.

## 🔬 Insights from the Model
- Patients are classified into different drug types based on decision rules.
- The entropy values show how well the model separates different drug categories.
- The trained model can be used to predict drug prescriptions for new patients.

## 🚀 Implementation
### 1️⃣ Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib
```

### 2️⃣ Load Dataset
### 3️⃣ Train the Model
### 4️⃣ Visualize the Tree

## 🎯 Predictions
The model can now predict the most suitable drug for a new patient:
```python
new_patient = [[45, 1, 0]]  # Age: 45, BP: 1 (High), Cholesterol: 0 (Normal)
predicted_drug = model.predict(new_patient)
print("Predicted Drug:", predicted_drug)
```

## 🏆 Key Takeaways
- This is a **multiclass classification** problem.
- Decision Trees can be effectively used for medical diagnosis.
- The model can generalize to predict drugs for new patients.

## 📜 Conclusion
This project demonstrates how Decision Trees can be used for medical applications, particularly in **prescribing the right drug based on patient data**. It serves as a simple yet powerful way to automate drug recommendations.

## 🔗 Connect
📧 Email: hello.nivashinsights@gmail.com  
🔗 LinkedIn: [Nivash R N](https://www.linkedin.com/in/nivash-r-n/)  
🌐 Portfolio: [rnnivash.github.io/My_Port](https://rnnivash.github.io/My_Port/)

