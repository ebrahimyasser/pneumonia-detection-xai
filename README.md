# Pneumonia Detection with Explainable AI

This project is a graduation thesis for BSc in Artificial Intelligence (BUE), aiming to build a robust and explainable AI system for pediatric pneumonia detection from chest X-rays.

## 🚀 Models Used
- VGG16 (TensorFlow)
- ResNet50 (TensorFlow)
- Vision Transformer (ViT) (PyTorch + timm)
- ViT-CNN Hybrid Ensemble

## 🧠 Features
- Transfer Learning (ImageNet pretrained)
- Grad-CAM Visualizations for explainability
- Attention Rollout (for ViT)
- Handling class imbalance with weighted loss
- GPU support for training

## 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Grad-CAM heatmaps

## 🗃️ Dataset
- Pediatric Chest X-Ray Dataset (Kermany et al.)  
  Available via [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## 🛠️ Libraries
- TensorFlow / Keras
- PyTorch + timm
- OpenCV, NumPy, Matplotlib

## 📁 Structure
- `models/` → Model definitions
- `notebooks/` → Training and testing notebooks
- `outputs/` → Visualizations and results
- `utils/` → Helper functions (e.g., Grad-CAM)

## 📄 License
This project is licensed under the MIT License.
