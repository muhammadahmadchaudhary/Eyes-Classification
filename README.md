# Eye Classification Project
## This project focuses on classifying images of eyes using machine learning techniques. The workflow involves data preprocessing, model training, and evaluation to accurately predict the category of eye images based on their features. Below is an overview of the key steps implemented in the project:

# Data Preparation:

##Images are loaded from a specified directory structure where each subfolder represents a different class label.

## The dataset is constructed by associating image paths with their corresponding labels, followed by shuffling and resetting indices for consistency.

# Image Preprocessing:

## Images are resized and normalized to prepare them for input into the model.
## Additional preprocessing steps include converting images to grayscale, applying standard scaling, and encoding labels.

# Model Training:

## Various models are explored, including Convolutional Neural Networks (CNNs) implemented using TensorFlow/Keras, and traditional machine learning models like Support Vector Machines (SVM).
## The models are trained on the preprocessed dataset, with performance metrics like accuracy being tracked.

#Evaluation:

## After training, the models are evaluated using metrics such as accuracy, classification reports, and confusion matrices.
## These metrics help in understanding the effectiveness of the model and identifying areas for improvement.

## This project serves as a practical implementation of machine learning techniques for image classification, particularly in the domain of eye-related imagery. It demonstrates the full pipeline from data preparation to model evaluation, providing insights into the challenges and considerations involved in developing a robust classification model.
