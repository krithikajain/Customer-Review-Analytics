
# Semi-Supervised Learning with PySpark

## Overview
This project implements a semi-supervised learning workflow using PySpark. It processes text data from the `train.csv` file and performs iterative training with labeled and pseudo-labeled datasets to classify Amazon reviews.

## Features
- Preprocessing text data: cleaning, tokenization, stop words removal, and TF-IDF computation.
- Dimensionality reduction using PCA.
- Semi-supervised training with a Random Forest classifier.
- Iterative training with gradual integration of pseudo-labeled data.
- Evaluation of model performance using metrics such as accuracy, precision, recall, and a confusion matrix.

## Steps in the Code : provided in pseudo code file in pseudo code dir

## How to Run
1. Ensure PySpark is installed and configured on your system.
2. Place the `amazon.csv` file in the working directory.
3. Run the Python script using a Spark-enabled environment.

## Dependencies
- PySpark
- ML Lib and other standard libraries

## Outputs ( provided in report as well output dir)
- Model performance metrics: accuracy, precision, recall.
- Confusion matrix for test dataset evaluation.
- Processed datasets and intermediate results stored in the checkpoint directory.


