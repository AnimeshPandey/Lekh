# Lekh
Lekh aims to develop a Machine Learning Program that recognizes hand written text in English language.

The project should be able to correctly recognize hand written text just by the the digital image data that it receives. The software aims in the direction of providing a more accurate and more smooth experience of handwriting recognition for use in smart gadgets of the age.

So far, we have achieved this using some of the most widely used Machine Learning Algorithms like K-Nearest Neighbor Classification, Support Vector Machine and Random Forest Classifier, whose performances are compared below. Further, we hope to increase our efficiency with Deep Learning algorithm, multilayered Convolutional Neural Network using Keras with Theano and Tensorflow.

# Requirements

* Python 3.5 +
* Scikit-Learn (latest version)
* Numpy (+ mkl for Windows)
* Matplotlib

# Usage

**1.** Download the four MNIST dataset files from this link:

```
http://yann.lecun.com/exdb/mnist/
```

**2.** Unzip and place the files in the dataset folder inside the MNIST_Dataset_Loader folder under each ML Algorithm folder i.e :

```
KNN
|_ MNIST_Dataset_Loader
   |_ dataset
      |_ train-images-idx3-ubyte
      |_ train-labels-idx1-ubyte
      |_ t10k-images-idx3-ubyte
      |_ t10k-labels-idx1-ubyte
```

Make sure that those files have the exact same names as these. Do this for SVM and RFC folders and you should be good to go.

**3.** To run the code, navigate to one of the directories for which you want to run the code using command prompt:

```
cd 1. K Nearest Neighbors/
```

and then run the file "knn.py" as follows:

```
python knn.py
```

or 

```
python3 knn.py
```

This will run the code and all the print statements will be logged into the "summary.log" file.

**NOTE: If you want to see the output to print on the Command prompt, just comment out line 16, 17, 18, 106 and 107 and hence you will get all the prints on the screen.**

Alternatively, you can also use PyCharm to run the code and run the ".py" file in there.

Repeat the steps for SVM and RFC code.