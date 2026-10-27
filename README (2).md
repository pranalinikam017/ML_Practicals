# 🤖 ML-Experiments

A hands-on collection of **11 machine learning experiments** covering the full workflow: data preprocessing, exploratory analysis, classification, regression, clustering, dimensionality reduction, and neural networks. Each experiment lives in its own folder with a Jupyter notebook and the dataset it uses.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Experiments at a Glance](#-experiments-at-a-glance)
- [Project Structure](#-project-structure)
- [Experiment Details](#-experiment-details)
- [Getting Started](#-getting-started)
- [Tech Stack](#-tech-stack)
- [Key Learnings](#-key-learnings)
- [Contributing](#-contributing)

---

## 🔍 Overview

This repository documents my machine learning learning journey through practical, end-to-end notebooks. Every experiment follows a similar flow:

1. Load and inspect the dataset
2. Clean and preprocess the data
3. Visualize and understand patterns
4. Train one or more models
5. Evaluate and compare results

It is meant as both a personal reference and a starting point for anyone learning core ML algorithms.

---

## 📊 Experiments at a Glance

| # | Experiment | Task | Technique / Algorithm | Dataset |
|---|-----------|------|-----------------------|---------|
| 01 | [Data Preprocessing](./01_Data_Preprocessing) | Data cleaning | Missing values, encoding, scaling | `Employee.csv` |
| 02 | [Exploratory Data Analysis](./02_Exploratory_Data_Analysis) | EDA | Statistical summaries, visualization | `Titanic.csv` |
| 03 | [Wine Classification + PCA](./03_Wine_Classification_PCA) | Classification | PCA dimensionality reduction | `Wine.csv` |
| 04 | [Diabetes Classification](./04_Diabetes_Classification) | Classification | Logistic Regression | `diabetes.csv` |
| 05 | [SVM – Social Network Ads](./05_SVM_Social_Network_Ads) | Classification | Support Vector Machine | `Social_Network_Ads.csv` |
| 06 | [Iris Classification (KNN)](./06_Iris_Classification_KNN) | Classification | K-Nearest Neighbors | `Iris.csv` |
| 07 | [Insurance Regression](./07_Insurance_Regression) | Regression | Regression model comparison | `insurance.csv` |
| 08 | [Car Classification](./08_Car_Classification) | Classification | Classification models | `car_dataset.csv` |
| 09 | [House Price Prediction](./09_House_Prediction) | Regression | Regression | `USA_Housing.csv` |
| 10 | [Customer Segmentation](./10_Customer_Segmentation) | Clustering | Unsupervised clustering | `Mall_Customers.csv` |
| 11 | [Iris Classification (ANN)](./11_Iris_Classification_ANN) | Classification | Artificial Neural Network | `iris.data` |

---

## 📁 Project Structure

```
ML-Experiments/
│
├── 01_Data_Preprocessing/
│   ├── Data_Preprocessing.ipynb
│   ├── Employee.csv
│   └── Employee_cleaned.csv
│
├── 02_Exploratory_Data_Analysis/
│   ├── EDA.ipynb
│   └── Titanic.csv
│
├── 03_Wine_Classification_PCA/
│   ├── Wine_Classification_PCA.ipynb
│   └── Wine.csv
│
├── 04_Diabetes_Classification/
│   ├── Diabetes_Logistic_Regression.ipynb
│   └── diabetes.csv
│
├── 05_SVM_Social_Network_Ads/
│   ├── SVM.ipynb
│   └── Social_Network_Ads.csv
│
├── 06_Iris_Classification_KNN/
│   ├── Iris_KNN.ipynb
│   └── Iris.csv
│
├── 07_Insurance_Regression/
│   ├── Regression_Comparison.ipynb
│   └── insurance.csv
│
├── 08_Car_Classification/
│   ├── Car_Classification.ipynb
│   └── car_dataset.csv
│
├── 09_House_Prediction/
│   ├── House_Prediction.ipynb
│   └── USA_Housing.csv
│
├── 10_Customer_Segmentation/
│   ├── Customer_Segmentation.ipynb
│   └── Mall_Customers.csv
│
├── 11_Iris_Classification_ANN/
│   ├── Iris_ANN.ipynb
│   └── iris.data
│
└── README.md
```

---

## 🧪 Experiment Details

### 01 · Data Preprocessing
Cleans a raw employee dataset and prepares it for modeling: handling missing values, encoding categorical features, and scaling numerical ones.
- **Input:** `Employee.csv`
- **Output:** `Employee_cleaned.csv`

### 02 · Exploratory Data Analysis
Explores the **Titanic dataset** through summary statistics and visualizations to uncover distributions, correlations, and outliers, and to see which factors relate to passenger survival.
- **Dataset:** `Titanic.csv`

### 03 · Wine Classification with PCA
Classifies wine types from their chemical properties and applies **Principal Component Analysis (PCA)** to reduce dimensionality and visualize class separation.
- **Dataset:** `Wine.csv`

### 04 · Diabetes Classification
Predicts whether a patient has diabetes from diagnostic measurements using **Logistic Regression**.
- **Dataset:** `diabetes.csv`

### 05 · SVM on Social Network Ads
Uses a **Support Vector Machine** to predict whether a user purchases a product after seeing a social network advertisement.
- **Dataset:** `Social_Network_Ads.csv`

### 06 · Iris Classification with KNN
Classifies iris flower species using the **K-Nearest Neighbors** algorithm.
- **Dataset:** `Iris.csv`

### 07 · Insurance Cost Regression
Predicts medical insurance charges and **compares multiple regression models** to find the best performer.
- **Dataset:** `insurance.csv`

### 08 · Car Classification
Applies classification techniques to categorize cars based on their attributes.
- **Dataset:** `car_dataset.csv`

### 09 · House Price Prediction
Predicts house prices from features such as income, house age, rooms, and population using regression.
- **Dataset:** `USA_Housing.csv`

### 10 · Customer Segmentation
Groups mall customers into segments using **unsupervised clustering**, helping identify distinct customer profiles for targeted marketing.
- **Dataset:** `Mall_Customers.csv`

### 11 · Iris Classification with ANN
Builds an **Artificial Neural Network** to classify iris species, offering a contrast to the classical KNN approach in experiment 06.
- **Dataset:** `iris.data`

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/pranalinikam017/ML-Experiments.git
cd ML-Experiments

# 2. (Optional) create a virtual environment
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

### Running an experiment

```bash
cd 04_Diabetes_Classification
jupyter notebook Diabetes_Logistic_Regression.ipynb
```

> 💡 Each notebook reads its dataset from its own folder, so run notebooks from inside the experiment directory.

---

## 🛠 Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Data handling | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine learning | scikit-learn |
| Deep learning | TensorFlow / Keras |
| Environment | Jupyter Notebook |

---

## 🎯 Key Learnings

- Preparing raw data: cleaning, encoding, and scaling
- Using EDA to guide modeling decisions
- Reducing dimensionality with PCA
- Building and evaluating classifiers: Logistic Regression, SVM, KNN, ANN
- Comparing regression models using standard metrics
- Discovering structure in unlabeled data with clustering

---

## 🤝 Contributing

Suggestions and improvements are welcome:

1. Fork the repository
2. Create a branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m "Add improvement"`)
4. Push the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 👤 Author

**Pranali Nikam**
- GitHub: [@pranalinikam017](https://github.com/pranalinikam017)

⭐ If you found this repository helpful, consider giving it a star!
