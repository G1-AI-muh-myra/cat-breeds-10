# Cat Breed Images Classification with Convolutional Neural Networks (CNN)

## Description
This repository contains a comprehensive analysis of cat breed classification using various convolutional neural network (CNN) models. It is part of the project for the **ISB46703 - Principle of Artificial Intelligence** subject, focusing on dataset preparation, model performance evaluation, and improvement strategies. Detailed analysis of confusion matrices, training accuracy, and loss trends are included to provide comprehensive insights.

## Overview
Cat breed classification is a challenging task due to the subtle visual differences between breeds. This project employs three popular neural network architectures—**ResNet50**, **DenseNet121**, and **MobileNetV3Small**—to tackle this classification problem. The goal is to analyze their performance, identify areas for improvement, and suggest enhancements.

The selected domain for this project is **Animal subspecies**. The dataset is sourced from the Kaggle repository **'nikolasgegenava/cat-breeds'** (Top 10 classes by image count). The target dataset size is **~5,000 images**, with approximately **200-500 images per class** across ten cat breed classes:
- Abyssinian
- Bombay
- Egyptian Mau
- Exotic Shorthair
- Himalayan
- Maine Coon
- Russian Blue
- Scottish Fold
- Siamese
- Sphynx

## Contents
### Attached Files
`00_full_cat_breed_project_colab.ipynb`: Python notebook consisting of the full project implementation, including dataset downloading, dataset preparation, model training, model evaluation, graph visualization, confusion matrix analysis, and final model comparison.

### Confusion Matrix Analysis

Provides a visual summary of the three models. Highlights key metrics, such as correct classifications and misclassifications. Offers detailed insights into error patterns and potential biases in the model.

### Model Performance Comparison

Compares accuracy, mean average precision (mAP), and training times across the three models. Identifies the best performing model based on these metrics.

### Training Accuracy and Loss Trends

Examines the evolution of training and validation accuracy. Analyzes training and validation loss to understand overfitting or underfitting trends.

## Performance Metrics

The performance metrics are generated in the notebook after training the three models.

The results include:

- ResNet50 accuracy, mAP, and training time
- DenseNet121 accuracy, mAP, and training time
- MobileNetV3Small accuracy, mAP, and training time
- Model comparison table
- Confusion matrix analysis
- Training accuracy and loss trends

# Folder Structure


The notebook creates a local project folder structure:
```text
notebooks
└── AI-miniproject-3rd-FINAL
project_results/
├── dataset/
├── models/
├── raw_dataset/
└── results/
