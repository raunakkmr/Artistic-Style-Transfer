# Artistic-Style-Transfer
PyTorch implementation of Artistic Style Transfer.

* The design is based on Stanford CS 231N's [assignment](http://cs231n.github.io/assignments2018/assignment3/).
* I use small image sizes (192 x 192) - the optimization is much faster and it's easier to experiment on my local machine.
* I use SqueezeNet for computational efficiency. It's fairly straightforward to modify the code to use a different network like VGG - change the pretrained model, and content/style indices and weights. You might have to use different hyperparameters.
