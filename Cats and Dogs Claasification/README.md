# 🐶🐱 Image Classification with Corrupted Data (Computer Vision Project)

This project focuses on developing a deep learning model to classify images of cats and dogs using computer vision techniques. A key challenge addressed is improving model accuracy when dealing with corrupted image data containing **salt-and-pepper noise** and **motion blur**.

---

## 🎯 Objective

- Develop a convolutional neural network (CNN) to classify cat vs dog images.
- Train and test on both clean and corrupted image datasets.
- Apply preprocessing and enhancement techniques to improve model performance under noisy conditions.

---

## 🧪 Dataset

- Contains labeled images of cats and dogs.
- Includes both:
  - **Normal images** for baseline training
  - **Corrupted images** with:
    - Salt and Pepper Noise
    - Motion Blur

---

## 🧠 Model Overview

- Baseline model: CNN architecture achieving **~88% accuracy** on clean data.
- Additional experiments:
  - Preprocessing filters for denoising
  - Data augmentation
  - Tuning hyperparameters to increase robustness
  - Evaluation on noisy datasets

---

## ⚙️ Techniques Used

- **Salt & Pepper Noise Removal**: Median filtering
- **Motion Blur Handling**: Gaussian/average filtering
- **Image Preprocessing**: Resizing, normalization
- **Data Augmentation**: Random flips, rotations
- **Model Optimization**: Learning rate tuning, batch size adjustment

---

## 🔍 Results Summary

| Data Type           | Accuracy |
|---------------------|----------|
| Clean Images        | ~88%     |
| Noisy (Baseline)    | 43.75%   |
| Noisy (Enhanced)    | 91.28% ✅ |

The model's accuracy on corrupted data improved significantly from **43.75%** to **91.28%** after applying denoising techniques, data augmentation, and tuning model architecture.  
This demonstrates the model’s enhanced robustness and ability to generalize even under challenging image conditions.


---

## 🛠️ Tools & Technologies

- Python
- TensorFlow / Keras
- OpenCV
- Google Colab
- NumPy, Matplotlib

---

## 👥 Team Members

- **Doaa Brnawi**
- **Lamis Melebari**
- **Lina Alghamdi**

---

## 📚 Course Context

This project was developed as part of a Computer Vision course, and applies concepts such as CNNs, noise processing, and image restoration to real-world classification tasks.
