#  Breast Cancer Classification using CNN

##  Overview
This project uses a Convolutional Neural Network (CNN) to classify breast cancer histology images as benign or malignant.

##  Objective
To build a deep learning model capable of detecting cancer from medical images with high accuracy.

##  Dataset
- IDC (Invasive Ductal Carcinoma) dataset
- Image size: 50x50 pixels
- Classes:
  - 0 → Benign
  - 1 → Malignant

## ⚙️ Model Architecture
- Convolutional Layers (Feature Extraction)
- MaxPooling Layers (Dimensionality Reduction)
- Flatten Layer
- Dense Layers
- Dropout (Overfitting prevention)

##  Training Details
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Epochs: 5 & 10
- Batch Size: 32

##  Performance
- Accuracy improved from ~85% to ~90%+
- Model showed good generalization

##  Key Concepts
- Feature extraction from images
- Deep learning using CNN
- Overfitting prevention using dropout

##  Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

##  Outcome
Successfully built a CNN model for cancer detection, demonstrating the power of deep learning in medical imaging.
