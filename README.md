### Neural network from scratch
This project is an implementation of two-layered deep neural network without using any standard deep learning libraries. The network is trained to recognize pictures of cats(0) vs dogs(1) via binary classification. Pictures are loaded and preprocessed using OpenCV library. All component functions of the network are written in python+numpy.

### Installation
To run this project, you will need Python 3 and the following packages:
- NumPy
- OpenCV
- Matplotlib
- OS

### Data
Data used for the project is a small portion of images (1000/25000 for train and 100/12500 for test) from this kaggle competition:
- https://www.kaggle.com/competitions/dogs-vs-cats/data
As the implementation of the network is structured as L-layered it can handle more data after changing a few hyperparameters.

### Results
The neural network achieves an accuracy of 83% on the training set and an accuracy of 82% on the test set.
