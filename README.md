# Image Classification using CNN Keras
### Objective: To classify an Image as either Dog or Cat
### Data Source: https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset
### Language: Python 3.0
### Key Concepts:
- To use Convolutional Neural Networks in the classification of Images, in this case Binary Classification
- The dataset consists of 2 categories: Dogs and Cats
- The images for both the categories were in separate folders.
- The data is quite balanced. There is an equal number of images in the two categories for both Training and Test datasets.
- Implementation is done using Keras API of Tensorflow
- Image Augmentation like flips, zoom, shear etc have been done to avoid overfitting
- Model Evaluation is done to analyse where has model performed well, and where has it misclassified images the most.
- Set FAST_RUN = True if fast run is required. In this case, the number of Epochs will be set to 5 only.
