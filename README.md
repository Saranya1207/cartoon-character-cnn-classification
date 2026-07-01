# Cartoon Character Recognition using Deep Learning (CNN)
Classifies Tom and Jerry cartoon images using a Convolutional 
Neural Network built with TensorFlow and Keras.

## Dataset
Tom and Jerry Image Classification dataset from Kaggle
(balabaskar/tom-and-jerry-image-classification)

## Tools & Libraries
Python, TensorFlow, Keras, NumPy, Matplotlib, Google Colab

## Model Architecture
- Conv2D (32 filters, 3x3) + MaxPooling
- Conv2D (32 filters, 3x3) + MaxPooling
- Flatten
- Dense (64, ReLU)
- Dense (1, Sigmoid) — binary classification

## Steps Performed
- Dataset download from Kaggle API
- Image loading and resizing to 100x100
- Normalization (pixel values divided by 255)
- Train/Validation split (80/20)
- CNN model building using Sequential API
- Model compilation using Adam optimizer, binary crossentropy loss
- Model training and accuracy evaluation

## How to Run
Open cartoon_cnn_classification.ipynb in Google Colab
Upload your kaggle.json API key when prompted
