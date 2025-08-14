# Hand Gesture Recognition with CNN

This project implements a **Hand Gesture Recognition** system using a Convolutional Neural Network (CNN) trained on the [LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog) dataset. The model classifies grayscale 128×128 images of hands into multiple gesture categories.  
It includes dataset download, preprocessing, training, evaluation, and an export-ready model for real-time inference.

---

## 📌 Features
- **Automatic dataset download** via `kagglehub` https://www.kaggle.com/datasets/gti-upm/leapgestrecog
- **Data preprocessing**: grayscale conversion, resizing, normalization
- CNN architecture with:
  - Convolutional layers + Batch Normalization
  - Max Pooling
  - Dropout regularization
  - Dense softmax output
- **Training & validation** with Early Stopping and ReduceLROnPlateau callbacks
- **Evaluation** with classification report and confusion matrix
- **Model export** to `.h5` and label mapping to JSON
- Ready for **real-time webcam inference** (Google Colab compatible)

---
