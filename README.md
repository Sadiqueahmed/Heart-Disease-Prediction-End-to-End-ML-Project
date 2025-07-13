# ❤️ Heart Disease Prediction – End-to-End ML Project

This project uses Machine Learning to predict the presence of heart disease in patients based on various medical attributes. It walks through the complete ML workflow — from data preprocessing and visualization to model training, evaluation, and interpretation.

---

## 📁 Dataset

The dataset used is `heart.csv`, containing 14 clinical features and a binary target variable (`0` for absence, `1` for presence of heart disease).

| Feature        | Description                                      |
|----------------|--------------------------------------------------|
| age            | Age of the patient                               |
| sex            | Gender (1 = male; 0 = female)                    |
| cp             | Chest pain type (0–3)                            |
| trestbps       | Resting blood pressure                           |
| chol           | Serum cholesterol (mg/dl)                        |
| fbs            | Fasting blood sugar (> 120 mg/dl)                |
| restecg        | Resting ECG results                              |
| thalach        | Maximum heart rate achieved                      |
| exang          | Exercise-induced angina                          |
| oldpeak        | ST depression induced by exercise                |
| slope          | Slope of the peak exercise ST segment            |
| ca             | Number of major vessels colored by fluoroscopy  |
| thal           | Thalassemia (0 = normal; 1 = fixed defect; etc.) |
| target         | 1 = heart disease, 0 = no heart disease          |

---

## 🔍 Workflow

1. **Data Loading & Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Correlation Matrix**
4. **Data Preprocessing & Scaling**
5. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
6. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
7. **Feature Importance (Random Forest)**

---

## 🚀 Models & Results

| Model                | Accuracy (%) |
|----------------------|--------------|
| Logistic Regression  | ~83–85%      |
| Random Forest        | ~87–90%      |

> 📌 Random Forest generally performed better in this project.

---

## 📊 Visualizations

- Countplots of target distribution  
- Correlation heatmap  
- Feature importance bar chart  

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📎 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Sadiqueahmed/Heart-Disease-Prediction-End-to-End-ML-Project.git
   ```
2. Navigate to the folder:
   ```bash
   cd Heart-Disease-Prediction-End-to-End-ML-Project
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Heart_Disease_Prediction.ipynb
   ```

---

## 📌 Project Status

✅ Completed — Exploratory + Predictive Modeling done.  
🚀 Scope for improvement with hyperparameter tuning and advanced models like XGBoost or SVM.

---

## 👤 Author

- **Sadique Ahmed**
- [GitHub Profile](https://github.com/Sadiqueahmed)
