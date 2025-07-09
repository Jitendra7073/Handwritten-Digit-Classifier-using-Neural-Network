
<center> 
<h1> HANDWRITTEN DIGIT CLASSIFIER </h1>

<i>Detect Digits Instantly from Drawings or Uploaded Images</i>

**Built with the tools and technologies:**</center>

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-purple)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Pillow](https://img.shields.io/badge/Pillow-Image%20Processing-lightgrey)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

---

##  Overview

**Handwritten Digit Classifier** is a machine learning project that trains a custom-built 2-layer neural network to recognize handwritten digits (0–9). It uses MNIST-style image data and allows predictions from **uploaded 28x28 grayscale images**.

---

###  Why Handwritten Digit Classifier?

This project is ideal for:

- **Beginners learning ML & deep learning fundamentals**
- **Practicing image classification without heavy frameworks**
- **Understanding custom neural networks from scratch**

---

##  Features

-  **Trains a Fully Connected Neural Network** (2-layer NN)
-  **Upload 28x28 grayscale image** to recognize digits
-  **Implements ReLU, Softmax, One-Hot Encoding, Backpropagation**
-  **Prints model accuracy live during training**
-  **Works entirely inside Jupyter Notebook**

---

##  Getting Started

###  Prerequisites

- Python 3.x
- Jupyter Notebook

---

###  Installation

```bash
# Clone the repository
git clone https://github.com/Jitendra7073/Handwritten-Digit-Classifier-using-Neural-Network.git
```

```bash
# Navigate to the project folder
cd Handwritten-Digit-Classifier-using-Neural-Network
```

```bash
# Install dependencies
pip install numpy pandas matplotlib pillow scipy
```

### Predict from Image File

```python
predict_digit_from_image("Testing_data/digit_0.png")
```

 Output:
```
We found digit 7
```
