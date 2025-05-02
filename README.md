# Iris Flower Classification using K-Nearest Neighbors💐

## Introduction
This project demonstrates the application of the K-Nearest Neighbors (KNN) algorithm to classify iris flowers into three species (setosa, versicolor, and virginica) based on their sepal and petal measurements. The Iris dataset, a classic in machine learning, serves as the foundation for this analysis.

## Dataset🗄️
The Iris dataset consists of 150 samples, equally distributed among three iris species. Each sample includes four features:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
---
# Data Exploration and Visualization📊

## Data Shape and Distribution🔍

- Shape: The dataset comprises 150 rows (samples) and 5 columns (4 features + 1 target variable - species).
- Distribution: Each species (setosa, versicolor, virginica) has 50 samples, ensuring a balanced class distribution.

---

## Visualizations📈
- Pairplot: A pairplot was used to visualize the relationships between the features, revealing distinct clusters for each species, suggesting the suitability of KNN for this classification task.
- Boxplots: Boxplots were generated for each feature, grouped by species, to showcase the distribution of measurements and identify potential outliers.

--- 

# Model Building
## Data Splitting🪓
The dataset was split into training and testing sets using an 80/20 ratio:
- Training Set: 80% of the data (120 samples) used to train the KNN model.
- Testing Set: 20% of the data (30 samples) used to evaluate model performance.
  
---

## KNN Model🧮
A KNN classifier was trained with k=5, chosen based on the square root of the test set size. The model predicts the species of a new data point based on the majority class among its 5 nearest neighbors.

---

# Model Evaluation💯
## Metrics📏
- Accuracy: The model achieved an accuracy of 100% on the test set, indicating perfect classification.
- Confusion Matrix: A confusion matrix was generated to visualize the model's predictions against the actual species labels, revealing no misclassifications.
- Classification Report: A classification report provides precision, recall, and F1-score for each class, further confirming the model's exceptional performance.

---
# Conclusion🏁
The KNN model demonstrated exceptional performance in classifying iris flowers, achieving 100% accuracy on the test set. The selected value of k=5 proved to be effective for this dataset. The clear patterns in the features and balanced class distribution contributed to the model's success.
