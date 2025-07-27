# 🖼️ Color to Grayscale Image Converter using Deep Learning

This project uses a Convolutional Autoencoder built with TensorFlow and Keras to convert color images (RGB) into grayscale. The CIFAR-10 dataset is used for training and evaluation.

---

## 🚀 Features
- Converts RGB color images to grayscale using a neural network.
- Trained on CIFAR-10 dataset (32x32 images).
- Visual comparison of original, true grayscale, and predicted grayscale outputs.
- Built using TensorFlow and Keras.

---

## 🧠 Model Architecture
- **Encoder:**
  - Conv2D → ReLU
  - MaxPooling2D
  - Conv2D → ReLU
  - MaxPooling2D
- **Decoder:**
  - Conv1DTranspose → ReLU
  - Conv2DTranspose → ReLU
  - Final Conv2D layer with sigmoid activation to output 1-channel grayscal

## 🧰 Requirements
Install dependencies using pip:
```bash
pip install tensorflow matplotlib

👨‍💻 Author

Divakar I
Built during an AI Internship project.


