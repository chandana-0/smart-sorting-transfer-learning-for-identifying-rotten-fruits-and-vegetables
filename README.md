# 🧠 Smart Sorting – Transfer Learning for Rotten Fruit & Vegetable Detection

## 📌 Project Overview
Smart Sorting is a deep learning-based web application designed to classify fruits and vegetables as Healthy or Rotten using transfer learning techniques. It leverages the VGG16 architecture to provide fast and accurate predictions. This solution supports quality control in agriculture, retail, and household environments by reducing food waste and improving sorting efficiency.

## ✨ Key Features
- Upload images of fruits or vegetables via a user-friendly web interface  
- Predict the freshness category using a pre-trained VGG16 CNN  
- Display result: Good to Eat or Not  
- Show prediction confidence and feedback message  
- Capture user feedback for continuous improvement

## 📁 Dataset Details
- Source: Kaggle  
- ~29,000 images  
- 29 classes (Healthy/Rotten pairs for 14 fruits and vegetables)  
- Split: 80% Training / 20% Validation  
- Preprocessing: Resized, normalized, and augmented using ImageDataGenerator

## 🧠 Model Architecture
- Based on VGG16 with pre-trained ImageNet weights  
- Fine-tuned top layers for binary classification  
- Trained using EarlyStopping and ModelCheckpoint  
- Evaluation: classification report, confusion matrix, Grad-CAM

## 🧰 Tech Stack
- Python 3.9  
- TensorFlow / Keras  
- Flask  
- HTML5 & CSS3  
- Jupyter Notebook  
- PIL, NumPy, OS

