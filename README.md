# Rock-vs-Mine-Prediction

📌 Project Overview

This project aims to classify objects detected by sonar as either rocks or mines using machine learning techniques. The dataset contains numerical frequency readings of sonar signals, and a Logistic Regression model is used for classification.

📂 Dataset Description

Source: sonar_data.csv

Rows: 207

Columns: 61

Features: First 60 columns represent sonar frequency readings.

Target Variable:

R → Rock

M → Mine

⚙️ Installation & Dependencies

Prerequisites

Ensure you have Python installed. Required libraries:

pip install numpy pandas scikit-learn

🚀 Usage Instructions

Clone the repository:

git clone https://github.com/your-username/sonar-rock-mine-prediction.git
cd sonar-rock-mine-prediction

Run the Python script:

python main.py

🔬 Model Training & Evaluation

Splitting Data: 90% Training, 10% Testing

Model Used: Logistic Regression

Training the Model:

model = LogisticRegression()
model.fit(X_train, Y_train)

Performance Metrics:

accuracy_score(Y_test, model.predict(X_test))

📊 Results & Future Scope

Achieved decent accuracy using Logistic Regression.

Can be improved using advanced models like Random Forest or Neural Networks.
