# CODTECH-TASK-2

Name:BUSHRA ASRAR KHAN
Company:CODTECH IT SOLUTIONS
ID:CT4MQFS
Domain:Data Science 
Duration:4 months

Project Overview: Image Classification using CNN on CIFAR-10 Dataset:
As part of my Deep Learning task for the internship at CODTECH IT SOLUTIONS, I successfully implemented an image classification model using Convolutional Neural Networks (CNNs) with TensorFlow. The model was trained on the CIFAR-10 dataset, which contains 60,000 32x32 color images across 10 categories.

Objective:
To build and evaluate a deep learning model capable of classifying images from the CIFAR-10 dataset into categories like airplanes, birds, cats, ships, and more.

Dataset:
Name: CIFAR-10

Source: Built-in Keras datasets

Classes: ['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']

Training Samples: 50,000

Test Samples: 10,000

Model Architecture:
Implemented using TensorFlow Keras Sequential API:

Conv2D (32 filters, 3x3 kernel, ReLU)

MaxPooling2D (2x2)

Conv2D (64 filters)

MaxPooling2D (2x2)

Conv2D (64 filters)

Flatten

Dense (64 units, ReLU)

Dense (10 units, Softmax)

Training Details:
Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Epochs: 10

Validation: Performed on test set

Metrics Tracked: Accuracy & Loss

Visualizations:
Training & Validation Accuracy and Loss: Line plots for each epoch

Prediction Samples: 25 test images with predicted vs. actual labels, color-coded for correctness (Blue = Correct, Red = Incorrect)

Evaluation Results:
Test Accuracy: ~{round(test_acc, 2)}

The model demonstrates effective performance for image classification tasks and correctly predicts the majority of test samples.

Key Learnings:
Built and trained a deep CNN from scratch

Gained hands-on experience with TensorFlow, model evaluation, and visualization

Learned how to analyze misclassifications using test image visualizations

Conclusion:
This project deepened my understanding of deep learning workflows including dataset handling, model design, training, and performance evaluation. Visual results provided clear feedback on prediction accuracy, making it a well-rounded image classification task.
