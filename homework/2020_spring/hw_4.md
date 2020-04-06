### Homework 4

**Problem 1**

Using only ```numpy```, implement the function ```conv2d```.  It takes as input ```input_mat``` and ```kernel_mat``` and outputs ```output_mat```.  All variables 
are square matrices.  It should compute the convolution of ```input_mat``` with the kernel ```kernel_mat``` using valid padding.

**Problem 2**

Using only ```numpy```, implement the function ```maxpooling2d```. It takes as input ```input_mat``` and ```s``` and outputs ```output_mat```.
The variables ```input_mat``` and ```output_mat``` are square matrices and ```s``` is an integer.  It should compute the maxpooling operation 
on ```input_mat``` using window of shape ```s``` times ```s```.

**Problem 3**

You will adapt the notebook [using VGG16 conv base for feature extraction, using data augmentation, not using dropout, fine-tuning](https://colab.research.google.com/drive/1F-RWvoxH8MmT7c1UmNy41iuOp-ejiLoF).
You will have to replace the VGG16 conv base by new conv bases. You should not use VGG19.

You should create two notebooks.  Both should use the same conv base, unfreeze the same number of layers of the conv_base, 
but use different classifiers.