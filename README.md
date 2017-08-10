# LeafClassifier
This project is meant to classify a leaf based on a picture from a smart phone.  This is accomplished by using Tensorflow mobile and the Keras framework.  The data used for training is from [Leaf Snap](leafsnap.com/dataset/).  The skeleton of the android application is provided as an example application in [Tensorflow mobile](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android/).
## Current State
Classifier works at 52% accuracy over only 2 epochs of training on pre-segmented photos
## TODO
- Configure Nvidia Tensorflow for faster training
- Train over more epochs to ensure validity of pre-segmented model
- Train model to perform edge detection of color jpeg
- Combine both models and validate
- Port trained network to simple android application
- Real world testing
- Expand app asthetics
