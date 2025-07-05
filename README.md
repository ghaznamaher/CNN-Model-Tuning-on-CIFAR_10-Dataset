# CNN-Model-Tuning-on-CIFAR_10-Dataset

**CIFAR-10 CNN Accuracy Improvement**

This project focuses on improving the accuracy of a Convolutional Neural Network (CNN) on the CIFAR-10 dataset using hyperparameter tuning techniques without transfer learning.

**Here is a summary of the steps we took in this notebook:**

1.*Import Libraries:* Imported necessary libraries for data manipulation, model building, and visualization.
2.*Load and Normalize Data:* Loaded the CIFAR-10 dataset and normalized the pixel values.
3.*Split Data:* Split the training data into training and validation sets.
4.*Image Augmentation:* Applied image augmentation to the training data.
5.*Build and Train Baseline Model:* Created, compiled, and trained a baseline CNN model.
6.*Evaluate Baseline Model:* Evaluated the baseline model's performance and plotted learning curves.
7.*Experiment with Regularization and Architecture:* Built, trained, and evaluated models with Batch Normalization, Dropout, and increased depth individually.
8.*Experiment with Optimizer Tuning:* Built, trained, and evaluated a model with SGD with Momentum.
9.*Experiment with Callbacks:* Built, trained, and evaluated a model using Learning Rate Scheduler, Early Stopping, and Model Checkpoint.
10.*Build and Train Combined Model:* Created, compiled, and trained a model incorporating multiple improvements.
11.*Evaluate All Models:* Evaluated all the models on the test set and presented a performance summary.
12.*Visualize Confusion Matrices:* Plotted confusion matrices for each model.
13.*Report and Discuss:* Provided a report discussing the reasoning behind the changes and the impact of each technique on model performance.


