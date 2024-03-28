# CIFAR-10-Image-Classification
The objective of this code is to train different machine learning models for image classification using the CIFAR-10 dataset, which contains 60,000 color images categorized into 10 classes.

# • Dataset Overview: 
In the CIFAR-10 dataset, each image size is (32x32x3 pixels), and the distribution of classes (10 classes with 6,000 images each). (Evaluate results firstly on color images) 

# • Data Preparation: 
The training set contains (50,000 images). This step simulates a cross-validation setup for training. Evaluate the effect of different validation sets: a) no Validation set, b) 1 validation set with 20% of 80%, c) 3-fold cross-validation set, d) 5-fold cross-validation set, e) 10-fold cross-validation set, f) leave one out cross-validation set.

#• Model Evaluation:
Evaluate your trained model's performance using the provided test set (10,000 images). Calculate and report metrics such as accuracy, precision, recall, and Fl-score to assess classification performance.
