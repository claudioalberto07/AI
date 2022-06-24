# Artificial Inteligence

### Introduction
Convolution is the mathematical operation that gives the layers of 
a CNN their unique structure. In next lines, you'll see 
why this structure is so effective at solving computer vision 
problems.

We will apply these ideas to the problem of image classification: 
given a picture, can we train a computer to tell us what it's a 
picture of? You may have seen apps that can identify a species of 
plant from a photograph or classify the type of vehicles. 
That's an image classifier!

### The convolution classifier
A CNN to image classifier can be divided in two parts: 
- Convolution Base: is used to extract features from image. The 
base of this operation is the convolution.
The features can be an line, color texture, shape, pattern or an
complex combination.
- Dense head: is used to classify/determine the class of an image.
The base of this operation is dense layers.

### Training an classifier
The goal of the training an neural network to image classifier is 
make her learn two things:
- Which features to extract from an image(base).
- Which class goes with what features(head).

To training an neural network we can use an pretrained network base.
With this, we can:
- Transfer base learning.
- Attach fresh layers to learn.
- Training the classifier with little dataset.

### Feature Extraction

The feature extraction consists in three basic operations:
- Convolution: FILTER an image for particular feature.
- RELU: DETECT that feature within the filtered image.
- Pooling: CONDENSE the image to enhance the features.

This operations are able to isolate ssome particular characteristics
of the original images(can be horizontal lines, vertical lines, regions).

#### Filter with Convolution
A convolution layer carrie out the filtering step. This layers needs
like parameters the number of filters.
- Filters are the number of how many feature maps you want it to create
as output.


