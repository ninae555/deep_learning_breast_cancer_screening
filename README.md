## Classification of Breast Histopathology Images using Convolutional Neural Networks (CNN)
#### Data Science, Columbian College of Arts & Sciences, George Washington University
#### Nina Ebensperger, Muhannad Alwhebie, Nammin Woo

Breast cancer is one of the leading causes of death among women worldwide. Early and accurate detection plays a vital role in improving patient outcomes and survival rates. Histopathology, the microscopic examination of breast tissue samples, is a fundamental diagnostic tool for identifying and classifying breast cancer. However, the manual analysis of histopathology images is a labor-intensive and time-consuming task prone to human error.

In recent years, advancements in machine learning and deep learning techniques have shown promising results in automating the analysis of histopathology images. Convolutional Neural Networks (CNNs), a type of deep learning algorithm specifically designed for image analysis, have demonstrated remarkable success in various computer vision tasks. Leveraging CNNs for the automated classification of breast histopathology images holds immense potential for improving diagnostic accuracy, reducing subjectivity, and enhancing the efficiency of cancer detection.

In this project, the focus is on developing a robust CNN model for the classification of breast histopathology images using the dataset sourced from Kaggle's "Breast Histopathology Images" collection. By training a CNN on this dataset, the goal is to create a reliable system capable of distinguishing between benign and malignant breast tissue samples.

Specifically, the 162 whole-mount slide images of Breast Cancer (BCa) specimens scanned at 40x, sourced from the Cancer Genome Atlas (TCGA), Invasive Ductal Carcinoma (IDC), is used for training and test the suggested model.

Through this endeavor, the aim is to contribute to the field of medical image analysis by developing a powerful CNN model that can assist pathologists in making accurate and efficient diagnoses. By automating the classification process, the project aims to provide valuable support to medical professionals, ultimately improving patient outcomes and advancing the fight against breast cancer.

*This topic was origined from Kaggle

### <u> Summary of Final model  </u>

**VGG16 with freezing pretrained layers have been chosen as Final model.**

1. The test score predicting Cancer tissues was the highest out of all models.​

2. While the F1 score did not out-perform the score of the RESNet, the recall and the precision were still out-performing that of the RESNet. ​

3. Model Robustness: The gap between the training and validation tests were smaller with VGG16 than in RESNet meaning VGG16 has more consistent performance. ​

4. Model Complexity: VGG16 is the least complex with having less parameters to train
