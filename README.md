# 🌾 Crop Prediction and Recommendation Based on Climatic Conditions Using Machine Learning

This project uses a machine learning model to recommend the most suitable crop for cultivation based on soil and climatic conditions. It supports data-driven decisions in agriculture to improve yield, efficiency, and sustainability.

---

## 📘 Project Overview

The notebook `crop.ipynb` demonstrates:

- Data loading and preprocessing
- Exploratory data analysis and visualization
- Model training using Random Forest Classifier
- Model evaluation using accuracy score and classification report
- Crop prediction based on custom environmental input

---

## 🧪 Technologies Used

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab / Jupyter Notebook

---

## 📂 Dataset

- The dataset contains agricultural records with the following features:
  - **Nitrogen (N)**, **Phosphorus (P)**, **Potassium (K)**
  - **Temperature** (°C), **Humidity** (%)
  - **pH Level**
  - **Rainfall** (mm)
  - **Label**: Recommended Crop (e.g., rice, maize, cotton)

---

## 🧠 Model Used

The main model used in this project is the **Random Forest Classifier**, an ensemble method that constructs multiple decision trees and combines their predictions for improved accuracy and robustness.

- **Advantages of Random Forest:**
  - Effectively handles high dimensional data.
  - Reduces overfitting compared to single decision trees.
  - Provides feature importance to identify key influencing factors.

Other models that can be explored include:
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Logistic Regression
- K-Nearest Neighbors (KNN)

Random Forest was selected for its superior performance on this dataset.

---

## 📈 Model Performance

- Achieved over **98% accuracy** on test data.
- Evaluation metrics include precision, recall, and F1-score.
- Visualization includes feature distributions, correlation heatmaps, and confusion matrices.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/niiiiitish/Crop-prediction-and-recommendation-climatic-condition-using-ML.git
