# Handwritten Digit Recognition using CNN (MNIST Dataset)

This project is a simple Machine Learning / Deep Learning model that recognizes handwritten digits (0–9) using a Convolutional Neural Network (CNN).  
It is trained using the popular *MNIST dataset*, which contains 70,000 images of handwritten digits.

---

## Project Overview

This project uses *Deep Learning* (TensorFlow + Keras) to automatically learn patterns like curves, edges, and shapes from handwritten digits.  
The model is then able to correctly classify images into digits from *0 to 9*.

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab  
  #Dataset Used
*MNIST dataset*

- 60,000 training images  
- 10,000 testing images  
- Each image: *28 × 28* pixels, grayscale  

The dataset is loaded using:
```python
from tensorflow.keras.datasets import mnist
