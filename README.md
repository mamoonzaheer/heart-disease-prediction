#  Heart Disease Prediction using Machine Learning

This project leverages machine learning techniques to predict the presence of heart disease using patient health data. It includes an end-to-end pipeline from data preprocessing and model training to web deployment using Flask.

---

##  Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes. This project aims to assist medical professionals by providing a machine learning model that can predict the likelihood of heart disease based on key health indicators.

---

##  Features

- Binary classification: Detect presence or absence of heart disease
- Data preprocessing pipeline using `scikit-learn`
- Trained model using Random Forest (99% accuracy)
- Flask web app with HTML frontend for user input and prediction
- Clean UI with immediate result display
- Ready-to-deploy structure

---

##  Project Structure

```
heart-disease-prediction/
├── app.py                         # Flask backend
├── dataset.csv                    # Heart disease dataset
├── Heart_Disease_Prediction.ipynb # Notebook for EDA & model training
├── preprocessing_pipeline.joblib # Preprocessing pipeline
├── rf_classifier.joblib          # Trained model
├── requirements.txt              # Dependencies
├── templates/
│   ├── index.html                # Input form
│   └── result.html               # Output display
└── README.md                     # Project documentation
```

---

##  Dataset

- **Source**: Kaggle  
- **Samples**: 1000+  
- **Features**: Age, Gender, Cholesterol, Blood Pressure, etc.  
- **Target**: `HeartDisease` (1 = Disease Present, 0 = No Disease)

---

##  Models Used

- Logistic Regression  
- Decision Tree  
- Random Forest  (Best accuracy)  
- Gradient Boosting  

---

##  Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

##  How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. **(Optional) Create virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate       # On macOS/Linux
   venv\Scripts\activate        # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**

   ```bash
   python app.py
   ```

5. **Open in browser**

   Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) to use the web app.

---

##  Future Enhancements

- Add explainability tools (e.g., SHAP, LIME)
- Deploy on Render or Vercel
- Integrate real-time health monitoring APIs
- Improve frontend styling

---

##  Acknowledgements

- [Kaggle](https://www.kaggle.com/) for the dataset  
- Open-source community (Flask, Scikit-learn, Pandas, Seaborn)

---

##  License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
