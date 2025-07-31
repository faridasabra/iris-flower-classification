---

# Iris Flower Classification

This project focuses on developing a machine learning model to classify iris flowers into their respective species based on specific measurements.

## Project Description

The **Iris Flower Classification** project aims to build a machine learning model capable of accurately identifying the species of iris flowers (setosa, versicolor, and virginica) based on their **sepal length, sepal width, petal length, and petal width** measurements. This project automates the classification process, offering a practical solution for identifying iris species.

## Dataset

The **Iris dataset** consists of 150 rows and 6 columns, including length and width measurements of sepal and petal for different species in centimeters. The dataset is clean, with **no duplicate or null values**.

**Columns:**
* `Id` (dropped during preprocessing)
* `SepalLengthCm`
* `SepalWidthCm`
* `PetalLengthCm`
* `PetalWidthCm`
* `Species`

## Data Manipulation

The initial `Id` column is dropped as it's not needed for the classification task.

## Machine Learning Models

The project explores and trains several machine learning models for classification:

* **Support Vector Machine (SVM)**
* **Logistic Regression**
* **Decision Tree**
* **K-Nearest Neighbors (KNN)**
* **Naive Bayes**

The project includes steps for:
* Data exploration and visualization (e.g., box plots, joint plots, pair plots, heatmaps for correlation).
* Splitting data into training and testing datasets.
* Feature scaling (Standard Scaler).
* Label encoding for categorical variables.
* Model training and evaluation (accuracy scores, confusion matrix, classification report).

## Conclusion

The tuned **Random Forest model** was selected as the final prediction model in a similar project referenced in the search results, demonstrating strong performance in classifying Iris species. This project provides valuable insights into feature importance for species differentiation and has potential applications in botany, horticulture, and environmental monitoring.

---

## Getting Started

To run this project, you'll typically need to:
1.  **Clone the repository.**
2.  **Install the required Python packages** (e.g., pandas, seaborn, matplotlib, scikit-learn).
3.  **Execute the Jupyter Notebook** to replicate the analysis and model training.
