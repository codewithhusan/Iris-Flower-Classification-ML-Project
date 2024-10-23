# Iris Flower Classification - Supervised Machine Learning Project

## 🌟Overview
This project focuses on building a supervised machine learning model to classify iris species based on their physical features such as sepal and petal length/width. The model is trained using the classic **Iris dataset**, which is widely used in pattern recognition and classification tasks.

## 💻Dataset
The dataset used is the Iris dataset, which contains 150 records of iris flowers, with the following features:
- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**
- **Species** (target variable: Setosa, Versicolor, or Virginica)

## 🔍Key Features
- **Data Preprocessing**:
  - Loaded and explored the dataset using Pandas.
  - Normalized the feature data for better model performance.
  - Split the dataset into training and testing sets.
  
- **Model Development**:
  - Implemented multiple classification algorithms such as:
    - **Logistic Regression**
    - **Decision Trees**
    - **Support Vector Machines (SVM)**
  - Evaluated models based on accuracy and confusion matrix.

- **Performance**:
  - Achieved a classification accuracy of 1.0 on the test set.
  - The model predicts the iris species with high accuracy by learning from the features.

- **Visualization**:
  - Visualized feature relationships through count plots and decision trees.
  - Visualized decision boundaries and feature importance for model interpretability.

## 🎯Project Structure
- **Final_project_SML.ipynb**: The Jupyter Notebook containing the entire code for loading data, preprocessing, model training, evaluation, and visualization.
- **Iris.csv**: The Iris dataset
  
## 🛠️How to Use
1. Clone or download the repository.
2. Open the `Final_project_SML.ipynb` file in Jupyter Notebook.
3. Run the cells step by step to see the data preprocessing, model training, and performance evaluation.
4. Explore the visualizations and decision boundaries generated in the notebook.

## 📊Results
- The model successfully classifies iris species with a high degree of accuracy.
- The most significant features for classification were **Petal Length** and **Petal Width**, as indicated by feature importance analysis.

## 🔧Libraries and Tools
- **Python 3.x**
- **Pandas** for data manipulation
- **Scikit-Learn** for machine learning algorithms
- **Matplotlib** and **Seaborn** for data visualization

## 👋 Conclusion
This project demonstrates how machine learning algorithms can be applied to a well-known dataset to achieve meaningful results. The Iris dataset is simple yet effective for demonstrating the basics of supervised learning, from data preprocessing to model evaluation.
