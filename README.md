# 🌼 Iris Flower Classification – Machine Learning Project

End-to-end ML pipeline using Python, Pandas, Scikit-Learn, Seaborn & Matplotlib.

---

## 📌 1. Project Overview

The Iris dataset is one of the most famous datasets used for learning Machine Learning.  
This project predicts the **species of an Iris flower** using **4 numerical features**, applying a full ML workflow:

- Data Loading  
- EDA  
- Data Cleaning  
- Label Encoding  
- Train–Test Split  
- Multiple ML Models  
- Model Comparison  
- Feature Importance  
- User Input Prediction Function  

---

## 📊 2. Problem Definition

**Goal:**  
Given 4 measurements of a flower:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

Predict the **species**:

- Setosa  
- Versicolor  
- Virginica  

**Type:** Multiclass Classification  
**Success Metric:** Accuracy → Confusion Matrix → Classification Report  

---

## 📁 3. Dataset Information

- **Source:** Iris.csv  
- **Total Samples:** 150  
- **Features:** 4 numeric  
- **Classes:** 3  
- **Balanced Dataset:** Yes (50 each)  

---

## 🧪 4. EDA (Exploratory Data Analysis)

### ✓ Checked:

- Shape  
- Column names  
- Data types  
- Null values  
- Statistical summary  

### ✓ Visuals:

- Histograms  
- Scatter plots  
- Pairplot  
- Correlation heatmap  

**Key Observations:**

- PetalLength & PetalWidth are the strongest discriminators.  
- Setosa species is always cleanly separable.  
- Dataset is noise-free & balanced → ML models perform well.  

---

## 🧹 5. Data Cleaning

- Removed ID column  
- No missing values  

---

## 🏷 6. Label Encoding

Species → encoded into numerical target:

- Setosa → 0  
- Versicolor → 1  
- Virginica → 2  

---

## 🔀 7. Train–Test Split

- 80% training  
- 20% testing  

---

## 🤖 8. Models Used

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~95%     |
| Decision Tree       | ~93%     |
| Random Forest       | ~96–98%  |
| SVM                 | ~96–98%  |

---

## 🥇 9. Best Model

**Random Forest** & **SVM** performed the best.  
They captured feature interactions better & gave highest accuracy.

---

## 🔍 10. Feature Importance (Random Forest)

Most important features:

1. Petal Length  
2. Petal Width  
3. Sepal Length  
4. Sepal Width  

Petal-based features dominate species classification.

---

## 🧾 11. Prediction Function (User Input)

Allows manual testing:

```python
predict_species(5.1, 3.5, 1.4, 0.2)
```

Output:

```
Setosa
```

---

## 🧠 12. Insights

- Iris is excellent for beginners to learn end-to-end ML workflow.  
- Dataset is perfectly clean and balanced → ideal for practicing modeling.  
- RandomForest provides powerful performance + feature importance.  
- Good starter project for internships & ML portfolio.  

---

## 🛠 13. Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Seaborn  
- Matplotlib  

---

## 🚀 14. How to Run

```bash
pip install -r requirements.txt
python iris_project.ipynb
```

---

## 📎 15. Future Improvements

- Add hyperparameter tuning  
- Add model deployment (Flask/Streamlit)  
- Export model as .pkl for real use  
- Add interactive UI  

---

## 🙌 Author

**Deepanshu Yadav**  
Beginner Machine Learning Engineer  
India  