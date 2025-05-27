# ❤️ Heart Disease Prediction
This project uses machine learning to predict the presence of heart disease in patients using clinical data from the UCI Heart Disease dataset.

## 📊 Dataset
- 303 patient records
- 13 input features like age, cholesterol, chest pain, ST depression, etc.
- Binary target: 0 = no disease, 1 = disease

## 🧠 Models Used
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest (best performer)

## 🔍 Explainability
We used **SHAP values** to understand feature importance and improve interpretability:
- `cp` (chest pain), `thal`, and `oldpeak` were the most impactful features
- SHAP plots are included for both continuous and categorical features

## 🎯 Accuracy
- Final Random Forest accuracy: ~84%
- Precision and recall balanced across both classes

## 📁 Files
| File | Description |
|------|-------------|
| `heart_disease_prediction.ipynb` | Jupyter notebook with full workflow |
| `heart.csv` | Dataset used |
| `shap_summary_all.png` | SHAP summary for all features |
| `shap_continuous.png` | SHAP summary for continuous features |
| `shap_categorical.png` | SHAP for categorical/binary features |
| `README.md` | Project summary |

## 🚀 Future Work
- Deploy model with Streamlit or Flask
- Add patient-specific SHAP explanations
- Cross-validate on other health datasets
