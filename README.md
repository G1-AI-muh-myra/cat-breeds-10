# Cat Breed Classification Using Deep Learning

A comparative analysis of ResNet50, DenseNet121 and MobileNetV3Small architectures for multi-class cat breed classification.-


## Project Overview
Course : ISB46703 - Principle of Artificial Intelligence
Presenters:- 
1.  Muhammad bin Iskandar (52213224369)
2.  Myra Jasmeen Daniella Binti Bakar Jamili (52213224398)
Task Type: Multi-class Image Classification
Number of Classes: 10 Cat Breeds



## Dataset Information

### Classes in Dataset (Balanced - 500 images each):

# Breed Name (No. of Images) 
1 Abyssinian: 500
2 Bombay: 500
3 Egyptian Mau: 500
4 Exotic Shorthair: 500
5 Himalayan: 500
6 Maine Coon: 500
7 Russian Blue: 500
8 Scottish Fold: 500
9 Siamese: 500
10 Sphynx: 500

Total Images: 5,000

---

##  Model Performance Comparison

Architecture: 
Test Accuracy | mAP | Training Time (minutes) |
DenseNet121: 
94.8% | 99.0% | 69.60
ResNet50: 
95.6% | 98.9% | 71.68
MobileNetV3Small: 
17.2% | 12.0% | 9.54

###  Best Model Selection: **ResNet50**

- Highest Test Accuracy (95.6%)
- High mAP (98.9)
- Slightly lower mAP than DenseNet121
- Long training time (Downside)

---

## Technical Specifications

### Models Compared:

Model: 
1. Architecture Type
2. Key Features
ResNet50: 
1. Residual Network
2. 50 layers, skip connections for gradient flow 
DenseNet121: 
1. Densely Connected CNN
2. 121 layers, feature reuse across layers 
MobileNetV3Small:
1. Mobile-Optimized
2. Lightweight, efficient for edge devices 

### Evaluation Metrics:

- **Test Accuracy**: Percentage of correctly classified images
- **mAP (mean Average Precision)**: Harmonic mean of precision and recall across all classes

---

## Generated Visualizations

### Dataset Graphs:
1. `class_distribution.png` - Bar chart showing balanced class distribution
2. `sample_cat_breeds.png` - 50-image grid visualization (1600×2000px)

### Training Graphs:
- Accuracy curves for all 3 models
- Loss curves for all 3 models

---

## Setup & Installation

```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/cat-breed-classification.git

# Install dependencies
pip install tensorflow keras matplotlib numpy pillow scikit-learn

# Run the notebook
jupyter notebook cat_breed_classification.ipynb
