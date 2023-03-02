# Quantum-MNIST-Classification

Image Classification on Fashion MNIST with TensorFlow-Quantum and Cirq
About the Dataset and QML

The original MNIST dataset contains a lot of handwritten digits. People from AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset they would try on. “If it doesn’t work on MNIST, it won’t work at all”, they said. “Well, if it does work on MNIST, it may still fail on others.” Fashion-MNIST is intended to serve as a direct drop-in replacement for the original MNIST dataset to benchmark machine learning algorithms, as it shares the same image size and the structure of training and testing splits.

We shall perform QML on Fashion MNIST dataset using TensorFLow Quantum and Cirq.

TensorFlow-Quantum is a great place to start learning QML and get into this amazing field. TensorFlow Quantum (TFQ) is a quantum machine learning library for rapid prototyping of hybrid quantum-classical ML models.TensorFlow Quantum focuses on quantum data and building hybrid quantum-classical models. It integrates quantum computing algorithms and logic designed in Cirq, and provides quantum computing primitives compatible with existing TensorFlow APIs, along with high-performance quantum circuit simulators.

Cirq is a Python software library for writing, manipulating, and optimizing quantum circuits, and then running them on quantum computers and quantum simulators. Cirq provides useful abstractions for dealing with today’s noisy intermediate-scale quantum computers, where details of the hardware are vital to achieving state-of-the-art results.

Today's(NISQ Era) Quantum Computer are not very powerful and have various limitations. Also, the field of Quantum Machine Learning is currently evolving. To keep things simple, we will modify the Fashion MNIST dataset by making classification on only two classes - Sandal and Ankle boot. The reason to choose these classes is that they are similar to each other and therefore, it ascertains that the classification problem doesn't become very easy. The image shape in the provided dataset is (28,28), but we need to downscale the images to classify them using QML due to the hardware restrictions. We will downscale the images so that they have the shape (4,4).

Number of Images in the Train Dataset - 10200

Number of Images in the Validation Dataset - 1800

Number of Images in the Test Dataset - 2000

Size of each Image - (2,2)

Type of Image - Grayscale Image

Number of Labels - 2

Label Description

5 Sandal

9 Ankle boot
