# Neural Network from Scratch using NumPy

This repository contains an implementation of a simple feedforward neural network using only NumPy. It was built as a learning project to understand the fundamentals of neural networks, backpropagation, and gradient descent.

## 🎯 Features

- Built from scratch with NumPy (no deep learning frameworks)
- Implements:
  - Feedforward pass
  - Stochastic Gradient Descent (SGD)
  - Backpropagation
- Achieves **95% accuracy** on the MNIST test dataset
- Inspired by Michael Nielsen’s book: *Neural Networks and Deep Learning*

## 📦 Requirements

- Python 3.x
- NumPy

Install dependencies:

```bash
pip install numpy pandas scikit-learn
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/abhuday-sudhir/Neural-Network-using-Numpy.git
   cd nn
   ```

2. **Prepare the MNIST dataset**

   Download the MNIST dataset from [Yann LeCun's website](http://yann.lecun.com/exdb/mnist/) or use any helper script included.


   ```
3. **Run training manually**

   In your main script or a Jupyter notebook, you can initialize and train the network like this:

   ```python

   training_data, validation_data, test_data = load_data_wrapper()
   net = Network([784,x,y, 10]) #Replace x and y with required neurons in hidden layer
   net.SGD(training_data, epochs=30, mini_batch_size=10, eta=3.0, test_data=test_data)

   ```

## 📊 Results

The neural network achieves **~95% test accuracy** on the MNIST dataset using a simple architecture ( `784-20-20-10`) after a 50 epochs of training.

## 📚 Reference

This project follows and implements the algorithms described in:

- Michael A. Nielsen — [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)


---

Made with ❤️ for learning and experimentation.
