# Babby Nets

This is the code I used to prepare for & present the talk "Write Your Own Neural Net" in the UCLA GSO Math Seminar, January 18 2024.

The files

* `nnet0.ipynb`
* `nnet1.ipynb`
* `nnet2.ipynb`
* `nnet3.ipynb`

were written ahead of time, and the file `welldoitlive.ipynb` was a version of `nnet0.ipynb` that was live-coded during the talk.

## nnet0.ipynb

This implements a very small network (2 inputs, 1 hidden layer with 2 neurons, 1 output) which gets trained via very brutal raw gradient descent. Currently it's set up to approximate the function (x,y) ↦ xy.

## nnet1.ipynb

This implements an arbitrary dense neural net, again trained with gradient descent (this time with actual backpropogation).

## nnet2.ipynb

This introduces tensorflow, and trains a small network to approximate (x,y) ↦ xy.

## nnet3.ipynb

This implements an MNIST classifier using Tensorflow. After training, you can use the `make_prediction()` function to classify the contents of the image `handdrawn.bmp`.
Currently `handdrawn.bmp` contains nonsense, but you should replace this with a white digit drawn on a black background.
