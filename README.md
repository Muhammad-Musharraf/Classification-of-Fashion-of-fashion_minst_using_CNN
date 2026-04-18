# 👕 Fashion MNIST Classification using CNN

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN)** to classify clothing images from the **Fashion MNIST dataset**. The model learns to recognize different types of fashion items such as shirts, shoes, bags, and more with high accuracy.

Fashion MNIST is a widely used benchmark dataset in computer vision, consisting of grayscale images of clothing items across 10 categories. ([arXiv][1])

---

## 🎯 Objective

The main goal of this project is to:

* Build a deep learning model using CNN
* Train it on Fashion MNIST dataset
* Achieve accurate multi-class image classification
* Understand feature extraction using convolutional layers

---

## 📊 Dataset Information

The dataset contains:

* 🖼️ 70,000 grayscale images (28×28 pixels)
* 🧪 60,000 training images
* 🧾 10,000 testing images
* 🔟 10 classes of fashion items

### Classes:

* T-shirt/top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

---

## 🧠 Model Architecture

The project uses a **Convolutional Neural Network (CNN)** consisting of:

* Convolutional Layers (feature extraction)
* Activation Function (ReLU)
* Pooling Layers (dimensionality reduction)
* Fully Connected Dense Layers
* Output Layer (Softmax for classification)

CNNs are highly effective for image classification tasks due to their ability to automatically learn spatial features from images. ([MDPI][2])

---

## ⚙️ Workflow

1. Load Dataset (Fashion MNIST)
2. Normalize Pixel Values
3. Reshape Input Data
4. Build CNN Model
5. Compile Model
6. Train Model
7. Evaluate Performance
8. Make Predictions

---

## 📈 Evaluation Metrics

* Accuracy
* Loss
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 🛠️ Technologies Used

* Python 🐍
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 🚀 How to Run This Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Muhammad-Musharraf/Classification-of-Fashion-of-fashion_minst_using_CNN.git
cd Classification-of-Fashion-of-fashion_minst_using_CNN
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebook / Script

```bash
jupyter notebook
```

---

## 📊 Key Features

✔️ CNN-based image classification
✔️ End-to-end deep learning pipeline
✔️ Clean preprocessing of image data
✔️ Beginner-friendly implementation
✔️ Strong baseline for computer vision tasks

---

## 🔮 Future Improvements

* Add data augmentation
* Hyperparameter tuning
* Use advanced architectures (VGG, ResNet)
* Deploy model using Streamlit or Flask
* Improve accuracy with regularization techniques

---

## 👤 Author

**Muhammad Musharraf**
Passionate about Artificial Intelligence, Machine Learning, and Deep Learning.

---

## ⭐ Support

If you find this project useful, please ⭐ star the repository and share it!
