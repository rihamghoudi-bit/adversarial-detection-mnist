# adversarial-detection-mnist
Interactive demo of adversarial attacks (FGSM) and image restoration using inverse problem techniques on MNIST.
# Adversarial Detection using Inverse Problems (MNIST)

##  Overview
This project demonstrates how neural networks can be fooled by adversarial attacks and how numerical inverse methods can help recover the original signal.

We apply the **FGSM (Fast Gradient Sign Method)** to generate adversarial examples on MNIST images, then use **Total Variation (TV) denoising** to restore them.

---

##  Features
-  Random MNIST image classification
-  Adversarial attack using FGSM
-  Image restoration using TV denoising
-  Interactive interface built with Gradio

---

##  Technologies Used
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-image
- Gradio

---

##  Key Concepts
- Adversarial Machine Learning
- Fast Gradient Sign Method (FGSM)
- Inverse Problems
- Image Denoising (Total Variation)

---

##  Demo

###  Original Image
(Add screenshot here)

### Adversarial Image
(Add screenshot here)

## Restored Image
(Add screenshot here)

---

## Installation

```bash
pip install gradio tensorflow scikit-image matplotlib
