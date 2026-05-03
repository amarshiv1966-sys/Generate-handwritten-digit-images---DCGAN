#  Handwritten Digit Generation using DCGAN

A Deep Learning project that uses a **Deep Convolutional Generative Adversarial Network (DCGAN)** to generate realistic handwritten digit images from random noise.

---

##  Overview

This project implements a **DCGAN architecture** trained on the **MNIST dataset** to generate synthetic handwritten digits.  
The model learns the underlying distribution of digit images and produces new, realistic samples.

---

## Architecture

- **Generator**
  - Takes random noise as input
  - Uses transposed convolution layers to generate images

- **Discriminator**
  - Classifies images as real or fake
  - Uses convolutional layers for feature extraction

---

##  Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

##  Dataset

- **MNIST Dataset**
  - 60,000 training images
  - 10,000 test images
  - Grayscale images of size 28×28

---

##  Features

- Generates realistic handwritten digits
- Uses GAN-based adversarial training
- Supports hyperparameter tuning
- Visualizes generated outputs

---

##  Results

Sample generated digits after training:

<!-- Add your output image here -->
![Generated Digits](<img width="488" height="484" alt="image" src="https://github.com/user-attachments/assets/9655d0f1-faf0-4ace-b0d4-911e1fc1e97f" />
)

---

## How to Run

```bash
git clone https://github.com/yourusername/dcgan-digit-generator.git
cd dcgan-digit-generator
pip install -r requirements.txt
python train.py
