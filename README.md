## Classification of Breast Histopathology Images using Convolutional Neural Networks (CNN)
#### Data Science, Columbian College of Arts & Sciences, George Washington University
#### Nina Ebensperger, Muhannad Alwhebie, Nammin Woo

This project aimed to develop a robust CNN model for the classification of breast histopathology images. By leveraging advancements in machine learning and deep learning techniques, the goal was to create a reliable system capable of distinguishing between benign and malignant breast tissue samples, ultimately improving diagnostic accuracy and efficiency in cancer detection.

The project used the dataset sourced from Kaggle's "Breast Histopathology Images" collection, specifically focusing on the 162 whole-mount slide images of Breast Cancer (BCa) specimens scanned at 40x, sourced from the Cancer Genome Atlas (TCGA), Invasive Ductal Carcinoma (IDC). This dataset was used for training and testing the suggested models.

The team explored multiple models for classification, including RESNet50, EfficientNetB7, and VGG16. Each model had different numbers of parameters, freeze options, and learning rates. The models were evaluated based on various metrics such as accuracy, precision, recall, F1 score, and precision for non-cancer samples.

### Findings

After thorough experimentation and analysis, VGG16 with freezing pretrained layers was chosen as the final model. The decision was based on several factors:

Test Score: VGG16 achieved the highest test score for predicting cancer tissues among all the models. This indicates that the model performed well in accurately classifying the breast histopathology images.

Precision and Recall: Although the F1 score of VGG16 did not outperform RESNet50, the precision and recall of VGG16 were superior. Precision and recall are crucial metrics in medical diagnosis, as they indicate the ability to minimize false positives and false negatives, respectively.

Model Robustness: VGG16 exhibited a smaller gap between the training and validation tests compared to RESNet50. This suggests that VGG16 had more consistent performance and was less prone to overfitting the training data.

Model Complexity: VGG16 was the least complex model among the options considered, with fewer parameters to train. This factor can contribute to faster training times and potentially better generalization on unseen data.

In conclusion, the project successfully developed a powerful CNN model using VGG16 with freezing pretrained layers for the classification of breast histopathology images. This model showed promising results in terms of accuracy, precision, and recall, making it a suitable candidate for assisting pathologists in making accurate and efficient diagnoses.
