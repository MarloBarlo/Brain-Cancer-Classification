# 🧠 Brain Cancer Classification using CNN

## Overview

This project applies deep learning techniques to classify **brain MRI scans** as **cancerous** or **non-cancerous** using a **Convolutional Neural Network (CNN)** built with Python and TensorFlow/Keras. It was developed as part of an independent study to explore the intersection of medical imaging and artificial intelligence.

---

## 🔍 Objective

To build a reliable classification model that can analyze medical imaging data and accurately detect signs of brain cancer, supporting early diagnosis and potential intervention.

---

## 🧰 Tools & Libraries

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **OpenCV**

---

## 📁 Dataset
The original plan for this project was to use MRI scan data from The Cancer Imaging Archive (TCIA), a publicly available resource for medical imaging datasets. To prepare for this, I developed an image conversion tool designed to preprocess DICOM images into a format compatible with deep learning workflows (e.g., JPEG or PNG).

However, due to time constraints within the scope of the independent study, I was unable to fully integrate and process the TCIA data. Instead, I used a smaller pre-labeled dataset of brain MRI scans for training and testing the CNN model. This allowed for building and validating the core deep learning pipeline while setting the foundation for future expansion using TCIA or similar datasets.

The dataset consists of brain MRI scans labeled as:
- **Cancerous**
- **Non-Cancerous**

> [Dataset](https://www.kaggle.com/code/rezas6234/transformlay-brain-datasets-br35h-1ep/notebook)


---

## 🧠 Model Architecture

The CNN architecture includes:
- Multiple **convolutional** and **max-pooling** layers
- **Dropout** for regularization
- **Flattening** and **dense layers** for classification
- **Binary crossentropy** as the loss function
- **Accuracy** as the primary metric

---

## 🧪 Evaluation

The model is trained on a split of training and validation data, and evaluated using:
- **Confusion Matrix**
- **Accuracy Score**
- **Loss Curves**
- **Classification Report**

---

## 🖼️ Visual Examples

**Training & Test Accuracy**  
![image](https://github.com/user-attachments/assets/b50868f3-4b48-4175-9dc8-44b7ac863424)

**Cancerus MRI Scan
![image](https://github.com/user-attachments/assets/23b9fe19-8792-4c0c-9e2a-5af691e2501e)

**Cancer free MRI Scan
![image](https://github.com/user-attachments/assets/17a3c2b5-603f-437f-ba85-f2358362adca)

---

## ✅ Results

- Achieved over **92% accuracy** on the validation set.
- Successfully identified patterns in MRI images that distinguish cancerous tissue.

---

## 💡 Future Work

- Expand dataset for better generalization.
- Expand classification to other cancers (Lung, Breast, etc.) or Specify Brain cancer types.
- Experiment with **data augmentation**.
- Possibly deploy the model using **Flask** or **Streamlit** for clinical demo purposes.
