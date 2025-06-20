# emotion-image-_classifier
# Emotion Classifier Using CNN

This project classifies images as **Happy** or **Sad** using a Convolutional Neural Network (CNN).  
It was built and trained using **Kaggle Notebooks** and tested on custom images from the internet.

## 🔧 Tools Used
- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- Kaggle GPU Notebook

## 📁 Dataset
- Source: Custom dataset uploaded to Kaggle
- Classes: `happy people`, `sad people`
- Preprocessing: Removed blurry and faceless images using OpenCV

## 🧠 Model Summary
- Input Size: 224x224
- Layers: Conv2D, MaxPooling, Dense, Dropout
- Loss Function: Binary Crossentropy
- Optimizer: Adam

## 📈 Results
- Accuracy: 97% on training data
- Validation loss converged smoothly

## 🖼️ Example Prediction
<img src="example_output.jpg" alt="Model prediction output" width="300"/>

## 🚀 How to Run
1. Upload your images to Kaggle `/kaggle/input/`
2. Load your trained model:
   ```python
   model = tf.keras.models.load_model('/kaggle/working/imageclassifier.h5')
