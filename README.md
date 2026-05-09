Smart Grape Leaf Disease Detection System 
  
## 📌 Project Overview

The **Smart Grape Leaf Disease Detection System** is an AI-powered agricultural solution designed for a client to help farmers, vineyard owners, and agricultural researchers to detect grape leaf diseases in real time using image classification and deep learning techniques.The system used, a company provided grape leaf disease dataset containing multiple categories of infected and healthy grape leaves. By analyzing uploaded leaf images, the model can instantly predict the disease type and provide faster support for crop monitoring and disease management.

# Client Requirements
The client requires a system that can:

* Detect grape leaf diseases automatically
* Classify multiple disease categories accurately
* Reduce manual inspection efforts
* Support real-time image prediction
* Improve crop health monitoring
* Assist farmers in early disease diagnosis

# Dataset Description

The dataset contains labeled grape leaf images divided into the following categories:

| Disease Category     | Description                                    |
| -------------------- | ---------------------------------------------- |
| Black Rot            | Fungal disease causing dark lesions on leaves  |
| Esca (Black Measles) | Disease affecting grapevine tissues and leaves |
| Leaf Blight          | Causes browning and drying of leaves           |
| Healthy              | Disease-free grape leaves                      |

## How to Run

### Install Requirements
pip install -r requirements.txt

### Run Training
detect-leaf-disease.ipynb

## Project Structure
grape-leaf-disease/
├── dataset/
├── models/
├── results/
├── detect-leaf-disease.ipynb (train.py)
├── requirements.txt
└── README.md

#  System Workflow

## Step 1 — Data Collection

The dataset images are collected and organized into disease-specific folders.

## Step 2 — Image Preprocessing

Images are:

* Resized
* Normalized
* Augmented using rotation, zooming, and flipping

## Step 3 — Model Training

A Convolutional Neural Network (CNN) is trained using the grape leaf dataset.

## Step 4 — Real-Time Prediction

Users upload a grape leaf image and the system predicts:

* Disease name
* Confidence score
* Leaf condition

## Step 5 — Result Visualization

The system displays prediction results with graphs and performance metrics.

---

# Technologies Used

| Technology         | Purpose                    |
| ------------------ | -------------------------- |
| Python             | Programming language       |
| TensorFlow / Keras | Deep learning framework    |
| CNN                | Image classification       |
| OpenCV             | Image preprocessing        |
| Matplotlib         | Visualization              |
| Google Colab       | Model training environment |

---

#  Expected Outcomes

The proposed system is expected to:

* Achieve high disease classification accuracy
* Detect diseases faster than manual inspection
* Support agricultural automation
* Reduce crop damage through early detection
* Improve productivity in vineyards

---

#  Real-Time Client Benefits

## ✅ Faster Disease Detection

Farmers can instantly identify diseases without waiting for laboratory analysis.

## ✅ Reduced Crop Loss

Early disease detection helps prevent disease spread.

## ✅ Cost Effective

Reduces dependency on manual experts and repeated inspections.

## ✅ Easy to Use

Simple image upload interface for real-time predictions.

## ✅ Scalable Solution

Can be expanded for:

* Mobile applications
* IoT agriculture systems
* Drone-based monitoring
* Web deployment

---

# Future Enhancements

Future versions of the system may include:

* Mobile app integration
* Live camera disease detection
* Cloud-based prediction API
* Treatment recommendations
* Multi-crop disease classification
* IoT sensor integration

---

# 📌 Conclusion

The Smart Grape Leaf Disease Detection System provides an intelligent and efficient approach for identifying grape leaf diseases using Artificial Intelligence and Deep Learning. This solution helps clients modernize agricultural monitoring, improve crop quality, and support precision farming practices through real-time disease prediction.
