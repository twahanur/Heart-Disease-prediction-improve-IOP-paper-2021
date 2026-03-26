# ❤️ Heart Disease Prediction System

**Machine Learning Based Heart Disease Prediction**  
*Improved Logistic Regression Model with 92% Accuracy*

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Project Overview

This project implements a **Heart Disease Prediction System** based on the research paper:

> **"Heart disease prediction using machine learning algorithms"**  
> Harshit Jindal et al., 2021, IOP Conference Series

We have **improved** the original paper's accuracy from **87.5%** to **92.00%** by:
- Dropping low-correlation features (`fbs` & `chol`)
- Proper preprocessing and feature scaling
- Hyperparameter tuning
- Extensive model comparison

---

## ✨ Key Features

- **Best Model**: Logistic Regression (Improved) → **92.00% Accuracy**
- **Dataset**: UCI Cleveland Heart Disease Dataset (303 records)
- Multiple algorithms tested (KNN, Random Forest, Voting Classifier, XGBoost, LightGBM, MLP etc.)
- Full EDA with Correlation Heatmap
- ROC Curve & Confusion Matrix visualization
- Clean, well-documented Jupyter Notebook

---

## 📊 Results Comparison

| Model                          | Accuracy    | Improvement over Paper |
|-------------------------------|-------------|------------------------|
| Paper (Jindal 2021)           | 87.50%      | -                      |
| KNN (Best)                    | 85.33%      | -                      |
| Random Forest                 | 86.67%      | -                      |
| Weighted Voting               | 89.33%      | +1.83%                 |
| **Final Improved LR**         | **92.00%**  | **+4.50%**             |

**AUC Score**: ~0.94 (very good)

---

## 🗂️ Dataset Information

- **Source**: https://archive.ics.uci.edu/ml/datasets/heart+disease
- **Total Records**: 303
- **Features**: 13 medical attributes (age, sex, chest pain, blood pressure, etc.)
- **Target**: Binary (0 = No Heart Disease, 1 = Heart Disease)

---

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn
- LightGBM, XGBoost (tested)
- Jupyter Notebook

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/twahanur/Heart-Disease-prediction-improve-IOP-paper-2021.git
cd Heart-Disease-prediction-improve-IOP-paper-2021
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open `Heart_Disease_Prediction.ipynb` in Google Colab or Jupyter Notebook.

---

## 📁 Project Structure

```
├── Heart_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
├── model.pkl
├── scaler.pkl (scaled version)
└── screenshots/
```

---

## 📈 Future Improvements

- Deploy as Web App using Streamlit
- Add patient data input form
- Implement Deep Learning model
- Real-time prediction API

---

## 📚 References

- Jindal et al. (2021)
- UCI Heart Disease Dataset

---

## 👨‍💻 Author

**Twahanur Rahman**  
https://github.com/twahanur  

---

**Made with ❤️ for better healthcare using Machine Learning**
