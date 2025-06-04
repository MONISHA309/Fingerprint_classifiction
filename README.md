# INTEGRATING DIMENSION REDUCTION AND AUGMENTATION METHODS FOR ENHANCED FINGERPRINT CLASSIFICATION

## 🔍 Why This Project?
  This project focuses on fingerprint classification using deep learning. The goal is to build a secure and efficient biometric system by comparing multiple combinations of feature extraction, dimensionality reduction, and classification techniques to identify the most accurate model.

## 📂 Dataset Source
  The FVC2000_DB4_B dataset is a well-structured fingerprint dataset organized into folders: np_data, train_data, and real_data. The dataset covers 10 fingerprint classes for both left and right hands (thumb, index, middle, ring, and little fingers labeled 0–9). It provides a diverse range of fingerprint patterns, making it suitable for fingerprint classification and biometric authentication research

## 🧠 Model Description
  The proposed system enhances fingerprint classification by using augmentation techniques (like inversion, rotation), PCA/LDA for dimensionality reduction, and deep learning models. Pretrained CNNs (AlexNet, GoogleNet) extract rich features, while RNNs and DBNs handle classification. This approach improves accuracy, reduces computational cost, and boosts generalization.

🔧 Preprocessing
  1. Grayscale Conversion
  2. Resizing
  3. Gaussian Blur for Denoising
  4. Contrast Enhancement

🔁 Augmentation
  1. Inversion Augmentation
  2. Multi-augmentation

📐 Feature Extraction
  1. AlexNet
  2. GoogleNet 

📉 Dimensionality Reduction
  1. PCA (Principal Component Analysis)
  2. LDA (Linear Discriminant Analysis)

🧮 Classification
  1. RNN (Bi-LSTM)
  2. DBNs (Deep Belief Networks)

## 🏆 Results
  The highest accuracy achieved was 88.20% using Multi-Augmented GoogleNet features with PCA and DBNs. This combination proved most effective for robust and accurate fingerprint classification.

## ▶️ How to Run
Clone the repository

Upload dataset into the appropriate directory

Modify file paths in the script as needed

Run training script via Colab or local Python environment

Results and models will be saved in the specified output folder
