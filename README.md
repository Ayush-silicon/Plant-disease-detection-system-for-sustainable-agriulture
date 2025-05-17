# 🌿 Plant Disease Detection System for Sustainable Agriculture

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-ML-orange?logo=tensorflow) 
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red?logo=streamlit)
![AICTE](https://img.shields.io/badge/AICTE-Internship-yellow)

## 🧠 Overview

A deep learning-based web application that identifies plant diseases from leaf images using a **Convolutional Neural Network (CNN)**. This system supports crops like:

- 🍎 Apple
- 🍒 Cherry
- 🍇 Grape
- 🌽 Corn

> ⚡ Built for AICTE Internship Cycle 6  
> 🎯 Goal: Support **precision agriculture** by enabling early disease detection and sustainable crop management.

---

## 📷 Sample Output

| Upload Leaf Image | Prediction |
|-------------------|------------|
| ![Leaf]("C:\Users\Ayush Singh\Downloads\Edunet-Internship\apple scap.jpeg") | `Apple Scab (Confidence: 97%)` |

---

## 🔍 Features

- 🌱 Classifies healthy and diseased leaves
- 🤖 Trained CNN using **PlantVillage** dataset
- 🖥️ Interactive web app built with **Streamlit**
- 📊 Outputs **disease name**, **confidence score**, and **suggested cure**
- 📈 Real-time predictions with **high accuracy**

---

## 🧪 Tech Stack

| Layer            | Tools Used                         |
|------------------|------------------------------------|
| Language         | `Python`                           |
| Deep Learning    | `TensorFlow`, `Keras`, `CNN`       |
| Data Processing  | `OpenCV`, `NumPy`, `Matplotlib`    |
| Web UI           | `Streamlit`                        |
| Training Platform| `Google Colab`                     |

---

## ⚙️ Methodology

```mermaid
graph TD
    A[Image Upload] --> B[Image Preprocessing]
    B --> C[CNN Model Inference]
    C --> D{Healthy or Diseased?}
    D -->|Healthy| E[Result: Healthy Leaf ✅]
    D -->|Diseased| F[Result: Disease Type + Cure ⚠️]
