# MNIST Digit Recognition

This project is based on the MNIST Digit Recognition task. The goal of this project is to build a machine learning model that can recognize handwritten digits from 0 to 9.

The MNIST dataset contains handwritten digit images. It includes 60,000 training images and 10,000 testing images. Each image is 28 x 28 pixels in grayscale format.

In this project, the dataset was loaded using TensorFlow. The images were explored and visualized. After that, the pixel values were normalized from 0 to 255 into a range of 0 to 1. This preprocessing step helps improve model performance.

A neural network model was built using Keras. The model includes a Flatten layer, a Dense hidden layer with ReLU activation, and an output layer with Softmax activation. The model was then trained on the training dataset.

After training, the model was evaluated on the test dataset to measure its accuracy. The trained model was also used to make predictions on test images.

This project shows how deep learning can be used for image classification and handwritten digit recognition.

## Tools and Libraries Used

- Python
- NumPy
- Matplotlib
- TensorFlow
- Keras

## File Included

- MNIST.ipynb

## Conclusion

The MNIST digit recognition model was successfully built, trained, and tested. The model was able to classify handwritten digits with good accuracy.
