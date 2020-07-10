# Image-classifier-for-SVHM-dataset

## SVHN Dataset
SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting.
It comes from a significantly harder, unsolved, real world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.

Dataset is available at this link: [`Training Dataset`](http://ufldl.stanford.edu/housenumbers/train_32x32.mat) , [`Test Dataset`](http://ufldl.stanford.edu/housenumbers/test_32x32.mat)

**Overview**
* 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.
* Dataset contain RGB images of size 32x32 and labels corresponding to them. 
* There are 73257 training examples and 26023 test examples. 
* The images in the Dataset is shown below.

![Images in Dataset](http://ufldl.stanford.edu/housenumbers/32x32eg.png)

## Model
There are two simple models used, one is MLP and other is CNN. Performance of both these model are compared and some random prediction from these models are also shown.
