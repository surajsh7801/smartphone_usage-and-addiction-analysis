Smart Healthcare Risk Prediction System
📌 Project Overview

The Smart Healthcare Risk Prediction System is a Machine Learning project that analyzes patient health data and predicts the likelihood of heart disease. The project includes Exploratory Data Analysis (EDA), data preprocessing, visualization, and predictive modeling using Logistic Regression.

This system helps healthcare professionals identify high-risk patients based on various medical and lifestyle factors such as age, BMI, blood pressure, cholesterol levels, smoking habits, diabetes status, and more.

🎯 Objectives
Analyze healthcare data to identify health risk patterns.
Perform data visualization for better understanding of patient characteristics.
Build a machine learning model to predict heart disease.
Evaluate model performance using accuracy and confusion matrix.
📂 Dataset Features

The dataset contains the following attributes:

Feature	Description
age	Patient age
gender	Male/Female
bmi	Body Mass Index
blood_pressure	Blood pressure level
cholesterol	Cholesterol level
glucose	Blood glucose level
smoking	Smoking habit
alcohol	Alcohol consumption
exercise_level	Physical activity level
diabetes	Diabetes status
stroke	Stroke history
chest_pain	Chest pain symptom
fatigue	Fatigue symptom
dizziness	Dizziness symptom
health_risk_score	Overall health risk score
heart_disease	Target variable (0 = No, 1 = Yes)
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
📊 Exploratory Data Analysis (EDA)

The project includes visualizations such as:

Age Distribution
Gender Distribution
BMI Distribution
Blood Pressure Distribution
Cholesterol Distribution
Exercise Level vs Heart Disease
Smoking Impact on Heart Disease
Alcohol Consumption vs Heart Disease
Glucose vs BMI Analysis
Stroke vs Heart Disease
Correlation Heatmap
Health Risk Score Analysis
🤖 Machine Learning Model
Algorithm Used
Logistic Regression
Data Preprocessing
Missing value check
Feature selection
Gender encoding
Feature scaling using StandardScaler
Train-Test Split (80:20)
Model Training
model = LogisticRegression(max_iter=1000)
model.fit(X_train, y_train)
Prediction
y_pred = model.predict(X_test)
📈 Model Evaluation
Accuracy Score
accuracy_score(y_test, y_pred)
Confusion Matrix
confusion_matrix(y_test, y_pred)

The model performance is evaluated using:

Accuracy
Confusion Matrix
🚀 Installation

Clone the repository:

git clone https://github.com/yourusername/smart-healthcare-risk-prediction.git

Navigate to project directory:

cd smart-healthcare-risk-prediction

Install dependencies:

pip install -r requirements.txt

Run Jupyter Notebook:

jupyter notebook
📁 Project Structure
Smart-Healthcare/
│
├── smart_healthcare.ipynb
├── smart_healthcare_dataset.csv
├── README.md
├── requirements.txt
│
└── outputs/
    ├── visualizations
    └── confusion_matrix
💡 Future Improvements
Implement advanced algorithms (Random Forest, XGBoost).
Deploy the model using Streamlit.
Add real-time patient risk prediction.
Create an interactive healthcare dashboard.
Improve model accuracy through hyperparameter tuning.
👨‍💻 Author

Suraj Shinde
Aspiring Data Scientist | Data Analyst | Machine Learning Enthusiast

📜 License

This project is intended for educational and learning purposes. Feel free to modify and enhance it for research and development.
