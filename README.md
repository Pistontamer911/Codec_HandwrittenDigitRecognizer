# Handwritten Digit Recognition using Convolutional Neural Networks (CNN)

## 📌 Project Overview

Handwritten digit recognition is a fundamental computer vision problem that involves classifying handwritten numerical digits into one of ten categories (0–9). This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset.

The model learns spatial features directly from image data through convolution and pooling operations, making it highly effective for image classification tasks.

---

## 🎯 Objectives

* Build a deep learning model for handwritten digit classification.
* Understand image preprocessing techniques.
* Learn the fundamentals of Convolutional Neural Networks.
* Evaluate model performance using accuracy metrics.
* Visualize training progress and prediction results.

---

## 📊 Dataset Information

### MNIST Dataset

The MNIST dataset is one of the most widely used benchmark datasets in machine learning and computer vision.

Dataset Characteristics:

* Total Images: 70,000
* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 pixels
* Color Format: Grayscale
* Classes: 10 digits (0–9)

Each image contains a handwritten digit represented by pixel intensity values ranging from 0 to 255.

---

## 🛠 Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn

---

## 🏗 CNN Architecture

The implemented Convolutional Neural Network consists of:

### Input Layer

* 28 × 28 grayscale image

### Convolution Layer 1

* 32 filters
* 3 × 3 kernel
* ReLU activation

### Max Pooling Layer 1

* 2 × 2 pooling

### Convolution Layer 2

* 64 filters
* 3 × 3 kernel
* ReLU activation

### Max Pooling Layer 2

* 2 × 2 pooling

### Flatten Layer

* Converts feature maps into a 1D vector

### Dense Layer

* 128 neurons
* ReLU activation

### Output Layer

* 10 neurons
* Softmax activation

---

## 🔄 Workflow

1. Load MNIST dataset
2. Normalize pixel values
3. Reshape images for CNN input
4. Build CNN architecture
5. Train the model
6. Evaluate model performance
7. Generate predictions
8. Visualize results

---

## 📈 Model Training

The model is trained using:

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Evaluation Metric: Accuracy
* Epochs: 5

The Adam optimizer efficiently updates model weights while minimizing classification loss.

---

## 📊 Performance Evaluation

Evaluation metrics include:

* Training Accuracy
* Validation Accuracy
* Test Accuracy

Additional visualizations:

* Accuracy Curve
* Sample Prediction Results
* Digit Recognition Examples

---

## 🔍 Key Findings

* CNNs automatically learn important image features.
* Convolution layers effectively detect edges and patterns.
* Pooling layers reduce dimensionality and improve efficiency.
* Deep learning significantly outperforms traditional image classification approaches.
* The model achieves high classification accuracy on unseen test images.

---

## 🚀 Applications

Handwritten digit recognition can be applied in:

* Postal code recognition
* Bank cheque processing
* Form digitization
* Document automation
* OCR systems
* Educational software

---

## ✅ Conclusion

This project demonstrates the power of Convolutional Neural Networks for image classification. By training on the MNIST dataset, the model successfully learns handwritten digit patterns and achieves high prediction accuracy. The project provides a strong foundation for understanding deep learning, computer vision, and neural network architectures.

---

## 👨‍💻 Author

Dharineesh

