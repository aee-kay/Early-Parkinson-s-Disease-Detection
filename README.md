# Early-Parkinson-s-Disease-Detection Using Machine Learning

## Overview

This project aims to detect Parkinson's Disease using various machine learning models. It utilizes a dataset from the UCI Machine Learning Repository and employs several classification algorithms to predict the presence or absence of the disease.

## Dataset

**Dataset Used:** Parkinson's Disease Dataset

**Dataset Source:** UCI Machine Learning Repository

**Dataset Hosting URL:** https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/parkinsons.data

## Methodology

1. **Data Collection:** The dataset is downloaded from the UCI Machine Learning Repository and loaded into a Pandas DataFrame.
2. **Data Preprocessing:** Redundant columns are dropped, and the dataset is checked for duplicates and missing values. The 'status' column is converted to a more memory-efficient data type.
3. **Exploratory Data Analysis:** Various visualizations like heatmaps, box plots, and pair plots are used to understand the relationships between features and the target variable.
4. **Balancing Dataset:** The dataset is balanced using the SMOTE technique to address the imbalance between Parkinson's and non-Parkinson's samples.
5. **Machine Learning Model Training:** Several classification models are trained, including:
    - Decision Tree Classifier
    - Random Forest Classifier
    - Logistic Regression
    - SVM
    - Naive Bayes
    - KNN Classifier
    - XGBoost Classifier
6. **Model Evaluation:** The models are evaluated using metrics like accuracy, precision, recall, F1-score, and R2-score. Confusion matrices and ROC curves are also generated.
7. **Comparison Table:** A comparison table is created to summarize the performance of different models.

## Results

The project demonstrates the effectiveness of various machine learning models in detecting Parkinson's Disease. The comparison table provides insights into the strengths and weaknesses of each model.

## Usage

1. Clone the repository.
2. Install the necessary libraries mentioned in the code.
3. Run the Jupyter Notebook to execute the code.

## Contributors

1. Anshul Kumar 
2. Akshat Singhal
3. Lakshay Kumar 
4. Avish Dharmawat
5. Keshav 

## License

This project is licensed under the MIT License.

## Acknowledgments

We acknowledge the UCI Machine Learning Repository for providing the dataset used in this project.
