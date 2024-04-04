# Brain Tumor Classification using CNN and TensorFlow 2.16

## Overview

This repository contains the code and documentation for a Convolutional Neural Network (CNN) designed to classify brain tumors into multiple categories: Glioma, Meningioma, No Tumor, and Pituitary. With the utilization of TensorFlow 2.16 and GPU acceleration, the model achieves a remarkable accuracy rate of 99.6%, demonstrating its robustness as a diagnostic tool. The project showcases the effectiveness of advanced CNN models, optimized with learning rates and early stopping mechanisms, in improving the accuracy and efficiency of brain tumor diagnosis, which is pivotal for enhancing medical treatment outcomes.

## Project Details:

- **Project Language**: Python, TensorFlow 2.16, Keras, Pandas, NumPy, Seaborn, Matplotlib.
- **Model Accuracy**: 99.6% on an extensive dataset of MRI brain tumor images.
- **Categories Classified**: Glioma, Meningioma, No Tumor, and Pituitary.
- **Key Techniques Used**:
  - Data augmentation to enhance dataset diversity and robustness.
  - Fine-tuning of learning rates with the Adam optimizer for better convergence.
  - Utilization of beta_1 and beta_2 values adjustments in the Adam optimizer.
- **Performance Enhancements**:
  - GPU acceleration to expedite training processes.
  - Implementation of EarlyStopping and ReduceLROnPlateau callbacks to prevent overfitting and optimize learning rates during training.

