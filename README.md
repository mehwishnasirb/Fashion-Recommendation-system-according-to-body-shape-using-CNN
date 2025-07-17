# Fashion-Recommendation-system-according-to-body-shape-using-CNN
This project is a Flask-based web application that recommends suitable outfits based on a person's body shape, using deep learning models. The system analyzes a user's uploaded image to identify body type and suggests fashion styles accordingly.
<h1 align="center">👗 Fashion Recommendation System</h1>
<h3 align="center">A deep learning-based Flask app that suggests outfits based on body shape analysis</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?logo=python" alt="python" />
  <img src="https://img.shields.io/badge/TensorFlow-ResNet50-orange?logo=tensorflow" alt="tensorflow" />
  <img src="https://img.shields.io/badge/Flask-2.0-green?logo=flask" alt="flask" />
</p>

---

## 🧠 Project Description

This project uses deep learning and computer vision to suggest fashion outfits based on the **body shape detected from a user's image**. It is a complete web application developed with **Flask**, integrated with two trained models:

- A **ResNet50-based CNN model** to classify body shape
- A rule-based outfit recommendation system based on predicted body shape

---

## 📷 How It Works

1. User uploads a full-body image.
2. Image is processed and resized to fit the model.
3. Body shape is predicted using the ResNet50 model.
4. An appropriate list of outfits is recommended for that body type.
5. Results are displayed in a clean web interface.

---

## 🚀 Demo

📍 Run locally at:  
```bash
http://127.0.0.1:8000
