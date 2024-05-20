# Breast_Cancer_Classificaton_Using_CNN

Objective: To build a breast cancer classifier on an IDC dataset that can accurately classify a histology image as benign or malignant.
In this project in python, we'll build a classifier to train on 80% of a breast cancer histology image dataset. Of this, we'll keep 10% of the data for validation. Using Keras, we'll define a CNN (Convolutional Neural Network), call it CancerNet, and train it on our images. We'll then derive a confusion matrix to analyze the performance of the model.IDC is Invasive Ductal Carcinoma; cancer that develops in a milk duct and invades the fibrous or fatty breast tissue outside the duct; it is the most common form of breast cancer forming 80% of all breast cancer diagnoses. And histology is the study of the microscopic structure of tissues.
Dataset -https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images

PROBLEM STATEMENT-
Imagine yourself as a Chief Data Scientist working in a big medical company that is working in partnership with Cancer Hospitals and is on a mission to identify the cancerous patients early way before their terminal illness and get them cured earlywhich can potentially save their lives and at the same make advancement in medicine and drug discovery with the help of technology that is rapidly making progress in every industry. Breast cancer (BC) is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths according to global statistics, making it a significant public health problem in today’s society. 
The early diagnosis of BC can improve the prognosis and chance of survival significantly, as it can promote timely clinical treatment to patients. Further accurate classification of benign tumours can prevent patients undergoing unnecessary treatments. Thus, the correct diagnosis of BC and classification of patients into malignant or benign groups is the subject of much research. This is your role to identify those cancerous patients by collecting their biological microscopic images and then build the AI algorithm that can detect benign or malignant cancers based on the images with high accuracy and precision.

DATASET-
Invasive Ductal Carcinoma (IDC) is the most common subtype of all breast cancers. To assign an aggressiveness grade to a whole mount sample, pathologists typically focus on the regions which contain the IDC. As a result, one of the common pre-processing steps for automatic aggressiveness grading is to delineate the exact regions of IDC inside of a whole mount slide. Use this IDC_regular dataset (the breast cancer histology image dataset) from Kaggle. This dataset holds 2,77,524 patches of size 50×50 extracted from 162 whole mount slide images of breast cancer specimens scanned at 40x. Of these, 1,98,738 test negative and 78,786 test positive with IDC. The dataset is available in public domain and you can download it here. You’ll need a minimum of 3.02GB of disk space for this.

PROJECT STEPS-
Data Preparation: Begin by collecting and preparing the breast cancer histology image dataset. This involves organizing and preprocessing the images to ensure they are ready for training.
Model Architecture (CancerNet): Design the Convolutional Neural Network architecture using Keras. Define the layers, filters, pooling, and activation functions necessary to effectively capture features in the images.
Training: Train the CancerNet model on the prepared dataset using the CNN architecture. This involves feeding the images through the layers of the network, adjusting weights and biases during backpropagation, and iteratively improving the model’s accuracy.
Model Evaluation: After training, assess the performance of the CancerNet model. Use metrics such as accuracy, precision, recall, F1-score, and others to gauge the model’s ability to correctly classify breast cancer histology images.
Confusion Matrix: Derive a confusion matrix based on the model’s predictions and the actual labels of the test dataset. The confusion matrix provides insights into the model’s true positive, true negative, false positive, and false negative predictions.
Performance Analysis: Analyze the confusion matrix to understand the performance of the CancerNet model. Determine its strengths and weaknesses, such as its ability to accurately detect cancerous and non-cancerous cases.







