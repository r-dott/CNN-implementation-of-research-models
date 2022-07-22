# CNN-implementation-of-reasearch-models
implementing models from research papers


1. LeNet5 model
   instead of flattening out the input layer uses multiple convolution layers to scan out desirable features across the image array.
   this feature gives shift invariance to the model.
   there is a steady trend in the architecture, i.e number of filters increases while the kernel size decreases.
   
   applied model:validation accuracy: 99.11%
                 test accuracy: 99>27%
               
               
2. Inception Model
   this model attempts to go deeper in the network. instead of orderwise convolution operations using filters 1x1 3x3 5x5 and pooling..
   this model concatenates the output from eacch of these operations and then further (if needed repeats the process or) flattens it and
   and connects it to dense layers.
   
   applied model:  validation accuracy: 100.0%
                   test accuracy: 99.72%
        