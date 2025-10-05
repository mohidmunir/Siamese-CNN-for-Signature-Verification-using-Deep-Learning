# ✍️ Siamese CNN for Signature Verification using Deep Learning

A deep learning project that verifies whether two handwritten signatures belong to the same person using a **Siamese Convolutional Neural Network (CNN)** architecture.  
Trained and evaluated on the [**Kaggle Signature Verification Dataset**](https://www.kaggle.com/datasets/robinreni/signature-verification-dataset).

---

## 📖 Overview

Signature verification is a challenging problem in biometric authentication.  
This project implements a **Siamese ResNet-18 CNN** that learns feature embeddings of signatures and predicts whether a given pair is **genuine (same person)** or **forged (different person)**.

<p align="center">
  <img src="docs/architecture_diagram.png" width="600">
</p>

---

## 🚀 Key Highlights

- 🧠 **Siamese ResNet-18** backbone with shared weights  
- 📊 Evaluation using **Accuracy, Precision, Recall, F1-Score, ROC-AUC**  
- 🔍 Classical baselines: **HOG + SVM** and **SIFT + BoVW + SVM**  
- ⚙️ **PyTorch implementation** – Colab-ready  
- 📈 Achieved **99.3 % test accuracy**, **F1 = 0.993**, **AUC = 1.0**

---

## 🗂️ Dataset

**Source:** [Kaggle – Signature Verification Dataset](https://www.kaggle.com/datasets/robinreni/signature-verification-dataset)

