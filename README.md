# notes
======
#### items are listed by alphabetical order

### Activation
* sigmoid 
* ReLU 
* tanh 
### Architecture/Structure
* Feedforward/Backpropagation
* Directed acyclic graph
### Gradient
* Gradient descent
* Gradient vanishing
* Gradient explosion
* Gradient boosting
* Gradient clipping

### Layers
* conv
** strides -- acts as shift step
** kernal size -- [width,height,channels]
** padding -- when the image res and kernal size does not match
** dilated convolution
** separable from 2d to 1d
** transposed/de/inverse convolution
** output of of conv layer depth == numbers of conv kernals
** checkerboard effect/
* activation
* pooling
** mean pooling
** max pooling
** median pooling
** random pooling

* fully connect
* 1x1 conv - from [w,h,c,k] to [w,h,c,k'<k or k'>k]
### Overfitting

### Normalization
* Linear/std/nonlinear
* Local response normalization, boost active response 
* Batch normalization, constraint intermediate value within network
* Layer normalization,
* Instance 
* Group normalization, improve robustness in small batches

### Optimizers
* ADAM
* SGD

### Regularization
* L1
* L2
* dropout
