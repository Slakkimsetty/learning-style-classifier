# 🎓 Learning Style Classifier

This machine learning project predicts a student's preferred learning style (Visual, Aural, Read/Write, Kinesthetic) based on simple quiz inputs.

---

## 📊 Problem

Students often struggle to study effectively because they don’t understand their ideal learning style. This model uses ML to predict learning preferences and recommend learning strategies.

---

## 📁 Dataset

We used a simulated version of the [VARK Learning Styles Dataset](https://www.kaggle.com/datasets/jessemostipak/vark-learning-styles-dataset), which originally contains responses to a learning preferences survey.

### 🔹 Features:
- **Visual**: Score for visual learning preference
- **Aural**: Score for auditory learning
- **Read/Write**: Score for reading and writing preference
- **Kinesthetic**: Score for hands-on learning
- **Label**: The dominant learning style category

The dataset was either manually created or adapted from available VARK-style templates for educational purposes.

---

## 🚀 Features

- Predicts VARK learning style using survey inputs
- Compares 4 models: Logistic Regression, Decision Tree, Random Forest, KNN
- Interactive Streamlit app to test live predictions
- Fully explained step-by-step in notebooks

---

## 🛠 Tech Stack

| Task | Tool |
|------|------|
| ML Models | scikit-learn |
| Data Handling | pandas, numpy |
| Visualization | seaborn, matplotlib |
