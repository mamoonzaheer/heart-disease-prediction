Heart Disease Prediction using Machine Learning

This project uses machine learning to predict the presence of heart disease based on patient health data. It features a full pipeline from data preprocessing to model deployment, including a simple web interface for user input and prediction display.


Features

Binary classification of heart disease (present/absent)

End-to-end ML pipeline with preprocessing, training, evaluation, and deployment

Flask-based web application with HTML frontend

Model serialization using joblib

Interactive predictions based on user input


Project Structure
Heart-Disease-Prediction/
├── Heart_Disease_Prediction.ipynb       # Main Jupyter Notebook for EDA and model training
├── app.py                               # Flask application for serving predictions
├── dataset.csv                          # Heart disease dataset
├── rf_classifier.joblib                 # Trained Random Forest model
├── preprocessing_pipeline.joblib        # Saved preprocessing pipeline
├── requirements.txt                     # Python dependencies
├── templates/
│   ├── index.html                       # Input form page
│   └── result.html                      # Prediction result page
└── README.md                            # Project documentation


Dataset

Source: Kaggle

Samples: 1000+

Features: Age, Blood Pressure, Cholesterol, Heart Rate, etc.

Target: HeartDisease (1 = Disease Present, 0 = No Disease)


How to Run the Project

1. Clone the Repository
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

2. (Optional) Create a Virtual Environment
python -m venv venv
source venv/bin/activate        # On macOS/Linux
venv\Scripts\activate           # On Windows

3. Install Required Libraries
pip install -r requirements.txt

4. Run the Flask App
python app.py

5. Open the App in Your Browser
Go to http://127.0.0.1:5000


Machine Learning Models Used

Logistic Regression
Decision Tree
Random Forest (Best model: 99% accuracy)
Gradient Boosting


Model Evaluation

Accuracy
Precision
Recall
F1 Score


Future Work

Add model explainability using SHAP or LIME
Deploy on cloud (Render, Vercel, etc.)
Improve frontend UI
Use real-world healthcare APIs or live data streams


Acknowledgements

Kaggle (Dataset)
Scikit-learn, Flask, Pandas, Seaborn — open-source tools that made this possible

License
This project is licensed under the MIT License — see the LICENSE file for details.