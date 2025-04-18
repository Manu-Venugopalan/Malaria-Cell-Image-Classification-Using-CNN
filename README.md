## 🦟 Malaria Cell Image Classification using Convolutional Neural Networks (CNN)

This project focuses on detecting **malaria-infected cells** from microscopic images using a **Convolutional Neural Network (CNN)**. It automates the classification of parasitized and uninfected blood cells, contributing toward faster and more reliable malaria diagnosis.

---

### 🔬 Objective
To classify cell images into two categories:
- **Parasitized** (Malaria-infected)
- **Uninfected** (Healthy)

---

### 🧠 Model Architecture
- Input: Color cell images resized to 64x64
- CNN Layers: Multiple convolution and max pooling layers
- Fully connected dense layers
- Activation Functions: ReLU (hidden layers), Sigmoid (output layer)
- Loss Function: Binary Crossentropy
- Optimizer: Adam

---

### 🧹 Data Preprocessing
- Image resizing and normalization
- Data augmentation using Keras `ImageDataGenerator` for better generalization
- Balanced dataset loading and splitting into train, validation, and test sets

---

### 📊 Results
- **Training Accuracy**: ~99%
- **Validation Accuracy**: ~96%
- **Loss Curve**: Stable and converging with no signs of overfitting
- **Evaluation**: Confusion matrix and classification report confirm strong performance across both classes

---

### 📁 Dataset
- Source: [NIH Malaria Dataset](https://lhncbc.nlm.nih.gov/LHC-publications/pubs/MalariaDatasets.html)
- Contains 27,558 labeled images of parasitized and uninfected blood cell images

---

### 🚀 How to Run
1. Clone the repository
2. Install required packages using `pip install -r requirements.txt`
3. Run `Malaria_Prediction_using_CNN.ipynb` to train and test the model
4. Use the trained model to predict malaria from new cell images

---
