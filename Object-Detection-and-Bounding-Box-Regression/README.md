 <h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Object-Detection-and-Bounding-Box-Regression/blob/main/Images/Logotipo.png alt="FLOWER MULTI-LABEL CLASSIFICATION" width="300">
<br>
<br>
MULTI-CLASS OBJECT DETECTION AND BOUNDING BOX REGRESSION WITH KERAS, TENSORFLOW, AND DEEP LEARNING
</h1>

<p align="justify">
My project is based on the development of a machine learning using the concepts of Convolutional Neural Network and object detection with TensorFlow Framework and Kareas API.

In Deep Learning, certain layers are responsible for certain recognition patterns, such as edges, textures, and so on. 

The idea of Convolutional Netowork is based on this concept in the analysis of our supposed image, and with the values of pixels present in this image, we will use filters, also called Kernel, which will perform Convolutional operations to obtain other values in a smaller matrix, and thus recognize the patterns needed for each layer. 
</p>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Cat-and-Dog-classification-TensorFlow/blob/main/Images/CNN%20Model.png alt="CNN model" width="550" height = "250">
<br>
</h1>

<p align="justify">
However, for the development of this project, the Transfer Learning technique was used. We downloaded the pre-trained parameters of the VGG 16 Classic Neural Network with the ImageNet Database, and removed the one-dimensional layers at the end, to add the convenient layers for the predictions of our model.

Furthermore, in this project we also perform the detection of the object to be categorized by drawing a rectangle from the bounding box.

Therefore, we have two types of predictions to be made in the final stages of the model, the class predictions and the Bounding Boxes predictions.
</P>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Object-Detection-and-Bounding-Box-Regression/blob/main/Images/transfer%20learning%20example.png alt="DEEP NEURAL NETWORK" width="600" height = "270">
<br>
</h1>
<p align="center">
Figure from: https://www.researchgate.net/figure/Example-of-how-transfer-learning-works-in-this-setting-the-last-layer-classification_fig6_332092821 
</p>

<p align="justify">
In this project the RELU activation function was used in all the other layers of bounding box regression, and only in the last layer the Sigmoid is used to ensure our output predicted values are in the range [0, 1]. Unlike my other projects, here it was not necessary to build the activation functions or the Forward or Backward propagation process, the framework is responsible for this type of process because VGG 16, and it is up to the developer to build the model and process the data.

Still in the last steps, we observe a Softmax operation because we are making a categorical classification, and the Softmax function is efficient for these cases.
</p>

<p align="justify">
Moreover, it is important to note that this project is a CNN model and Object Detection for study and knowledge of how machine learning works for simple situations. Even using frameworks the result will depend on how you design your Convolutional Neural Network, always watching Overfiting or Underfiting and studying how to improve your results.

Thanks, and enjoy.

</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## Features
[//]: # (Add the features of your project here:)
The programming language used was Python 3 in Jupyter environment, using the libraries highlighted below whose documentation is in the links just by clicking on them. In the next topic you will have a description of how you can install the libraries and test the code.

- 📁 [TensorFlow](https://www.tensorflow.org/api_docs/python/tf/all_symbols) — Framework used for CNN model.
- 📁 [Keras](https://keras.io/api/) — Deep learning API working together with machine learning platform TensorFlow.
- 📁 [Numpy](https://numpy.org/) — Python library used for the calculations of multidimensional matrices.
- 📁 [Matplotlib](https://matplotlib.org/3.3.3/contents.html) — Library used to check the tests.
- 📁 [Os](https://docs.python.org/3/library/os.html) — Library used to browse directories from our PC.
- 📁 [random](https://docs.python.org/3/library/random.html) — Library used to generate pseudo-random numbers.
- 📁 [OpenCV](https://opencv.org/) — Library used to modify and load our images.
- 📁 [imutils](https://pypi.org/project/imutils/) — Library used to modify our images.
- 📁 [pathlib](https://docs.python.org/3/library/pathlib.html) — Library used to flow from directories.
- 📁 [Scikit-learn](https://scikit-learn.org/stable/user_guide.html) — Library used to preprocessing our data.

## Getting started

To use this project, we need to do some library installations. Let's see below how to do this step:

👉 To install the TensorFlow library, if we use the Windows Command Prompt we can run the command:

`pip install tensorflow`

👉 By default the Keras is a package already installed together with the TensorFlow installation.

👉 To install the Numpy library, if we use the Windows Command Prompt we can run the command:

`pip install numpy`

If you want to install directly by Jupyter through Conda, we can execute the command:

`conda install numpy`

If you are having problems during installation, a good alternative is to check your version of pip and Python, when we run the command below in the Command Prompt both information are provided: 

`pip --version`

👉 To install the Matplotlib library, the process is similar. By Command Prompt we will do: 

`pip install matplotlib`

👉 By default the Os library is a package already installed together with the Python installation.

👉 By default the random library is a package already installed together with the Python installation.

👉 By default the imutils library is a package already installed together with the Python installation.

👉 By default the pathlib library is a package already installed together with the Python installation.

👉 To install the Scikit-Learn library, the process is similar. By Command Prompt we will do:

`pip install scikit-learn`

👉 Finally, the OpenCV library can be installed through the following command in the Command Prompt:

`pip install opencv-python`

⚠️ This project works with a database of images available free of charge on the [Kaggle](https://www.kaggle.com/) platform and the Bounding Boxes were made on the [Roboflow website](https://roboflow.com/). In this project the volume of images was reduced due to the hardware limitations of the computer that performed the training.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.