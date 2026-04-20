# 🧠 Adversarial Detection using Inverse Problems (MNIST)

Interactive demo of adversarial attacks (FGSM) and image restoration using inverse problem techniques on MNIST.

---

## 📌 Overview
This project demonstrates how neural networks can be fooled by adversarial attacks and how numerical inverse methods can help recover the original signal.

We apply the **FGSM (Fast Gradient Sign Method)** to generate adversarial examples on MNIST images, then use **Total Variation (TV) denoising** to restore them.

---

## 🚀 Features
- 🔢 Random MNIST image classification  
- ⚠️ Adversarial attack using FGSM  
- 🧹 Image restoration using TV denoising  
- 🎛 Interactive interface built with Gradio  

---

## 🛠 Technologies Used
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Scikit-image  
- Gradio  

---

## 🧠 Key Concepts
- Adversarial Machine Learning  
- Fast Gradient Sign Method (FGSM)  
- Inverse Problems  
- Image Denoising (Total Variation)  

---

## 📷 Demo

### 🟢 Original Image
![Clean](images/clean.png)

### 🔴 Adversarial Image
![Attack](images/attack.png)

### 🔵 Restored Image
![Restored](images/restored.png)

---

## 🔗 Live Demo
👉 https://4ff4e284d7e3549258.gradio.live

⚠️ Note: This link is temporary (Gradio public link expires after a few days).

---

## ⚙️ Installation

```bash
pip install gradio tensorflow scikit-image matplotlib
