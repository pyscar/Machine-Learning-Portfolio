# Artificial Neural Network for MNIST Image Classification

## Abstract

This project presents an end-to-end implementation of an Artificial Neural Network (ANN) for handwritten digit recognition using the MNIST dataset. The model is developed using TensorFlow/Keras and demonstrates the complete deep learning workflow, including data preprocessing, neural network construction, training, evaluation, and prediction. In addition, the notebook includes a regression example to demonstrate the application of ANNs to continuous prediction tasks.

---

# 1. Introduction

Handwritten digit recognition is one of the most widely studied problems in computer vision and deep learning. The MNIST dataset has become a benchmark for evaluating image classification algorithms because of its simplicity and standardized format.

This project focuses on building a fully connected Artificial Neural Network capable of classifying handwritten digits into ten classes (0–9).

---

# 2. Objectives

The objectives of this project are to:

- Load and preprocess the MNIST dataset.
- Normalize image pixel values.
- Design an Artificial Neural Network using TensorFlow/Keras.
- Train and validate the model.
- Evaluate classification performance.
- Visualize predictions and model behavior.
- Demonstrate ANN regression using a synthetic dataset.

---

# 3. Dataset

The project uses the MNIST dataset provided by TensorFlow/Keras.

Dataset characteristics include:

- 60,000 training images
- 10,000 testing images
- Image resolution: 28 × 28 pixels
- Grayscale format
- 10 output classes representing digits 0–9

---

# 4. Neural Network Architecture

The implemented architecture consists of:

- Flatten layer
- Dense layer (128 neurons, ReLU activation)
- Dropout layer (20%)
- Dense output layer (10 neurons)
- Softmax activation

This architecture performs multiclass classification using the Adam optimizer and Sparse Categorical Crossentropy loss function.

---

# 5. Methodology

The workflow followed in this project consists of:

1. Data loading
2. Image normalization
3. Model construction
4. Model compilation
5. Network training
6. Performance evaluation
7. Prediction visualization

The notebook also demonstrates ANN regression using a synthetic nonlinear dataset.

---

# 6. Model Evaluation

Performance is evaluated using several metrics and visualizations, including:

- Training accuracy
- Training loss
- Validation accuracy
- Validation loss
- Confusion matrix
- Sample predictions
- Misclassified digit analysis

---

# 7. Results

The Artificial Neural Network successfully classifies handwritten digits with high accuracy on the MNIST test dataset.

Training and validation curves indicate effective learning, while the confusion matrix and prediction visualizations provide insight into model performance across all digit classes.

The regression example further illustrates the versatility of neural networks for solving continuous prediction problems.

---

# 8. Applications

Artificial Neural Networks similar to the one implemented in this project can be applied to:

- Optical Character Recognition (OCR)
- Bank cheque processing
- Postal mail sorting
- Document digitization
- Medical image analysis
- Image recognition
- Intelligent automation systems

---

# 9. Future Improvements

Potential improvements include:

- Implementing Convolutional Neural Networks (CNNs)
- Hyperparameter optimization
- Data augmentation
- Transfer learning
- Deployment using Streamlit or FastAPI
- Exporting the trained model for inference

---

# 10. Conclusion

This project demonstrates the complete deep learning pipeline for handwritten digit recognition using Artificial Neural Networks. The results highlight the effectiveness of feedforward neural networks for image classification while introducing regression as an additional neural network application.