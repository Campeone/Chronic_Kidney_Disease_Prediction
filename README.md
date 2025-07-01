# Chronic Kidney Disease (CKD) Prediction Using Machine Learning

This project is a comprehensive machine learning pipeline designed to predict the presence of Chronic Kidney Disease (CKD) using clinical data. The project is intended to be part of an academic portfolio for a master's application in Health Data Science.

## 🔍 Problem Statement
Early detection of Chronic Kidney Disease (CKD) can significantly improve patient outcomes by enabling timely interventions. This project aims to build predictive models that classify whether a patient has CKD based on clinical measurements.

## 📁 Dataset
- **Source**: Kaggle / UCI Repository
- **Format**: CSV
- **Attributes**: Contains numerical and categorical features such as blood pressure, serum creatinine, albumin, hemoglobin, age, etc.
- **Target Variable**: `classification` (CKD or not CKD)

## ✅ Project Steps

### 1. Exploratory Data Analysis (EDA)
- Inspected the dataset structure and checked for missing values
- Visualized distributions of features
- Plotted correlation heatmaps and boxplots

### 2. Data Preprocessing
- Scaled numerical features using `StandardScaler`


### 3. Model Building
- **Train-Test Split**: 80-20 split with stratified sampling
- **Models Trained**:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - XGBoost Classifier
  - Support Vector Machine (SVM)
- **Model Evaluation Metrics**:
  - Confusion Matrix
  - Accuracy
  - Precision, Recall, F1-score

### 4. Hyperparameter Tuning
- Used `GridSearchCV` to tune Random Forest hyperparameters
- Selected best model based on cross-validation performance

### 5. Feature Engineering 
- Perform standardization on the dataset

### ⚡ **Project Structure**
```
Heart_Disease_EDA/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks with EDA and modelling
├── visualizations/        # Generated plots and charts
├── README.md              # Project overview and documentation
└── requirements.txt       # Dependencies
```

### 🛠️ **Tools & Libraries**

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, xgboost

## 📊 Results
- Best model: **Random Forest Classifier** after tuning
- Achieved high accuracy and good balance between precision and recall

## 📎 Files Included
- `chronic_kidney_disease.csv`: Dataset
- `ckd_modeling.ipynb`: Jupyter notebook with full analysis
- `README.md`: Project documentation

## 📌 How to Run
1. Clone the repository or download the notebook
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook step-by-step

## 🎓 Purpose
This project demonstrates the application of data science and machine learning in healthcare, specifically for predicting chronic illnesses. It was developed as part of a portfolio to support applications to graduate programs in Biomedical Data Science.

## 🔗 Author
**Ojo Timilehin**  
Email: [ojotimilehin01@gmail.com](mailto:ojotimilehin01@gmail.com)  
GitHub: [github.com/Campeone](https://github.com/Campeone)  

---
> "Empowering early diagnosis through data-driven health insights."
