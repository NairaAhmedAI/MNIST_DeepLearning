# MNIST Handwritten Digit Classification

This project builds a **Neural Network** using PyTorch to classify handwritten digits from the MNIST dataset.

## 📚 Dataset
- 60,000 training images
- 10,000 test images
- Images are 28x28 pixels grayscale

## 🏗️ Model Architecture
- Input: 28x28 pixels
- Hidden Layer 1: 128 neurons, ReLU
- Hidden Layer 2: 64 neurons, ReLU
- Output: 10 neurons, for digits 0-9
- Loss: Cross-Entropy
- Optimizer: Adam

## 📊 Results
![Test Accuracy Screenshot](https://github.com/user-attachments/assets/06739d4d-3f13-4d45-93ee-df6c7bbe1132)
![Confusion Matrix](https://github.com/user-attachments/assets/1766d364-c379-445f-a6c6-398fca335636)


- Achieved **>95% accuracy** on test set

## 🔧 Requirements
See `requirements.txt`

## 📝 Notes
- Loss function defined at `criterion = nn.CrossEntropyLoss()`
- Backpropagation occurs at `loss.backward()`
