# 🌸 SVM Hyperparameter Tuning on Iris Dataset

This project demonstrates **Support Vector Machine (SVM) hyperparameter optimization** on the classic **Iris dataset** using **GridSearchCV** and **RandomizedSearchCV**.  
It is designed as part of the **AutoML subject** to showcase how hyperparameter tuning can significantly improve model performance.

## 📂 Repo Structure

```
SVM-Hyperparameter-Tuning-on-Iris/
│── notebook/
│   └── iris_svm_hyperparameter_tuning.ipynb
│── README.md
```
## 📌 Questions

### Question 1
1. Import the dataset from `sklearn.datasets`.
2. Split the data into training and testing sets.
3. Create a **Pipeline** with:
   - `StandardScaler` for feature scaling
   - `SVC` (Support Vector Classifier) as the model
4. Use **GridSearchCV** to tune the following hyperparameters:
   - `C`: [0.1, 1, 10]
   - `kernel`: ['linear', 'rbf']
5. Print:
   - The **best parameters**
   - The **best cross-validation score**
   - The **test accuracy**

---

### Question 2
1. Import the dataset from `sklearn.datasets`.
2. Split into training and testing sets.
3. Build a **Pipeline** with:
   - `StandardScaler`
   - `SVC` (Support Vector Classifier)
4. Perform **GridSearchCV** and **RandomizedSearchCV** using the following parameter ranges:
   - `C`: [0.1, 1, 10, 100]
   - `kernel`: ['linear', 'rbf', 'poly']
   - `gamma`: ['scale', 'auto']
5. Compare and print for both methods:
   - **Best parameters**
   - **Cross-validation accuracy**
   - **Test accuracy**


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
