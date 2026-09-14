# 5.2 Statement

## Problem Statement

Handwritten digit recognition is a computer-vision and machine-learning
problem in which a system receives an image containing a handwritten
numeral and predicts its class. Handwritten digits can vary in stroke
thickness, shape, slant, and writing style, making manual identification
repetitive and difficult to scale.

The objective of this project is to develop a simple, reproducible, and
understandable digit-classification pipeline that can be executed
locally from the terminal. The system uses the MNIST dataset and a
TensorFlow/Keras neural network to learn patterns associated with digits
0--9 and predict the digit represented by an input image.

## Scope of the Project

The project covers the complete basic machine-learning workflow for
handwritten digit recognition:

-   Loading the MNIST training and test datasets using TensorFlow/Keras.
-   Normalizing the image data before training and evaluation.
-   Building a Sequential neural network with a flattened 28 × 28 input,
    two dense ReLU layers, and a 10-class softmax output.
-   Training the model on MNIST for the configured three epochs.
-   Evaluating the trained model using the MNIST test dataset.
-   Saving the trained model locally as `handwritten.keras`.
-   Reading handwritten digit images from the local `digits` folder.
-   Preparing and inverting the input image before prediction.
-   Predicting the digit using the trained model and NumPy `argmax`.
-   Displaying the processed input image using Matplotlib.

The current project is a local, command-line-based implementation. It
does not include a web application, database, authentication system, or
external API.

## Target Users

The primary target users are:

-   **Students and learners** who want to understand the fundamentals of
    handwritten digit classification and neural networks.
-   **Beginners in machine learning** who want a simple end-to-end
    TensorFlow/Keras project.
-   **Academic users and instructors** who need a compact example for
    demonstrating dataset preprocessing, model training, evaluation,
    model persistence, and image inference.
-   **Developers experimenting with digit recognition** who want a
    lightweight baseline that can later be extended.

## High-Level Features

1.  **MNIST Dataset Loading** -- Loads the standard MNIST
    handwritten-digit training and test datasets.
2.  **Image Preprocessing** -- Normalizes image data and prepares local
    handwritten images for inference.
3.  **Neural Network Classification** -- Uses a Sequential dense neural
    network to classify digits from 0 to 9.
4.  **Model Training** -- Trains the model on the MNIST training data
    for three epochs.
5.  **Model Evaluation** -- Evaluates the model on the MNIST test set
    and reports loss and accuracy at runtime.
6.  **Model Persistence** -- Saves the trained model as
    `handwritten.keras` and reloads it for later use.
7.  **Local Image Inference** -- Reads handwritten digit images from the
    `digits` directory.
8.  **Digit Prediction** -- Produces the most probable digit class using
    `argmax`.
9.  **Visualization** -- Displays the processed input image using
    Matplotlib.
