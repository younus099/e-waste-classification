# 🔌 E-Waste Image Classification using EfficientNetV2B0

This is a deep learning project focused on classifying different types of electronic waste using images. The model uses EfficientNetV2B0 with transfer learning to enhance accuracy while keeping training efficient.

## 📌 Project Overview

Electronic waste (e-waste) poses a serious environmental challenge. Manual classification is time-consuming and often inaccurate. This project automates the identification of e-waste items by classifying images into 10 predefined categories using a CNN-based image classifier.

## 🧠 Features

✅ EfficientNetV2B0 as a pre-trained base  
✅ Custom classification head with softmax output  
✅ Training, validation, and testing using `image_dataset_from_directory`  
✅ EarlyStopping and ModelCheckpoint callbacks  
✅ Evaluation with confusion matrix & classification report  
✅ Interactive Gradio interface for image prediction

## 🗂 Dataset Structure
Dataset/

├── train/

├── validation/

└── test/

## 🗂 Dataset
Source: [Kaggle - E-Waste Image Dataset](https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset)

## 🛠️ Tools & Technologies

- Python
- TensorFlow & Keras
- EfficientNetV2B0 (Transfer Learning)
- Gradio
- NumPy, Matplotlib, Seaborn
- PIL (Image Handling)
- Scikit-learn (Evaluation metrics)

Each folder contains 10 class-specific subfolders with images.

📉 Model Accuracy: ~94%  
📦 Model Format: `best_model.keras`

🖥 Try It Yourself

Run the notebook or use the Gradio interface to test with your own images:
```python
interface.launch(share=True)
