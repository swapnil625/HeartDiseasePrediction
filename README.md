
# 🫀 Heart Disease Risk Prediction

## 📌 Project Overview
Developed a classification model to **predict the risk of heart disease** using patient health data from the **Framingham Heart Study** dataset. The objective is to assist in identifying individuals at high risk of developing coronary heart disease (CHD) within 10 years.

## 🛠️ Features & Workflow
- Data Cleaning & Preprocessing (handling missing values, scaling)
- Manual Oversampling to balance the dataset
- Model Training:
  - Random Forest Classifier
- Model Evaluation:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📈 Results
- Achieved **98% accuracy** with Random Forest.
- Improved recall for high-risk patients (CHD=1) up to **99%** using threshold tuning.

## 📂 Dataset
- **Framingham Heart Study dataset**
- Features include: age, sex, smoking status, blood pressure, cholesterol, glucose levels, etc.

## ✅ How to Run
1. Clone this repository or download files.
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the Jupyter Notebook:
```
jupyter notebook Heart_Disease_Prediction.ipynb
```

## 📌 Repository Structure
```
Heart-Disease-Prediction/
├── dataset/ Heart.csv.csv                       
├── pyhton Code/Heart_Disease_Prediction.ipynb
├── requirements.txt
└── README.md
```

## 👩‍💻 Author
Swapnil Dave 
