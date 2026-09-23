# 🤖 AI & ML Practical Exercise

### Subject Code: **704 — Artificial Intelligence & Machine Learning**

This repository contains the practical implementations for the **AI & ML Practical Exercise**.

The practicals cover **Naïve Bayes, k-Nearest Neighbors (kNN), Bayesian Networks, classification metrics, algorithm comparison, and user-input prediction** using different CSV datasets.

---

## 📚 Practical Questions

### 01 — Naïve Bayes Classifier

**Dataset:** `pima_indian.csv`

> Write a program to implement the **Naïve Bayesian classifier** for a sample training data set stored as a `.CSV` file. Compute the **accuracy of the classifier**, considering a few test data sets.

**Concepts Covered:**

* Naïve Bayes Classifier
* Training & Testing Data
* Classification
* Accuracy

---

### 02 — Bayesian Network for Heart Disease Diagnosis

**Dataset:** `heart.csv`

> Write a program to construct a **Bayesian Network** considering medical data. Use this model to demonstrate the **diagnosis of heart patients** using a standard Heart Disease Dataset. Calculate the **accuracy, precision, and recall** for the dataset.

**Concepts Covered:**

* Bayesian Network
* Medical Diagnosis
* Heart Disease Classification
* Accuracy
* Precision
* Recall

---

### 03 — kNN Classifier

**Dataset:** `titanic.csv`

> Write a program to implement the **k-Nearest Neighbors (kNN) classifier** for a sample training data set stored as a `.CSV` file. Compute the **accuracy of the classifier**, considering a few test data sets. Also calculate the **accuracy, precision, and recall** for the dataset.

**Concepts Covered:**

* k-Nearest Neighbors
* Feature Selection
* Data Preprocessing
* Classification
* Accuracy
* Precision
* Recall

---

### 04 — kNN Classifier

**Dataset:** `winequalityN.csv`

> Write a program to implement the **k-Nearest Neighbors (kNN) classifier** for a sample training data set stored as a `.CSV` file. Compute the **accuracy of the classifier**, considering a few test data sets. Also calculate the **accuracy, precision, and recall** for the dataset.

**Concepts Covered:**

* k-Nearest Neighbors
* Data Preprocessing
* Feature Scaling
* Classification
* Accuracy
* Precision
* Recall

---

### 05 — Naïve Bayes vs kNN

**Dataset:** `customer_churn.csv`

> Write a program to implement the **Naïve Bayesian classifier and the kNN classifier** for a sample training data set stored as a `.CSV` file. Compute the **accuracy of both classifiers**, considering a few test data sets and compare both algorithms. Also calculate the **accuracy, precision, and recall** for the dataset.

**Concepts Covered:**

* Naïve Bayes
* k-Nearest Neighbors
* Algorithm Comparison
* Classification
* Accuracy
* Precision
* Recall

---

### 06 — Naïve Bayes & kNN with User Input

**Dataset:** `winequalityN.csv`

> Write a program to implement the **Naïve Bayesian classifier and the kNN classifier** for a sample training data set stored as a `.CSV` file. Also compute **performance metrics** for the algorithms and **predict the outcome for user input**.

**Concepts Covered:**

* Naïve Bayes
* k-Nearest Neighbors
* Performance Evaluation
* User Input Prediction
* Classification

---

## 🧠 Algorithms Covered

| Algorithm                    |   Practicals   |
| ---------------------------- | :------------: |
| 🧮 Naïve Bayes               |   Q1, Q5, Q6   |
| 📍 k-Nearest Neighbors (kNN) | Q3, Q4, Q5, Q6 |
| 🕸️ Bayesian Network         |       Q2       |

---

## 📊 Evaluation Metrics

The practicals use the following classification performance metrics:

* **Accuracy** — Overall proportion of correctly classified samples.
* **Precision** — Proportion of predicted positive samples that are actually positive.
* **Recall** — Proportion of actual positive samples correctly identified.

### Formulas

**Accuracy**

```text
Accuracy = (TP + TN) / (TP + TN + FP + FN)
```

**Precision**

```text
Precision = TP / (TP + FP)
```

**Recall**

```text
Recall = TP / (TP + FN)
```

Where:

* `TP` = True Positive
* `TN` = True Negative
* `FP` = False Positive
* `FN` = False Negative

---

## 📁 Repository Structure

```text
AI-ML-Practical/
│
├── Q01/
│   ├── pima_indian.csv
│   └── Q01.ipynb
│
├── Q02/
│   ├── heart.csv
│   └── Q02.ipynb
│
├── Q03/
│   ├── titanic.csv
│   └── Q03.ipynb
│
├── Q04/
│   ├── winequalityN.csv
│   └── Q04.ipynb
│
├── Q05/
│   ├── customer_churn.csv
│   └── Q05.ipynb
│
├── Q06/
│   ├── winequalityN.csv
│   └── Q06.ipynb
│
└── README.md
```

> The exact folder and file names may vary depending on the repository structure.

---

## 🛠️ Technologies & Libraries

The practicals are implemented using **Python** and Jupyter Notebook.

### Main Libraries

* 🐍 Python
* 📓 Jupyter Notebook
* 🐼 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-learn
* 🕸️ pgmpy — for Bayesian Network implementation

---

## 🔬 Practical Workflow

Most classification practicals follow a common machine-learning workflow:

```text
        CSV Dataset
             │
             ▼
    Data Preprocessing
             │
             ▼
    Feature & Target Selection
             │
             ▼
    Train / Test Split
             │
             ▼
    Model Training
             │
       ┌─────┴─────┐
       ▼           ▼
  Naïve Bayes     kNN
       │           │
       └─────┬─────┘
             ▼
       Model Prediction
             │
             ▼
   Performance Evaluation
             │
       ┌─────┼─────┐
       ▼     ▼     ▼
   Accuracy Precision Recall
```

---

## 📋 Practical Overview

|  Q.No. | Dataset              | Algorithm / Model | Main Task                 |
| :----: | -------------------- | ----------------- | ------------------------- |
| **01** | `pima_indian.csv`    | Naïve Bayes       | Classification & Accuracy |
| **02** | `heart.csv`          | Bayesian Network  | Heart Disease Diagnosis   |
| **03** | `titanic.csv`        | kNN               | Classification & Metrics  |
| **04** | `winequalityN.csv`   | kNN               | Classification & Metrics  |
| **05** | `customer_churn.csv` | Naïve Bayes + kNN | Algorithm Comparison      |
| **06** | `winequalityN.csv`   | Naïve Bayes + kNN | Metrics & User Prediction |

---

## 🎯 Learning Objectives

Through these practicals, the following concepts are explored:

* Understanding **supervised machine learning**
* Implementing **Naïve Bayes classification**
* Implementing **k-Nearest Neighbors**
* Constructing a **Bayesian Network**
* Performing **data preprocessing**
* Splitting datasets into training and testing sets
* Feature encoding and scaling
* Making predictions using trained models
* Evaluating classification models
* Calculating **Accuracy, Precision, and Recall**
* Comparing different machine-learning algorithms
* Performing predictions using **user-provided input**

---

## 👨‍💻 Author

**Gami Abhay Sureshbhai**

MSc IT — AI & ML Practical Exercise

---

⭐ **If you find this repository useful, consider giving it a star!**
