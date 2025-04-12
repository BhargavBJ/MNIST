# 🧠🔢 MNIST CNN Digit Classifier

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify handwritten digits from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/). It is designed to be simple yet powerful, and supports both training and inference, including prediction on custom user-uploaded images.

---

## 🚀 Features

- ✅ CNN architecture built from scratch using PyTorch
- 📈 Achieves ~98% test accuracy on MNIST
- 🖼️ Upload and classify your own digit images (e.g., `.png`, `.jpg`)
- 🔍 Includes visualization of preprocessing steps and predictions
- 📉 Evaluation with loss and accuracy tracking
- ⚡ GPU acceleration with CUDA support (via Google Colab)

---

## 📚 Dataset

- **MNIST**: A standard benchmark dataset of 28x28 grayscale images of handwritten digits (0–9).
- Automatically loaded via `torchvision.datasets.MNIST`.

---

## 🧪 How to Use (Google Colab)

> This project is developed and runs entirely in **Google Colab**, so no local setup is required.

1. 📂 Clone or download the repository.
2. 🧭 Open `mnist_cnn_digit_classifier.ipynb` in **Google Colab**.
3. ▶️ Run each code cell in order:
   - Trains the CNN model from scratch
   - Evaluates performance on the test set
   - Accepts custom digit images for prediction
4. 📤 Upload a test image (28x28 or will be resized).
   - Make sure it's a **black digit on a white background**.
   - Inversion is handled automatically if needed.
5. 🔍 View the predicted result with visual feedback.

---

## 🧱 Project Structure
MNIST-CNN-Digit-Classifier/ ├── mnist_cnn_digit_classifier.ipynb # Main Colab notebook ├── README.md 
# Project overview and instructions 
└── images/ 
 (Optional) Folder for custom test images └── 1.jpg
 
---

## 🛠 Requirements (For Local Use)

> If you want to run it locally instead of Colab, install the following(only if your device has a GPU):

```bash
pip install torch torchvision matplotlib pillow
```

# 📬 Author
Built with ❤️ using PyTorch & Google Colab by Bhargav.
