# MNIST Digit Recognition

## 📌 Project Overview
This project is part of a Machine Learning Internship task. The goal is to build a machine learning model that can recognize handwritten digits (0–9) using the MNIST dataset.

---

## 📊 Dataset
The MNIST dataset is a collection of handwritten digit images. It contains:
- 60,000 training images
- 10,000 testing images
- Each image is 28×28 pixels (grayscale)

The dataset is directly loaded using TensorFlow.

---

## ⚙️ Technologies Used
- Python
- NumPy
- Matplotlib
- TensorFlow / Keras

---

## 🧠 Steps Performed

### 1. Import Libraries
Required libraries such as NumPy, Matplotlib, and TensorFlow were imported.

### 2. Load Dataset
The MNIST dataset was loaded using TensorFlow.

### 3. Data Exploration
The shape of training and testing data was checked and sample images were visualized.

### 4. Data Preprocessing
Pixel values were normalized from 0–255 to 0–1 for better model performance.

### 5. Model Building
A neural network model was created using:
- Flatten layer
- Dense hidden layer (ReLU)
- Output layer (Softmax)

### 6. Model Training
The model was trained on the training dataset for multiple epochs.

### 7. Model Evaluation
The model was evaluated on test data to check accuracy.

### 8. Predictions
The trained model was used to predict digits from test images.

---

## 📈 Results
The model achieved good accuracy in recognizing handwritten digits from 0 to 9.

---

## 📂 Files Included
- mnist_digit_recognition.ipynb

---

## 🚀 How to Run
1. Open the notebook in Jupyter Notebook or Google Colab
2. Run all cells step by step
3. View results and predictions

---

## 📌 Conclusion
This project successfully demonstrates how a neural network can be used to recognize handwritten digits using the MNIST dataset.
