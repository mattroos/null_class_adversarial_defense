# null_class_adversarial_defense
Code to replicate the arxiv technical report:  
[Utilizing a null class to restrict decision spaces and defend against neural network adversarial attacks](https://arxiv.org/)

This code in this repo was used to build, train, and test all the models reported on in the paper. Is also generates all the figures.

### Main package requirements

- Tensorflow 2.1
- Numpy
- Pandas
- Matplotlib

### MNIST data

MNIST data was downloaded from Yann LeCunn's website: http://yann.lecun.com/exdb/mnist/

You'll need the Python mnist package to load the data
```
pip install mnist
```

In the train_mnist_multiple_models.ipynb and fgsm_mnist_multiple_models.ipynb files, set the path of the mnist directory to the location where you stored the files, e.g.
```
dir_mnist = './mnist'
```

### Jupyter notebook files

In order to import the .ipynb files without having to convert them to .py files, install these packages:
```
pip install import-ipynb
pip install nbformat
```

## Training models


## Experiments and figures

