# ❤️ Heart Disease Prediction Using Hybrid Machine Learning

## 📌 Overview
A machine learning project that predicts heart disease using patient health attributes. It compares multiple models and combines predictions through a hybrid approach to improve classification performance.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Random Forest
- Artificial Neural Network (ANN)
- SHAP for model interpretability
- Matplotlib and Seaborn

## 📊 Dataset
- **Records:** 918
- **Input features:** 11
- **Target:** `HeartDisease` (0 = No Disease, 1 = Disease)
- **Train-test split:** 80:20

## ⚙️ Workflow
1. Load and explore the dataset.
2. Encode categorical features.
3. Scale numerical features using `StandardScaler`.
4. Split data into training and testing sets.
5. Train and evaluate Logistic Regression, Random Forest, and ANN.
6. Build and evaluate the hybrid model.
7. Compare performance using accuracy, F1-score, and ROC-AUC.
8. Analyse feature importance using Random Forest and SHAP.

## 📈 Model Performance

| Model | Accuracy | F1-score | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 86.96% | 0.8879 | 0.8971 |
| Random Forest | 89.13% | 0.9038 | 0.9285 |
| ANN | 88.04% | 0.8942 | 0.9154 |
| **Hybrid Model** | **91.30%** | **0.9223** | **0.9291** |

## 🏆 Key Results
- The hybrid model achieved **91.30% accuracy** and an **F1-score of 0.9223** on the test set.
- It achieved the highest accuracy and F1-score among the four evaluated models.
- Random Forest achieved a ROC-AUC of 0.9285, while the hybrid model achieved 0.9291.
- The notebook includes a classification report, confusion matrix, ROC curves, threshold analysis, five-fold cross-validation, and SHAP analysis.

## 🚀 How to Run
1. Open the notebook in Google Colab.
2. Upload the `heart.csv` dataset when prompted.
3. Install the required dependencies.
4. Run the notebook cells in order.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow shap
```

## ⚠️ Disclaimer
This project is for educational and research purposes only. It is not a substitute for professional medical advice or diagnosis.
# heart-disease-prediction
