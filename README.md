# Deep-Neural-Network-for-Handwritten-Digit-Recognition-MNIST-

Description: Built and trained a Deep Neural Network (DNN) to classify handwritten digits (0–9) from the MNIST dataset, demonstrating strong foundational knowledge in deep learning architecture design, training, and evaluation.

Preprocessed image data by scaling pixel values to [0,1] and splitting 60,000 samples into training (54,000) and validation (6,000) sets for robust evaluation.

Designed a Feed-Forward Neural Network with a Flatten input layer, two hidden dense layers (50 neurons each, ReLU activation), and a 10-class Softmax output layer.

Compiled the model with Adam optimizer and Sparse Categorical Cross-Entropy loss, training over 5 epochs with a batch size of 100.

Evaluated model performance on 10,000 unseen test images, achieving 96.58% accuracy and 11% test loss, validating effective model generalization and performance.

Tech Stack: Python, TensorFlow (tf.keras, tensorflow-datasets), NumPy
