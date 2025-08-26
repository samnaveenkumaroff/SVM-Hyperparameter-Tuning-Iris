# SVM-Hyperparameter-Tuning-Iris

---

## 📂 Repo Structure

```
SVM-Hyperparameter-Tuning-on-Iris/
│── notebook/
│   └── iris_svm_hyperparameter_tuning.ipynb
│── README.md
```

---

## 📑 README.md

```markdown
# 🌸 SVM Hyperparameter Tuning on Iris Dataset

This project demonstrates **Support Vector Machine (SVM) hyperparameter optimization** on the classic **Iris dataset** using **GridSearchCV** and **RandomizedSearchCV**.  
It is designed as part of the **AutoML subject** to showcase how hyperparameter tuning can significantly improve model performance.

---

## 📊 Dataset
- **Dataset:** Iris Flower Dataset (built-in with sklearn)
- **Classes:** Setosa, Versicolor, Virginica
- **Features:** Sepal length, Sepal width, Petal length, Petal width

---

## ⚙️ Techniques Used
1. **Support Vector Machine (SVM)** for classification  
2. **GridSearchCV** for exhaustive search over parameter space  
3. **RandomizedSearchCV** for efficient randomized search  
4. **Pipeline & StandardScaler** for preprocessing  
5. **Train-Test Split & Cross Validation** for model evaluation  

---

## 🚀 Results
- **GridSearchCV Best Parameters:** `{'C': 1, 'kernel': 'rbf', 'gamma': 'scale'}`  
- **GridSearchCV Test Accuracy:** ~97%  

- **RandomizedSearchCV Best Parameters:** `{'C': 0.1, 'kernel': 'linear', 'gamma': 'scale'}`  
- **RandomizedSearchCV Test Accuracy:** ~100%  

👉 You’ll see how **different hyperparameter search strategies** can give **different results** even on the same dataset.

---

## 📂 Repository Structure
```

notebook/
└── iris\_svm\_hyperparameter\_tuning.ipynb
README.md

````

---

## ▶️ Run Notebook Online

Click the badge below to open this project in **Google Colab**:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/samnaveenkumaroff/SVM-Hyperparameter-Tuning-on-Iris/blob/main/notebook/iris_svm_hyperparameter_tuning.ipynb)

---

## 📦 Requirements
Install dependencies:
```bash
pip install -r requirements.txt
````

`requirements.txt`

```
scikit-learn
numpy
pandas
matplotlib
```

---

## 🌟 Why this Project?

* Beginner-friendly
* Helps understand **AutoML basics**
* Great starting point for anyone learning **ML model optimization**

---

## ✨ Author

**Done with ❤️ by [Sam Naveenkumar V](https://github.com/samnaveenkumaroff)**

🔗 [GitHub](https://github.com/samnaveenkumaroff)
🔗 [LinkedIn](https://www.linkedin.com/in/samnaveenkumaroff)

```
