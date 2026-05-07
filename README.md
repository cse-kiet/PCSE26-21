# 🌱 Crop Disease Detection using Deep Learning

An AI-powered crop disease detection system that identifies plant diseases from leaf images using a Convolutional Neural Network (CNN). The project is designed to help farmers and agricultural researchers detect diseases quickly, accurately, and efficiently using image-based analysis.

---

# 📌 Project Overview

Crop diseases significantly affect agricultural productivity and food security worldwide. Traditional disease detection methods are time-consuming, expensive, and dependent on expert knowledge.

This project provides an automated solution using Deep Learning and Computer Vision to classify plant diseases from leaf images. The system is trained on the PlantVillage Dataset and is capable of identifying 38 different plant disease classes, including healthy leaves.

The model achieves high accuracy while remaining lightweight and practical for real-world deployment on mobile and web platforms.

---

# 🚀 Features

- 🌿 Detects 38 plant diseases and healthy leaves
- 🤖 Deep Learning-based CNN architecture
- 📷 Image upload and real-time disease prediction
- 📊 Confidence score for predictions
- ⚡ Fast and lightweight implementation
- 📱 Suitable for mobile/web deployment
- 🧠 Automatic feature extraction using CNN
- 🌎 Future-ready for real-world field conditions

---

# 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Flask / Streamlit
- CNN (Convolutional Neural Network)

---

# 📂 Dataset

## PlantVillage Dataset

- Total Images: 61,486
- Classes: 38
- Includes:
  - Diseased plant leaves
  - Healthy plant leaves

### Crops Included

- Tomato
- Potato
- Corn
- Apple
- Grape
- Pepper
- Peach
- Strawberry
- Cherry
- Soybean
- and more

---

# 🧠 Model Architecture

The project uses a customized Convolutional Neural Network (CNN) architecture consisting of:

- Convolution Layers
- ReLU Activation
- Batch Normalization
- Max Pooling
- Dropout Layers
- Fully Connected Dense Layers
- SoftMax Output Layer

The model automatically learns features such as:

- Leaf spots
- Discoloration
- Texture variations
- Disease-specific patterns

---

# 🔄 Workflow

1. User uploads a leaf image
2. Image preprocessing is applied
3. CNN extracts important features
4. Model predicts disease class
5. Prediction and confidence score are displayed

---

# 🖼️ Image Preprocessing

The following preprocessing and augmentation techniques are used:

- Image Resizing
- Normalization
- Rotation
- Flipping
- Brightness Adjustment
- Zooming
- Noise Reduction

These techniques improve model robustness under varying real-world conditions.

---

# 📈 Model Performance

| Metric | Value |
|--------|--------|
| Accuracy | 98.7% |
| Classes | 38 |
| Dataset Size | 61,486 Images |

The model performs exceptionally well under controlled conditions and is designed to generalize for practical agricultural environments.

---

# 📱 Future Enhancements

- Integration with mobile applications
- Real-time field deployment
- Support for additional crops and diseases
- Use of advanced architectures:
  - EfficientNet
  - ResNet
  - Vision Transformers (ViT)
- Cloud-based monitoring dashboard
- Multilingual farmer support

---

# 🌍 Real-World Impact

This project aims to:

- Reduce crop losses
- Improve agricultural productivity
- Enable early disease detection
- Reduce unnecessary pesticide usage
- Help farmers make faster decisions
- Promote sustainable farming practices

---

# 📂 Project Structure

```bash
Crop-Disease-Detection/
│
├── dataset/
├── model/
├── static/
├── templates/
├── app.py
├── train.py
├── predict.py
├── requirements.txt
├── README.md
└── saved_model/
```

# 📊 CNN Working Overview

The Convolutional Neural Network processes images in multiple stages:

- Convolution operation extracts visual patterns
- ReLU introduces non-linearity
- Pooling reduces dimensions while preserving features
- Dense layers perform classification
- SoftMax predicts disease probabilities

This layered learning approach enables accurate disease detection from plant leaf images.

---

# 🎯 Objectives

- Develop an AI-powered crop disease detection system
- Detect diseases using leaf images
- Improve farming efficiency through automation
- Provide an easy-to-use solution for farmers
- Reduce dependency on manual inspection

---

# 👨‍💻 Team Members

- Mohammad Areeb
- Ayush Tripathi
- Aman Singh Bohra
- Yash Vinayak Singh

---

# 🎓 Academic Details

### Project Title
**An Image-Based Study on Crop Disease Detection**

### Institution
KIET Group of Institutions, Ghaziabad

### Affiliated To
Dr. A.P.J. Abdul Kalam Technical University, Lucknow

### Session
2025–26

---
