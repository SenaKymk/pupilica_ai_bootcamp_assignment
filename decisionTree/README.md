# 📊 Decision Tree Classification on Breast Cancer Dataset

## 📖 Project Summary
This project focuses on training and evaluating a **Decision Tree Classifier** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

The goal is to classify tumors as malignant (M) or benign (B) based on various medical measurements.

---

## ✅ Steps Performed
- 📥 Loaded the dataset from **Kaggle**
- 🔎 Checked and handled missing values
- 🤖 Built and trained a **Decision Tree Classifier**
- 📈 Performed **Feature Importance Analysis**
- ✂️ Removed features with **zero importance** and retrained the model
- 🔄 Compared and analyzed the model performance before and after feature selection

---

## 🎯 Model Performance

| Stage                 | Train Accuracy | Test Accuracy |
|-----------------------|---------------|--------------|
| **Before Feature Removal** | 99.56%        | 93.85%        |
| **After Feature Removal**  | 100%          | 93.85%        |

---

## 💡 Conclusion
Removing the features with zero importance:
- ✅ Simplified the model
- ✅ Did not affect the model performance
- ✅ Improved interpretability

The model remains robust and accurate after feature selection.

---

## 📌 Notes
Further improvements could include:
- Cross-validation for more reliable accuracy
- Testing other models such as Random Forest or Gradient Boosting
- Visualizing the decision tree for better interpretability
