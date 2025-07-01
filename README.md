# CNN-Model-Tuning-on-CIFAR_10-Dataset

CIFAR-10 CNN Accuracy Improvement
This project focuses on improving the accuracy of a Convolutional Neural Network (CNN) on the CIFAR-10 dataset using hyperparameter tuning techniques without transfer learning.

Baseline Performance
Model: Simple 2-layer CNN

Test Accuracy: 64.8%

Improvements Applied
Data Normalization

Scaled pixel values to [0, 1].

Train-Validation Split

Split 10% of training data for validation.

Data Augmentation

Applied rotation, width/height shifts, and horizontal flipping.

Model Architecture Tuning

Added more convolutional layers.

Introduced Batch Normalization and Dropout to reduce overfitting.

Optimizer Tuning

Used Adam with learning rate scheduling (ReduceLROnPlateau).

Callbacks

Used EarlyStopping to halt training when validation accuracy stopped improving.

Evaluation Metrics

Final accuracy on test set.

Confusion matrix and classification report.

Training/validation accuracy and loss curves.

Final Performance
Test Accuracy After Tuning: 84.6%

