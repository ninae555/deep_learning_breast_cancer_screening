# Classification of Breast Histopathology Images using CNN
**Data Science, Columbian College of Arts & Sciences, George Washington University**  
*Contributors: Nina Ebensperger, Muhannad Alwhebie, Nammin Woo*

The project harnesses the power of Convolutional Neural Networks to develop a dependable model for classifying breast histopathology images. With the advancements in deep learning, our aim was to distinguish between benign and malignant breast tissue samples, enhancing diagnostic precision in cancer detection.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Exploration](#model-exploration)
- [Findings](#findings)
- [Conclusion](#conclusion)

## Introduction
The core objective of this endeavor was to employ advanced machine learning and deep learning algorithms to build a trustworthy classification model for breast histopathology images.

## Dataset
We utilized the dataset from Kaggle's "Breast Histopathology Images" collection. Our focus was specifically on the 162 whole-mount slide images of Breast Cancer (BCa) specimens, scanned at 40x magnification, sourced from the Cancer Genome Atlas (TCGA), Invasive Ductal Carcinoma (IDC). This dataset played a crucial role in training and evaluating our models.

## Model Exploration
A variety of models were investigated for this classification task, including:
- RESNet50
- EfficientNetB7
- VGG16

Each model varied in terms of parameters, freezing options, and learning rates. Evaluation was based on metrics like accuracy, precision, recall, F1 score, and precision for non-cancer samples.

## Findings
Upon in-depth experimentation, VGG16 with freezing pretrained layers emerged as the chosen model, influenced by:
- **Test Score**: Superior test score in predicting cancer tissues.
- **Precision & Recall**: Important metrics in medical diagnosis; VGG16 showed better performance.
- **Model Robustness**: Smaller disparity between training and validation tests, suggesting less susceptibility to overfitting.
- **Model Complexity**: Fewer parameters meant potentially faster training and better generalization.

## Conclusion
The project's culmination was the successful creation of an effective CNN model (VGG16 with frozen pretrained layers) for classifying breast histopathology images. With an accuracy of 86.23%, the model shows great potential in assisting medical professionals in making accurate diagnoses.
