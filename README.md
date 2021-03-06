# ImageNet32-tensorflow
Implementation of the Wide Residual Networks used to classify the downscaled ImageNet dataset. This model in TensorFlow achieves the same Top-1 and Top-5 errors as reported in the paper: https://arxiv.org/abs/1707.08819 and runs 2-3 times faster than the Theano version. Furthermore, the bottleneck residual building block is also implemented which improves the accuracy to some extent compared to the baseline residual block.

The code is based on:
https://github.com/PatrykChrabaszcz/Imagenet32_Scripts
https://github.com/tensorflow/models/tree/master/official/resnet

# Dataset
http://image-net.org/download-images
