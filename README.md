# Iris Dataset Classification

## Overview
This project demonstrates classification techniques on the famous **Iris dataset**, a classic dataset for machine learning and data analysis. The goal is to classify iris species (Setosa, Versicolor, Virginica) based on sepal and petal dimensions using the following algorithms:

- k-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest (RF)
- Decision Tree (DTree)
- Gradient Boosting (GBoost)

## Dataset
The **Iris dataset** consists of 150 observations, each containing the following features:

- **Sepal Length** (cm)
- **Sepal Width** (cm)
- **Petal Length** (cm)
- **Petal Width** (cm)
- **Label**: Iris-setosa, Iris-versicolor, or Iris-virginica

The dataset is balanced, with 50 samples for each class.

## Objectives
- Explore and preprocess the Iris dataset.
- Apply various classification algorithms.
- Evaluate and compare the models' performance.

## Models and Methods

### 1. k-Nearest Neighbors (KNN)
- A simple, non-parametric method that uses proximity to classify data points.
- Performance tuned with different values of `k`.

### 2. Support Vector Machine (SVM)
- A supervised learning model that finds the optimal hyperplane for classification.
- Tested with linear and non-linear kernels.

### 3. Random Forest (RF)
- An ensemble learning method that builds multiple decision trees and combines their output.
- Parameters like the number of trees and maximum depth were tuned.

### 4. Decision Tree (DTree)
- A tree-based model that splits data using features to maximize information gain.
- Visualized for interpretability.

### 5. Gradient Boosting (GBoost)
- An iterative ensemble method that builds models sequentially to correct previous errors.
- Parameters like learning rate and number of estimators were fine-tuned.


## Dependencies
The project uses the following Python libraries:

- `pandas` for data manipulation.
- `numpy` for numerical computations.
- `matplotlib` for visualizations.
- `scikit-learn` for machine learning models and metrics.

## Usage
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```bash
   cd iris-classification
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   ```bash
   jupyter notebook Iris-KNN-SVM-RF-DTree-GBoost.ipynb
   ```

## Conclusion
This project highlights the effectiveness of various classification algorithms for the Iris dataset. Ensemble methods like Random Forest and Gradient Boosting achieved the highest accuracy, showcasing their robustness for small, structured datasets.
