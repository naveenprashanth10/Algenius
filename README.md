# 🌿 Algae Type & Toxicity Classifier

A deep learning–based image classification system that identifies different algae species and determines whether they are **toxic or non-toxic**, along with **descriptions and safety precautions**.

Built using **TensorFlow, MobileNetV2 (Transfer Learning), and Gradio** for an interactive web interface.

---

## 🚀 Features

- 🔍 Image-based algae classification  
- 🧠 Transfer Learning using MobileNetV2  
- ⚡ Data augmentation for better generalization  
- 🧪 Toxic vs Non-Toxic identification  
- 📝 Auto-generated:
  - Description  
  - Safety precautions  
- 🌐 Gradio web app for real-time predictions  
- 📦 Runs seamlessly on Google Colab  

---

## 🧠 Model Architecture

- **Base Model:** MobileNetV2 (ImageNet weights)  
- **Input Size:** 128 × 128 × 3  

### Custom Classification Head:
- GlobalAveragePooling2D  
- Dense (ReLU)  
- Dropout  
- Softmax output layer  

---

## 📂 Dataset Structure
algae_dataset/
│
├── train/
│ ├── Microcystis/
│ ├── Anabaena/
│ ├── Chlorella/
│ ├── Scenedesmus/
│ └── Oscillatoria/
│
└── val/
├── Microcystis/
├── Anabaena/
├── Chlorella/
├── Scenedesmus/
└── Oscillatoria/
