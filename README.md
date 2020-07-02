# Keras_using_pretrained_VGG16
Part of MSc project. Involves using VGG16 pretrained on ImageNet



## Using VGG16 pretrained on *ImageNet* for a new task by replacing the classifier at the top of the network

The **jupyter notebook** featured in this repo shows how to use VGG16 (pretrained on ImageNet) for a new classification task.
It involves using a new dataset and replacing the classifier (the fully connected layers at top of the network) with a new classifier.
The base of the network (convolutional base) is frozen and the new classifier is trained using the new dataset.
