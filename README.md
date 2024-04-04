# Brain Tumor Classification using CNN and TensorFlow 2.16

The following is an updated version of my [CNN brain tumor classification 2023](https://github.com/GusLovesMath/CNN_Brain_Tumor) project.

## Overview 🧠

This repository contains the code and documentation for a Convolutional Neural Network (CNN) designed to classify brain tumors into multiple categories: Glioma, Meningioma, No Tumor, and Pituitary. With the utilization of TensorFlow 2.16 and GPU acceleration, the model achieves a remarkable accuracy rate of 99.6%, demonstrating its robustness as a diagnostic tool. The project showcases the effectiveness of advanced CNN models, optimized with learning rates and early stopping mechanisms, in improving the accuracy and efficiency of brain tumor diagnosis, which is pivotal for enhancing medical treatment outcomes.

## Project Details 

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

## About the Dataset 📁

This project uses a comprehensive dataset combining figshare, SARTAJ, and Br35H collections, totaling 7023 MRI images classified into four categories: glioma, meningioma, no tumor, and pituitary. The dataset is designed for in-depth brain tumor analysis, crucial for early detection and accurate classification, which are key in determining the appropriate treatment path.

### Types of brain tumors in the dataset:
- **Glioma**: Cancerous brain tumors in glial cells.
- **Meningioma**: Non-cancerous tumors originating from the meninges.
- **No Tumor**: Normal brain scans without detectable tumors.
- **Pituitary**: Tumors affecting the pituitary gland, which can be cancerous or non-cancerous.
  
The dataset was refined to ensure high quality, with adjustments made to the glioma class for improved accuracy. Given the variety in image size, preprocessing steps such as resizing and margin trimming are recommended to optimize model performance.

For further information and to access the dataset, visit the Kaggle page: [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).
