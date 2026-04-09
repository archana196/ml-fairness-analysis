# Model Fairness, Bias and Explainability Analysis

## 📌 Objective
Analyze fairness and bias in a machine learning model using SHAP and apply mitigation techniques.

## 📊 Dataset
Adult Income Dataset

## 🤖 Model
Random Forest Classifier

## 🔍 Explainability
Used SHAP to:
- Identify important features
- Explain individual predictions

## ⚖️ Bias Detection
- Checked bias using gender (sex)
- Compared selection rates between groups

## 🛠️ Mitigation
- Removed gender-related features
- Retrained the model

## 📈 Results
- Bias reduced slightly / remained similar
- Accuracy remained stable

## ✅ Conclusion
- Models can learn bias from data
- Removing sensitive attributes alone is not enough
- SHAP improves model transparency

## 🔮 Future Work
- Remove correlated features
- Use fairness-aware algorithms