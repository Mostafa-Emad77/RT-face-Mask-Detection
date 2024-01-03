# Real Time CNN Mask Detection Project

This project uses a convolutional neural network (CNN) to detect whether people are wearing masks or not in real time. The CNN is trained on a dataset of face images with and without masks, and achieves high accuracy on both the training and test sets. The model is then deployed using OpenCV to capture video frames from a webcam and make predictions on them.

## Dataset

The dataset used for this project is the [Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset), which contains 12,000 images of people with and without masks. The images are divided into two classes: `with_mask` and `without_mask`. The dataset is split into 80% training and 20% test sets.

## Model

The model used for this project is a CNN with four convolutional layers, followed by max pooling, dropout, and fully connected layers.
The model is implemented using Keras and TensorFlow, and the code can be found on [Kaggle](https://www.kaggle.com/code/mostafaemad123/face-mask-detection-cnn). The model is trained for 10 epochs, and achieves 98% accuracy on the training set and 97% accuracy on the test set.

## Deployment

The model is deployed using OpenCV, which is a library for computer vision and image processing. The code uses the OpenCV functions to access the webcam, read the video frames, and display the results. The code also uses the Haar cascade classifier to detect faces in the images, and then crops and resizes them to fit the model input. The model then predicts whether the face is wearing a mask or not, and draws a bounding box and a label around it. The code can be run on any system with a webcam and the required libraries installed.

Here is the demo video : https://www.linkedin.com/posts/mostafa-emad-al-din-5361831b9_exciting-update-happy-to-share-that-ive-activity-7136501714605461504-3Jzw/?utm_source=share&utm_medium=member_desktop
