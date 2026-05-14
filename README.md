# Alzheimer's Disease Classification using Hybrid model

## 📌 Project Overview
This project focuses on the classification of Alzheimer's Disease using Deep Learning techniques. The model uses MRI brain images and applies transfer learning with the VGG16 architecture for feature extraction and classification. The primary objective of this project is to predict whether an MRI brain scan belongs to an Alzheimer patient or a Normal patient.

## 🚀 Features
- MRI image preprocessing
- Image resizing from 128×128 to 224×224
- Transfer learning using VGG16
- Dataset balancing using upsampling techniques
- Model training and evaluation
- Single MRI image prediction
- Classification output:
  - Alzheimer
  - Normal
- Model summary generation

## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- VGG16
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

## 📂 Project Structure

Alzheimer-Classification/
│
├── dataset/
│   ├── Alzheimer/
│   └── Normal/
│
├── models/
│   └── trained_model.h5
│
├── notebooks/
│   └── Alzheimer_Classification.ipynb
│
├── images/
│
├── requirements.txt
│
└── README.md

## ⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/Alzheimer-Classification.git

Move to the project directory:

cd Alzheimer-Classification

Install required packages:

pip install -r requirements.txt

## ▶️ Run the Project

Open Jupyter Notebook:

jupyter notebook

Run:

Alzheimer_Classification.ipynb

## 📊 Model Workflow

1. Load MRI dataset
2. Preprocess images
3. Resize images from 128×128 to 224×224
4. Perform dataset balancing using upsampling
5. Load pre-trained VGG16 model
6. Extract image features
7. Train classification model using stacking method
8. Evaluate model performance
9. Predict disease from a single MRI image

## 📈 Expected Output

Input:
MRI Brain Image

Output:
Prediction: Alzheimer

or

Prediction: Normal

## 🔮 Future Improvements
- Improve accuracy with larger datasets
- Add multiple Alzheimer stage classification
- Deploy as a web application
- Add real-time prediction support
- Create a user-friendly interface

## 👨‍💻 Author
Revanth Sanju
