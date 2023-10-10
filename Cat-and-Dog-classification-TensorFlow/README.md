<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Cat-and-Dog-classification-TensorFlow/blob/main/Images/CAT%20AND%20DOG%20CLASSIFICATION%20Logotipo.png alt="CAT AND DOGCLASSIFICATION" width="200">
<br>
<br>
CAT AND DOG CLASSIFICATION WITH TENSORFLOW
</h1>

<p align="justify">
My project is based on the development of a machine learning using the concepts of Convolutional Neural Network with TensorFlow Framework.

In Deep Learning, certain layers are responsible for certain recognition patterns, such as edges, textures, and so on. 

The concept of Convolutional Netowork is based on this concept in the analysis of our supposed image, and with the values of pixels present in this image, we will use filters, also called Kernel, which will perform Convolutional operations to obtain other values in a smaller matrix, and thus recognize the patterns needed for each layer. 
</p>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Cat-and-Dog-classification-TensorFlow/blob/main/Images/CNN%20Model.png alt="CNN model" width="550" height = "250">
<br>
</h1>

<p align="justify">
In CONV Nets projects it is very common to use POOL layers, called Pooling Layers, used as a way to accelerate our calculations and make some features more robust. In this project, we use MaxPooling Layers in each layer with convolutional operations except in Dense layers at the end of our CNN.
</P>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Cat-and-Dog-classification-TensorFlow/blob/main/Images/MaxPool%20example.png alt="DEEP NEURAL NETWORK" width="4000" height = "270">
<br>
</h1>

<p align="justify">
In this project the RELU activation function was used in all the other layers, and only in the last layer the Sigmoid is used, because we are making a binary classification, and the Sigmoid function is efficient for these cases. Unlike my other projects, here it was not necessary to build the activation functions or the Forward or Backward propagation process, the framework is responsible for this type of process, and it is up to the developer to build the model and process the data.

Still in the last layers, we observe a Flatten operation to modify our matrix, with the purpose of creating the Fully Connected Layers determined by the Dense operation, which will help in the transfer of parameters for pattern recognition. 
</p>

<p align="justify">
Moreover, it is important to note that this project is a CNN model for study and knowledge of how machine learning works for simple situations. Even using frameworks the result will depend on how you design your Convolutional Neural Network, always watching Overfiting or Underfiting and studying how to improve your results.

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

👉 Finally, the OpenCV library can be installed through the following command in the Command Prompt:

`pip install opencv-python`

⚠️ This project works with a database of images available free of charge on the [Kaggle](https://www.kaggle.com/) platform . In this project the volume of images was reduced due to the hardware limitations of the computer that performed the training.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.