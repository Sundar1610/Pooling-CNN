# CNN Pooling Techniques Comparison

## Overview
This project explores the impact of different pooling techniques in Convolutional Neural Networks (CNNs) using TensorFlow and Keras. Specifically, it compares **Max Pooling** and **Average Pooling** on the CIFAR-10 dataset. The goal is to analyze their effects on model performance in terms of accuracy.

## Dataset
The **CIFAR-10** dataset is used, consisting of 60,000 32x32 color images in 10 classes, with 50,000 training images and 10,000 test images.

## Model Architecture
- **Convolutional Layers**: Two convolutional layers with ReLU activation.
- **Pooling Layers**: Either Max Pooling or Average Pooling is applied after each convolutional layer.
- **Fully Connected Layers**: A dense layer with 64 neurons followed by a final softmax layer for classification.

## Training Process
- The model is trained for **5 epochs** using the Adam optimizer and sparse categorical cross-entropy loss.
- Batch size is set to **64**.
- Validation accuracy is tracked for both pooling methods.

## Results & Visualization
- After training, validation accuracy is printed for each epoch.
- A comparison plot is generated to visualize accuracy trends across epochs for both pooling techniques.

## Usage
### Dependencies
Ensure you have the following installed:
```bash
pip install tensorflow matplotlib numpy
```
### Running the Script
Simply execute the Python script:
```bash
python cnn_pooling_comparison.py
```

## Conclusion
This project helps in understanding the role of pooling techniques in CNNs by comparing their effects on model accuracy.

