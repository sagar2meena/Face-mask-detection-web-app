# Face-mask-detection-web-app
Face Mask Detection web application built with Flask, Keras-TensorFlow, OpenCV. It can be used to detect face masks both in images and in real-time video.

# demo
https://www.google.com/url?sa=i&url=https%3A%2F%2Fdev.to%2Fchandrikadeb7%2Fface-mask-detection-my-major-project-3fj3&psig=AOvVaw0N1Y4nw3vnfvrL85gluUZP&ust=1647445176720000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCLCVstq5yPYCFQAAAAAdAAAAABAJ
# goal
The goal is to create a masks detection system, able to recognize face masks both in images, both in real-time video, drawing bounding box around faces. In order to do so, I finetuned MobilenetV2 pretrained on Imagenet, in conjunction with the OpenCV face detection algorithm: that allows me to turn a classifier model into an object detection system.

#Technologies
Keras/Tensorflow
OpenCV
Flask
MobilenetV2

# usage
You have to install the required packages, you can do it:

via pip pip install -r requirements.txt
or via conda conda env create -f environment.yml
Once you installed all the required packages you can type in the command line from the root folder:

python wsgi.py
and click on the link that the you will see on the prompt.

# Data
The dataset used for training the model is available kaggle datasets download -d omkargurav/face-mask-dataset.
