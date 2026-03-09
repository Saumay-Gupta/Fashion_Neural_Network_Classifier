# Fashion MNIST Neural Network Classifier

## Overview

This project implements a simple **Neural Network using TensorFlow** to classify images from the **Fashion MNIST dataset**.  
The model learns to recognize different types of clothing items such as shirts, shoes, bags, and trousers from grayscale images.

This project was built as part of my **Machine Learning learning journey**, focusing on understanding neural networks, activation functions, loss functions, and optimizers.

---

## Dataset

The model uses the **Fashion MNIST dataset** available through TensorFlow.

### Dataset Details

- **60,000 training images**
- **10,000 test images**
- **28 × 28 grayscale images**
- **10 clothing categories**

### Classes

| Label | Clothing Item |
|------|---------------|
| 0 | T-shirt / Top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle Boot |

---

## Model Architecture

| Layer | Type | Neurons | Activation | Purpose |
|------|------|---------|-----------|---------|
| 1 | Flatten | - | - | Converts image to vector |
| 2 | Dense | 128 | ReLU | Feature extraction |
| 3 | Dense | 64 | ReLU | Feature refinement |
| 4 | Dense | 10 | Softmax | Class prediction |

---

### Activation Functions

- **ReLU** – used in hidden layers  
- **Softmax** – used in the output layer for multi-class classification  

---

## Training Configuration

- **Optimizer:** Adam  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Metric:** Accuracy  
- **Epochs:** 10  

---

## Libraries Used

- TensorFlow
- NumPy
- Matplotlib *(optional for visualization)*

### Install Dependencies

```bash
pip install tensorflow numpy matplotlib
```

--- 

### Results
The neural network successfully learns to classify clothing items from images.
Training improves accuracy as the model learns patterns in the dataset.


--- 
### Author
Saumay Gupta

This project is part of my Machine Learning learning journey.
