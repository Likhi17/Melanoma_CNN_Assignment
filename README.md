# Project Name : Multiclass classification model using a custom convolutional neural network in TensorFlow

## Problem statement: 
  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
  
## General Information:

### Multi-Class Classification:
We have a dataset with samples belonging to multiple, mutually exclusive classes (e.g., classifying images of cats, dogs, and birds).
The goal is to train a model that can analyze unseen data points and predict the most likely class it belongs to.
Common applications include image recognition, spam filtering, sentiment analysis, and many more.

### Convolutional Neural Networks (CNNs):
Inspired by the visual cortex of the human brain, CNNs are a powerful type of neural network architecture specifically designed for image recognition tasks.
They excel at capturing spatial relationships and extracting features from data with a grid-like structure (like images).
Key components:

### Convolutional layers: 
Apply filters to the input data, extracting features like edges, shapes, and textures.
Pooling layers: Downsample the data to reduce dimensionality and introduce translational invariance (less sensitive to small shifts).
Activation functions: Introduce non-linearity to the network, allowing it to learn complex relationships between features.

### TensorFlow:
An open-source framework by Google for numerical computation and large-scale machine learning.
Provides high-level APIs like tf.keras to simplify building and training neural networks.
Offers functionalities for data loading, preprocessing, model definition, compilation, training, and evaluation.

## Libraries & Technologies used

- Keras
- Tensforflow
- Pandas
- Numpy
- Matplotlib 
- Anaconda
  
## Layers used

- 3 Convolutions layers
- 1 rescalling layer
- 3 Dropout layesrs
- 2 Dense layers

## Activation functions
- Relu
- Softmax with dense layer

## Conclusions

- Multi-class classification with custom CNNs in TensorFlow provides a versatile and powerful tool for tackling problems that involve categorizing data into multiple classes.
- Yes the overfitting issue is solved by using the class rebalancing , the traning accuracy is appx to 88% where as the testing accuracy is to 83%.

accuracy: 0.8843
loss: 0.3000
val_accuracy: 0.8270
val_loss: 0.6691







## Contact
Created by [@githubusername] - @Likhi17
