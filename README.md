#  Handwritten Digit Recognizer using CNN
A Deep Learning project that recognizes handwritten digits using a Convolutional Neural Network (CNN) trained on the MNIST dataset with TensorFlow/Keras.

##  Project Overview

This project implements a **Convolutional Neural Network (CNN)** to recognize handwritten digits using the **MNIST dataset**. The model is trained to classify grayscale images of handwritten digits (0–9) with high accuracy.

Handwritten digit recognition is one of the fundamental applications of **Deep Learning** and **Computer Vision**, making it an excellent project for learning image classification using CNNs.

---

##  Problem Statement

The objective of this project is to build a deep learning model capable of accurately identifying handwritten digits from images.

The model learns patterns such as edges, curves, and shapes using convolutional layers, enabling it to classify handwritten digits with excellent accuracy.

---

##  Dataset

**Dataset:** MNIST Handwritten Digits Dataset

- Total Training Images: **60,000**
- Total Testing Images: **10,000**
- Image Size: **28 × 28 pixels**
- Number of Classes: **10 (Digits 0–9)**

The MNIST dataset is automatically loaded using TensorFlow/Keras.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

##  CNN Architecture

The Convolutional Neural Network consists of:

- Conv2D (32 filters, 3×3, ReLU)
- MaxPooling2D
- Conv2D (64 filters, 3×3, ReLU)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Dropout (0.5)
- Output Layer (10 neurons, Softmax)

---

## Project Workflow

1. Import required libraries
2. Load the MNIST dataset
3. Preprocess images
   - Normalize pixel values
   - Reshape images
   - One-hot encode labels
4. Build the CNN model
5. Train the model
6. Evaluate model performance
7. Predict handwritten digits
8. Visualize predictions
9. Save the trained model

---

## 📊 Model Evaluation

The model is evaluated using:

- Test Accuracy
- Test Loss
- Classification Report
- Confusion Matrix

Typical Accuracy:

**98% – 99%**

---

## 📈 Results

The CNN successfully recognizes handwritten digits with high accuracy.

Example output:

- Test Accuracy: **99%**
- Accurate predictions on unseen handwritten digit images
- Classification report showing excellent precision, recall, and F1-score

---

## 📁 Project Structure

```
Handwritten-Digit-Recognizer-CNN/
│
├── Handwritten_Digit_Recognizer.ipynb
├── README.md
├── requirements.txt
└── handwritten_digit_cnn.keras
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YasaswiniPilla/Handwritten-Digit-Recognizer-CNN.git
```

Navigate to the project folder

```bash
cd Handwritten-Digit-Recognizer-CNN
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook or Google Colab notebook to train and test the model.

---

## 📷 Sample Output

The project displays:

- Sample handwritten digit images
- Training & Validation Accuracy Graph
- Training & Validation Loss Graph
- Predicted digit images
- Confusion Matrix
- Classification Report

---

## 💡 Future Improvements

- Real-time handwritten digit recognition
- Streamlit web application
- Flask deployment
- Upload custom handwritten images for prediction
- Improve model using Batch Normalization
- Hyperparameter tuning

---

## 🎓 Learning Outcomes

This project demonstrates:

- Deep Learning fundamentals
- Convolutional Neural Networks (CNN)
- Image preprocessing
- Image classification
- TensorFlow/Keras implementation
- Model evaluation
- Computer Vision basics

---

## 👩‍💻 Author

**Yasaswini Pilla**

B.Tech – Information Technology

Machine Learning & Deep Learning Enthusiast

GitHub: https://github.com/YasaswiniPilla

---

## ⭐ If you found this project useful, please consider giving it a Star!
