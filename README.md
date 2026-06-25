# Neural Network Clothing Image Classification

TensorFlow/Keras classifier for the Fashion-MNIST dataset. The model takes 28x28 grayscale clothing images and predicts one of ten clothing categories such as shirts, trousers, coats, sandals, sneakers, bags, and ankle boots.

## What This Demonstrates

- Loading and preprocessing the Fashion-MNIST dataset.
- Normalising pixel values from `[0, 255]` to `[0, 1]`.
- Building a simple feed-forward neural network with Keras.
- Training with Adam and sparse categorical cross-entropy.
- Evaluating test accuracy and visualising predictions.

## Model Architecture

```text
Input: 28x28 grayscale image
Flatten: 784 features
Dense: 128 neurons, ReLU activation
Dense: 10 neurons, Softmax activation
```

## Run

```bash
pip install tensorflow matplotlib numpy
python3 main.py
```

The script trains for 5 epochs, evaluates on the test set, prints test accuracy, and displays a few sample predictions.

## Dataset

The project uses `keras.datasets.fashion_mnist`, so the dataset is downloaded automatically by Keras on first run.

## Status

Learning project focused on understanding the basic neural-network training loop: data loading, preprocessing, model definition, compilation, training, evaluation, and prediction.
