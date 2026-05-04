# Brain Tumor Detection using CNN

## Overview

This project applies a Convolutional Neural Network (CNN) to classify brain MRI images into two categories: tumor and non-tumor. The model is designed to assist in automated medical image analysis by identifying the presence of brain tumors from MRI scans.

## Objective

The main goal of this project is to build a deep learning model that can accurately distinguish between:

* 0 → No Tumor
* 1 → Tumor

This supports early detection and decision-making in medical diagnosis.

## Data Source

The dataset used in this project is publicly available on Kaggle:

Brain MRI Images for Brain Tumor Detection
https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

The dataset contains MRI images organized into two classes:

* "yes" → Tumor present
* "no" → No tumor

## Methodology

1. Data Loading

   * Dataset loaded directly from Kaggle using kagglehub

2. Data Preprocessing

   * Image resizing to 224×224
   * Normalization (pixel values scaled between 0 and 1)
   * Train/validation split (70% / 30%)

3. Model Architecture

   * Convolutional layers for feature extraction
   * MaxPooling layers for dimensionality reduction
   * Fully connected layers for classification
   * Sigmoid activation for binary output

4. Model Training

   * Optimizer: Adam
   * Loss Function: Binary Crossentropy
   * Evaluation Metric: Accuracy

5. Model Evaluation

   * Classification Report (Precision, Recall, F1-score)
   * Prediction probability visualization
   * Comparison between true and predicted labels

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* KaggleHub

## Results

The model achieved a validation accuracy of XX%.

Evaluation was performed using:
- Precision, Recall, and F1-score  
- Prediction probability visualization  

These results reflect the model’s performance in distinguishing between tumor and non-tumor MRI images.

## How to Run

1. Install required libraries:
   pip install tensorflow numpy matplotlib scikit-learn kagglehub

2. Run the notebook:
   Open the project file and execute all cells

3. The dataset will be downloaded automatically from Kaggle

## Project Structure

* main.ipynb → Full implementation of the model
* Dataset → Loaded automatically from Kaggle

## Future Improvements

* Improve model accuracy using data augmentation
* Experiment with deeper CNN architectures
* Add ROC curve and confusion matrix visualization

## Author

Suahil – AI System Engineering Student

