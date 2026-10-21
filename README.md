# Machine Learning Practical Experiments

This repository contains practical implementations of Machine Learning and Data Science concepts using Python. The experiments cover data preprocessing, exploratory data analysis, regression, classification, clustering, dimensionality reduction, and a basic artificial neural network.

## Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Repository Structure

Each experiment is kept in its own folder with its dataset and Jupyter Notebook.

```text
ML_Practicals/
├── README.md
├── Classification_of_car_Using_ML_algorithms/
├── Customer_segmentation_Using_K-Means/
├── Data_preprocessing_using_python/
├── Diabetes_prediction_using_logistic_regression/
├── EDA_Using_python/
├── House_prediction_using_Linear_Regression/
├── Iris_classification_Using_Single_Layer_ANN/
├── Iris_classification_using_knn/
├── PCA_ Dimensionality_reduction/
├── SVM_Using_Social_Network_dataset/
└── Various_Regression_algorithm/
```

## Experiments

### 1. Classification of Car Using ML Algorithms
**Folder:** `Classification_of_car_Using_ML_algorithms`

Classifies cars using different Machine Learning algorithms and compares their performance.

### 2. Customer Segmentation Using K-Means
**Folder:** `Customer_segmentation_Using_K-Means`
**Dataset:** `Mall_Customers.csv`

Groups customers into clusters based on their characteristics and spending behaviour using the K-Means clustering algorithm.

### 3. Data Preprocessing Using Python
**Folder:** `Data_preprocessing_using_python`
**Dataset:** `Employee.csv`

Cleans and prepares raw data: handling missing values, removing duplicates, encoding categorical data, and scaling features.

### 4. Diabetes Prediction Using Logistic Regression
**Folder:** `Diabetes_prediction_using_logistic_regression`
**Dataset:** `diabetes.csv`

Predicts whether a person has diabetes from medical features using a Logistic Regression classifier.

### 5. Exploratory Data Analysis (EDA) Using Python
**Folder:** `EDA_Using_python`

Explores a dataset using descriptive statistics and visualizations to understand its patterns, distributions, and relationships.

### 6. House Price Prediction Using Linear Regression
**Folder:** `House_prediction_using_Linear_Regression`
**Dataset:** `USA_Housing.csv`

Predicts house prices from housing-related features using a Linear Regression model.

### 7. Iris Classification Using Single-Layer ANN
**Folder:** `Iris_classification_Using_Single_Layer_ANN`
**Dataset:** `Iris.csv`

Builds a simple single-layer artificial neural network to classify Iris flowers.

### 8. Iris Classification Using KNN
**Folder:** `Iris_classification_using_knn`
**Dataset:** `Iris.csv`

Classifies Iris flower species using the K-Nearest Neighbour algorithm.

### 9. PCA Dimensionality Reduction
**Folder:** `PCA_ Dimensionality_reduction`
**Dataset:** `Wine.xls`

Reduces the number of features of the Wine dataset using Principal Component Analysis while keeping the most important information, then classifies the wines using the reduced features.

### 10. SVM Using Social Network Dataset
**Folder:** `SVM_Using_Social_Network_dataset`

Classifies data from a social network dataset using a Support Vector Machine.

### 11. Various Regression Algorithms
**Folder:** `Various_Regression_algorithm`
**Dataset:** `insurance.csv`

Compares different regression algorithms on the insurance dataset to find which one predicts best.

## How to Run

1. Install the required libraries:

   ```bash
   python3 -m pip install numpy pandas matplotlib scikit-learn jupyter
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open an experiment folder and run its `.ipynb` notebook. Make sure the dataset file is in the same folder.

## Author

**Pranali Nikam**

**GitHub:** [pranalinikam017](https://github.com/pranalinikam017)
**Repository:** ML_Practicals
