# Iris Flower Classification — Decision Tree Case Study

![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Algorithm](https://img.shields.io/badge/Algorithm-Decision%20Tree-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A complete end-to-end machine learning project that classifies iris flowers into three species based on their physical measurements. The project uses a **Decision Tree Classifier** and follows a structured, step-by-step machine learning pipeline — from loading raw data all the way to evaluating model performance.

---

## Problem Statement

Given four physical measurements of an iris flower, can a machine learning model correctly identify which species it belongs to?

The three species are:

- Setosa
- Versicolor
- Virginica

---

## Project Workflow

This project is broken into 10 clear steps:

| Step | Description |
|------|-------------|
| 1 | Load the dataset from a CSV file |
| 2 | Exploratory Data Analysis — shape, columns, missing values, class distribution, statistical summary |
| 3 | Define Independent (X) and Dependent (Y) variables |
| 4 | Visualize the data using a scatter plot (Petal Length vs Petal Width) |
| 5 | Split data into Training and Testing sets (50% / 50%) |
| 6 | Build the Decision Tree model using Gini criterion with max depth of 5 |
| 7 | Train the model on training data |
| 8 | Run predictions on test data |
| 9 | Evaluate performance — Accuracy Score, Confusion Matrix, Classification Report |
| 10 | Visualize the Confusion Matrix using ConfusionMatrixDisplay |

---

## Dataset

**File:** `iris.csv`

**Features (Independent Variables - X):**
- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

**Target (Dependent Variable - Y):**
- `species` — the flower type (Setosa / Versicolor / Virginica)

**Total Samples:** 150 rows (50 per class)

---

## Model Details

| Parameter | Value |
|-----------|-------|
| Algorithm | Decision Tree Classifier |
| Criterion | Gini Impurity |
| Max Depth | 2 |
| Train/Test Split | 80% / 20% |
| Random State | 42 |
| Library | scikit-learn |

---

## Visualization

**Scatter Plot** — Petal Length vs Petal Width, color-coded by species. This plot clearly shows how naturally separable the three classes are, which makes it a great dataset for understanding classification.

**Confusion Matrix Plot** — A visual heatmap showing where the model predicted correctly and where it made errors, plotted using `ConfusionMatrixDisplay`.

---

## Evaluation Metrics

The model is evaluated using:

- **Accuracy Score** — overall percentage of correct predictions
- **Confusion Matrix** — breakdown of correct vs incorrect predictions per class
- **Classification Report** — Precision, Recall, and F1-Score per class

---

## Tech Stack

- Python 3
- pandas — data loading and analysis
- matplotlib — scatter plot and confusion matrix visualization
- seaborn — imported for extended visualization support
- scikit-learn — model building, training, and evaluation

---

## How to Run

1. Clone this repository
2. Place `iris.csv` in the same folder as the script
3. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
4. Run the script:
   ```bash
   python iris_classification.py
   ```

---

## Key Concepts Covered

- Supervised Machine Learning
- Multi-class Classification
- Exploratory Data Analysis (EDA)
- Feature Selection
- Train/Test Split
- Decision Tree (Gini Criterion)
- Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
- Data Visualization

---

## Author

**Raviraj Aade**

Built as part of a Machine Learning Case Study series to understand the complete pipeline of a classification problem — from raw data to model evaluation.
