# Artistic-Style-Transfer
PyTorch implementation of Artistic Style Transfer.

* Original paper : [Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) by Gatys et al.
* The design is based on Stanford CS 231N's [assignment](http://cs231n.github.io/assignments2018/assignment3/).
* I use small image sizes (192 x 192) since the optimization is much faster and it's easier to run experiment on my local machine.
* I use SqueezeNet for computational efficiency. It's fairly straightforward to modify the code to use a different network like VGG - change the pretrained model, and content/style indices and weights. You might have to use different hyperparameters.
