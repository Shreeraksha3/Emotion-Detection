# 😀 Emotion Detection using Deep Learning

## 📌 Overview
This project implements an **Emotion Detection System** using **deep learning models** to classify facial expressions into distinct emotion categories.  
It uses **Convolutional Neural Networks (CNNs)** for feature extraction and classification, and compares multiple architectures such as **VGG16** and **ResNet50** to determine the best-performing model.

The goal is to develop an accurate and efficient system that can detect human emotions from images, which can be useful in areas such as:
- Human-computer interaction
- Mental health monitoring
- Customer service sentiment analysis

---

## ✨ Features
- **Preprocessing** of facial images
- **Model training** with VGG16 and ResNet50
- **Model comparison** based on accuracy
- **Visualization** of training performance
- **Prediction** on custom images

---

## 🛠️ Technologies Used
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

---

## 📂 Project Structure
📁 /dataset # Dataset for training and testing
📁 /models # Saved trained models
📄 Emotion_Detection.ipynb # Jupyter Notebook with full code
📄 README.md # Project documentation


---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
4. **Run Jupyter Notebook**
   ```bash
   jupyter notebook Emotion_Detection.ipynb

---
## 🧪 Usage
- Open the Emotion_Detection.ipynb notebook.
- Run all cells to:
- Load and preprocess the dataset
- Train the model
- Evaluate accuracy
- Predict emotions on new images
---
## 📈 Model Performance
- ResNet50 achieved higher accuracy compared to VGG16 in our experiments.
- Training and validation accuracy/loss plots are included in the notebook for comparison.

## 📸 Example Output

| Input Image | Predicted Emotion |
|-------------|-------------------|
| ![Happy](docs/happy.jpg)  | Happy 😀 |
| ![Sad](docs/sad.jpg)      | Sad 😢 |








