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
![Test Accuracy Screenshot](<img width="656" height="430" alt="image" src="https://github.com/user-attachments/assets/2321b199-2320-4995-9dd2-2f15799ab555" />
)  <!-- ضع صورة من Colab هنا -->

- Achieved **>95% accuracy** on test set

## 🔧 Requirements
See `requirements.txt`

## 📝 Notes
- Loss function defined at `criterion = nn.CrossEntropyLoss()`
- Backpropagation occurs at `loss.backward()`
