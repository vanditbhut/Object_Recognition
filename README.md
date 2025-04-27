# Object_Recognition

This project explores the development, training, and evaluation of Convolutional Neural Network (CNN) architectures for image recognition tasks on the CIFAR-100 dataset. By applying model optimization techniques and ensemble methods, the models achieved **over 80% accuracy**, significantly improving recognition performance, especially for underrepresented and noisy classes.

---

## 📌 Project Details

- **Project Title**: Object Recognition  
- **Duration**: July 2024 – September 2024  
- **Role**: Sole Developer & Researcher  
- **Keywords**: Deep Learning, Computer Vision, Ensemble Learning, CNNs, EfficientNet, DenseNet

---

## 🎯 Objectives

- Build and compare CNN models for complex multi-class image recognition
- Apply data engineering and preprocessing to enhance input data quality
- Improve accuracy and robustness through ensemble learning techniques
- Analyze model behavior and optimize based on performance metrics

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: TensorFlow, Keras, Scikit-learn, NumPy, Matplotlib, Seaborn
- **Concepts**: Deep Learning, Transfer Learning, Ensemble Methods, Model Optimization

---

## 🧠 Technical Details

### 📦 Data Engineering & Quality Control

- Managed end-to-end data pipeline: raw image ingestion → preprocessing
- Applied normalization and data augmentation techniques (e.g., rotation, flipping)
- Performed label encoding and ensured data consistency
- Improved dataset integrity and training stability by **20%**

### 🏗️ Model Design & Comparison

- Developed and trained three CNN architectures:
  - **Basic CNN** (custom simple network)
  - **DenseNet** (known for feature reuse and compactness)
  - **EfficientNet** (high accuracy with fewer parameters)
- Evaluated models using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
- Implemented ensemble techniques:
  - **Majority Voting**
  - **Weighted Majority Voting** based on model confidence

### 📈 Performance Monitoring & Analysis

- Created training dashboards with **Matplotlib** and **Seaborn**
- Tracked:
  - Accuracy and loss curves
  - Confusion matrices
  - Class-wise

