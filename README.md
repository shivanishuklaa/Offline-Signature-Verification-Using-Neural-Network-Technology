# Offline-Signature-Verification-Using-Neural-Network-Technology

This project is aimed at verifying signatures using a neural network-based model. The task involves determining whether a signature is real or forged by leveraging deep learning techniques, particularly Convolutional Neural Networks (CNNs) and Siamese Networks (SNNs). The project uses TensorFlow and Keras to train a model on a dataset of real and forged signatures.

The training dataset comprises of information assembled from open sources. It incorporates data from 30 people who have both genuine and forged signature.  
Link:-https://www.kaggle.com/datasets/divyanshrai/handwritten-signatures

# Project Description
This project focuses on developing an offline signature verification system using deep learning. The model is trained on signature images, using Siamese Networks to measure the similarity between two signature images and classify them as either real or forged.

Key features of the project:

1. Data Preprocessing: The signature images are resized and preprocessed to fit the input requirements of the model.
2. Model Architecture: A custom CNN-based feature extractor combined with a Siamese network to compute similarity between two images.
3. Training: The model is trained on real and forged signature pairs.
4. Evaluation: The model's performance is evaluated using metrics like accuracy, precision, recall, and F1 score.

# Installation Requirements
Python 3.9, TensorFlow, Keras, OpenCV, scikit-learn, NumPy, Matplotlib, seaborn

# Model Architecture
The model consists of the following components:
1. Feature Extractor: A CNN-based feature extractor that learns distinctive features from the input signature images.
2. Siamese Network: Two identical networks that process the two input signature images and measure their similarity.
3. Output Layer: A dense layer with a sigmoid activation function to classify the similarity as either "Real" or "Forged".

   
