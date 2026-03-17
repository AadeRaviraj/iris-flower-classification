#  Iris Flower Classification — Decision Tree Case Study

A complete end-to-end machine learning project that classifies iris flowers into three species using a **Decision Tree Classifier**. This project follows a structured, step-by-step ML workflow — from loading raw data all the way to evaluating model performance.

---

##  Problem Statement

Given four physical measurements of an iris flower, can a machine learning model correctly identify which species it belongs to?

The three species are:
- **Setosa**
- **Versicolor**
- **Virginica**

---

##  Project Workflow

This project is broken into **10 clear steps**:

| Step | Description |
|------|-------------|
| 1 | Load the dataset from a CSV file |
| 2 | Exploratory Data Analysis (EDA) — shape, columns, missing values, class distribution |
| 3 | Define Independent (X) and Dependent (Y) variables |
| 4 | Visualize the data using a scatter plot |
| 5 | Split data into Training and Testing sets (50/50 split) |
| 6 | Build the Decision Tree model using Gini criterion |
| 7 | Train the model on training data |
| 8 | Run predictions on test data |
| 9 | Evaluate performance — Accuracy, Confusion Matrix, Classification Report |
| 10 | Visualize the Confusion Matrix |

---

##  Dataset

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

##  Model Details

| Parameter | Value |
|-----------|-------|
| Algorithm | Decision Tree Classifier |
| Criterion | Gini Impurity |
| Max Depth | 5 |
| Train/Test Split | 80% / 20% |
| Library | scikit-learn |

---

##  Evaluation Metrics

The model is evaluated using:
-  **Accuracy Score** — overall correctness of predictions
-  **Confusion Matrix** — breakdown of correct vs incorrect predictions per class
-  **Classification Report** — Precision, Recall, and F1-Score per class
-  **Visual Confusion Matrix** — plotted using `ConfusionMatrixDisplay`

---

##  Visualization

**Scatter Plot** — Petal Length vs Petal Width, color-coded by species, showing how naturally separable the classes are.

**Confusion Matrix Plot** — Visual heatmap showing where the model predicted correctly and where it made errors.

---

##  Tech Stack

- **Python 3**
- **pandas** — data loading and analysis
- **matplotlib** — plotting and visualization
- **seaborn** — (imported for extended visualization support)
- **scikit-learn** — model building, training, and evaluation

---

##  How to Run

1. Clone this repository
2. Make sure `iris.csv` is in the same folder as the script
3. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
4. Run the script:
   ```bash
   python iris_classification.py
   ```

---

##  Key Concepts Covered

- Supervised Machine Learning
- Multi-class Classification
- Exploratory Data Analysis (EDA)
- Feature Selection
- Train/Test Split
- Decision Tree (Gini Criterion)
- Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
- Data Visualization

---

##  Author

Built as part of a **Machine Learning Case Study** to understand the full pipeline of a classification problem — from raw data to model evaluation.
