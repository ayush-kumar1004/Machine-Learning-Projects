# Machine Learning Portfolio Projects

This repository contains my key Machine Learning and Data Science projects, demonstrating end-to-end predictive modeling, computer vision, natural language processing, and advanced recommendation systems.

---

## Projects Overview

### 1. [Advanced Ecommerce Recommendation System](./Advanced%20Ecommerce%20Recommendation%20System/)
Engineered a content-based recommendation engine for e-commerce products using NLP techniques, semantic similarity, and word embeddings.
* **Key Features**:
  * Product similarities computed using **Bag of Words (BoW)**, **TF-IDF**, and **Word2Vec**.
  * Results generated with low latency (<100ms) for high-performance scalability.
* **Core Code**: [Apparel_Recommendation.ipynb](./Advanced%20Ecommerce%20Recommendation%20System/Apparel_Recommendation.ipynb) & [Word2Vec Basics.ipynb](./Advanced%20Ecommerce%20Recommendation%20System/Word2Vec%20Basics.ipynb)

---

### 2. [Air Quality Prediction](./Air%20Quality%20Prediction/)
A regression-based forecasting model to predict air pollution metrics and analyze regional AQI trends.
* **Key Features**:
  * Implemented Simple and Multi-variable Linear Regression algorithms from scratch (gradient descent, loss functions).
  * Evaluated and scaled models using Scikit-Learn.
* **Core Code**: [linear_regression_from_scratch.ipynb](./Air%20Quality%20Prediction/linear_regression_from_scratch.ipynb) & [linear_regression_sklearn.ipynb](./Air%20Quality%20Prediction/linear_regression_sklearn.ipynb)

---

### 3. [Handwritten Digit Recognition](./Handwritten%20Digit%20Recognition/)
Staged an optimized classification pipeline on the MNIST dataset using the K-Nearest Neighbors (KNN) algorithm.
* **Key Features**:
  * Reduced latency with vectorized NumPy operations.
  * Fine-tuned hyperparameters using cross-validation.
* **Core Code**: [KNN_MNIST_Digit_Recognition.ipynb](./Handwritten%20Digit%20Recognition/KNN_MNIST_Digit_Recognition.ipynb)

---

### 4. [Image Classification using KNN for Real-Time Face Detection](./Image%20Classification%20using%20KNN%20for%20Real-Time%20Face%20Detection/)
Created an interactive computer vision application that captures facial features via webcam and identifies individuals in real-time.
* **Key Features**:
  * Face detection using **OpenCV** and Haar Cascades.
  * Real-time classification powered by a custom **KNN** classifier.
* **Core Code**: [face_data_collect.py](./Image%20Classification%20using%20KNN%20for%20Real-Time%20Face%20Detection/face_data_collect.py) (data capture) & [face_recognition.py](./Image%20Classification%20using%20KNN%20for%20Real-Time%20Face%20Detection/face_recognition.py) (real-time classifier)

---

## 🛠️ Technical Stack
* **Languages**: Python (NumPy, Pandas, OpenCV, Scikit-Learn, TensorFlow, NLTK)
* **Tools**: Jupyter Notebook, VS Code, Git
