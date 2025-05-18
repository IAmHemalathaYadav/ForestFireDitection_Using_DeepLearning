# 🔥 Forest Fire Detection using Deep Learning

A deep learning-based image classification system that detects forest fires using Convolutional Neural Networks (CNN). The goal is to enable early fire detection using satellite or camera images and support rapid emergency response.

The model is trained on [The Wildfire Dataset](https://www.kaggle.com/datasets) from Kaggle, containing curated real-world images of forests with and without wildfires.

---

## 📌 Problem Statement

Forest fires result in massive environmental and economic losses, including the destruction of natural resources, threats to wildlife, and danger to human life. Traditional fire detection methods are manual, time-consuming, and often too late. This project addresses the need for an automated, scalable, and accurate solution using Deep Learning to detect fires in real-time from images.

---

## 🎯 Objective

- Classify images into two categories: **"Fire"** and **"No Fire"**
- Use **Convolutional Neural Networks (CNNs)** for image classification
- Provide a **real-time, automated detection system**
- Enable **early response** using satellite or surveillance camera images
- Reduce dependency on manual monitoring systems

---

## 🛠️ Technologies Used

- Python 🐍
- TensorFlow / Keras 🤖
- OpenCV 📷
- NumPy, Matplotlib, PIL
- Google Colab / Jupyter Notebook
- Image datasets (Fire and No Fire)

---

## 📁 Dataset structure

  wildfire_dataset
            |__train
                  |__Fire/NoFire
            |__validation
                  |__Fire/NoFire
            |__test
                  |__Fire/NoFire
  📌 Total images: 6,437
  📁 Split: Train, Validation, Test

## 🚀 How to Run the Project
  1)Clone the Repository
  2)Install Dependencies
  3)Train the Model
  4)Make Predictions
  
## 📊 Results
  - Achieved ~81% validation accuracy
  - Successfully detected fire presence from custom test images
  - Training and validation accuracy/loss graphs show good convergence

## 📈 Future Enhancements
  - Deploy using Flask or Streamlit as a web app
  - Integrate real-time detection from drone or CCTV footage
  - Use Transfer Learning (e.g., ResNet, VGG) to improve accuracy
  - Expand and balance the dataset for robustness

## 📄 License
  - This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)..




  
           
