# KNN Classification on Breast Cancer Dataset

## 🎯 Problem Statement and Goal of Project

This project explores a foundational classification task using the **K-Nearest Neighbors (KNN)** algorithm on the widely used **Breast Cancer dataset** from `scikit-learn`.
The primary goal is to understand the behavior of KNN in distinguishing between **malignant** and **benign** tumors based on numerical features derived from digitized images of breast mass tissue.

---

## 🛠 Solution Approach

The notebook follows a clean ML workflow:

1. **Data Loading**: Load breast cancer data via `sklearn.datasets.load_breast_cancer()`.
2. **Exploratory Data Analysis**:

   * View data shape, features, and class distributions.
   * Use `seaborn` for basic visualization.
3. **Train-Test Split**:

   * Split dataset into training and test sets (80/20).
4. **Modeling with KNN**:

   * Apply `KNeighborsClassifier` from `sklearn.neighbors`.
   * Test different `k` values (number of neighbors).
5. **Evaluation**:

   * Accuracy evaluation.
   * Confusion matrix plotting.
   * Error rate plot vs. `k`.

---

## 🧰 Technologies & Libraries

* Python 3
* `numpy`, `pandas` – numerical computing and data manipulation
* `seaborn`, `matplotlib` – visualization
* `scikit-learn` – datasets, model training, evaluation

---

## 📁 Dataset Description

* **Source**: `sklearn.datasets.load_breast_cancer()`
* **Features**: 30 real-valued features (e.g., mean radius, texture, smoothness)
* **Target Classes**:

  * `0`: malignant
  * `1`: benign
* **Samples**: 569
* **Goal**: Predict whether a tumor is malignant or benign

---

## ⚙️ Installation & Execution Guide

1. Download or clone the repository.
2. Install required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Run the notebook:

   ```bash
   jupyter notebook knn.ipynb
   ```

---

## 📊 Key Results / Performance

* **Train/Test Split**: 80/20
* **KNN Accuracy**: Varies with `k`, best value selected via error rate plot
* **Visualization**:

  * Target distribution via `seaborn.countplot`
  * Confusion matrix for classification performance
  * Error vs. `k` plot to optimize hyperparameters

---

## 📸 Sample Outputs

* 📈 Error rate vs. `k` visualization
* ✅ Confusion matrix
* 📊 Class distribution plots

---

## 📚 Additional Learnings / Reflections

* Demonstrates clear understanding of:

  * The importance of choosing the right `k`
  * Effects of class imbalance
  * Train-test split strategy
* A practical and well-scaffolded implementation of KNN in binary classification.

---

## 👤 Author

## mehran Asgari

**Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com)
**GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari)

---

## 📄 License

This project is licensed under the Apache 2.0 License – see the `LICENSE` file for details.

---

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*

