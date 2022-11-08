# fashion_mnist-image-processing
A python notebook for fashion image processing.  We use Tensorflow (preferably a veersion higher than 2.1)

# Used Dataset
We use the popular fashiom-MNIST which can be found in [fashiom-MNIST](http://yann.lecun.com/exdb/mnist/)

# Processing Steps
Our image processing approach is based on the convolution paradign. We stack multiple convolutional layers on top of each other to extract features from images.
## Convolution
we use kernels of size 3

## Stride
we use stride that equals 1, which is simply the step between convolutions.

## padding
We use padding= SAME which means with our stride of 1, the layer's outputs will have the same spatial dimensions as its inputs.

## DepthMaxPool
We select the max value when pooling the output of convolution which helps in accetuating features.

## Dropout
Dropout is very helpful to avoid overfittng our data.
