# Healthcare Data Analytics using PySpark

## Introduction
Healthcare systems produce an enormous volume of data every day, ranging from patient records to operational metrics. Unfortunately, a significant portion of this data goes underutilized because of the difficulties in processing and analyzing large datasets. This project seeks to derive valuable insights from healthcare data using tools like PySpark, ultimately enhancing patient care and improving system efficiency.

### Objective
This project aims to analyze extensive healthcare data to uncover patterns and trends as an application of the Big Data Analytics tool, **PySpark**. By doing so, it will provide actionable insights that can improve the accuracy of diagnoses, treatment plans, and overall healthcare management.

### Scope
This project showcases how Big Data Analytics can be utilized to process and analyze healthcare data. The emphasis is on using machine learning models to predict medical conditions and identify trends. Scalability is achieved through the use of distributed computing frameworks, making this method ideal for real-world, large-scale applications.

## Abstract
Healthcare is a sector that generates enormous amounts of data daily. Unfortunately, much of this data is underutilized due to its sheer volume and complexity. However, it has the potential to significantly reduce negative patient outcomes and streamline processes to reveal important patterns. This project leverages Big Data Analytics with PySpark to process large healthcare datasets. It showcases the scalable and efficient application of machine learning models like **Logistic Regression, Multilayer Perceptron (MLP), and XGBoost** to predict disease prevalence and analyze trends in the most affected conditions. The methodology, results, and suggestions for future improvements offer a thorough framework for data-driven decision-making in healthcare.

## Problem Statement
The healthcare industry encounters numerous challenges, such as the underuse of extensive data and the struggle to identify patterns within intricate datasets. This project aims to tackle these problems by efficiently managing healthcare data and employing machine learning models to reveal patterns and trends. The issue can be summarized as:

> **Managing large-scale healthcare data to identify trends and uncover patterns among medical conditions using various SparkML models.**

## Dataset Characteristics
The dataset used in this project contains approximately 3,000 patient records collected from medical institutions. It includes 26 features, such as PatientID, Age, Cholesterol, Hemoglobin, Platelets, and various blood-related metrics. The target variable, "Disease," represents five distinct medical conditions. This dataset provides a comprehensive foundation for analyzing patient health and predicting medical outcomes.
The dataset used is derived from Kaggle's Blood Samples Dataset and modified to have PatientID and Age, and split into halves for demonstration of joining of datasets in pyspark.

## Technology Stack
| Component               | Technology Used           |
|------------------------|-------------------------|
| **Programming Language** | Python                   |
| **Big Data Framework**  | Apache Spark (PySpark)   |
| **Machine Learning**    | Spark MLlib, XGBoost     |
| **Data Storage**       | HDFS / Local File System |
| **Visualization**      | Matplotlib, Seaborn      |
| **Development**        | Jupyter Notebook         |

## Acknowledgments
- Apache Spark Documentation
- PySpark API Reference
- Machine Learning with PySpark: Practical Guide
- Kaggle Blood Samples Dataset for Disease Prediction
