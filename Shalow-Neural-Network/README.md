<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Shallow-Neural-Network/blob/main/images/SHALLOW%20NEURAL%20NETWORK%20Logotipo.png alt="SHALLOW NEURAL NETWORK" width="200">
<br>
<br>
SHALLOW NEURAL NETWORK
</h1>

<p align="justify">
My project is based on the development of a machine learning using the concepts of Shallow Neural Network. 

Shallow Neural Networks are simplified and didactic representations of Deep Neural Networks that are more complex.In this project, the input characteristics are taken from the processed images for both testing and training, and they are vertically stacked on the Input Layer, of index 0. Each of these characteristics will be linked by neurons responsible for the calculations for pattern recognition, which we will call the Hidden Layer, of index 1. Finally, the result of our prediction is obtained on the Output Layer, of index 2, which has a single node, which can be 0 or 1.
</p>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Shalow-Neural-Network/blob/main/images/model_example.png alt="SHALOW NEURAL NETWORK" width="300">
<br>
</h1>

<p align="justify">
The values that the different layers are transmitting are called Activation Values, which will be stored in matrices called A in this project. In this case, the Hidden Layer activations are the values stored in A1, while the Output Layer results are stored in A2.

Each layer is associated with parameters W and b, which will be updated according to Forward and Backward propagation, decreasing the value of the Cost Function, improving the accuracy and precision of the project.
</P>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Shalow-Neural-Network/blob/main/images/Calculus.png alt="SHALOW NEURAL NETWORK" width="300">
<br>
</h1>

<p align="justify">
Moreover, it is important to note that this project is a Shalow Neural Network model for study and knowledge of how machine learning works for simple situations, without using mechanisms and frameworks, which would have a more significant efficiency, but which is not the goal in this work. This can be seen, by the uses of various functions of calculations such as Sigmoide, Cost Function, Forward Propagation and Backward Propagation.

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

- 📁 [Numpy](https://numpy.org/) — Python library used for the calculations of multidimensional matrices.
- 📁 [Matplotlib](https://matplotlib.org/3.3.3/contents.html) — Library used to check the tests.
- 📁 [Os](https://docs.python.org/3/library/os.html) — Library used to browse directories from our PC.
- 📁 [OpenCV](https://opencv.org/) — Library used to modify and load our images.

## Getting started

To use this project, we need to do some library installations. Let's see below how to do this step:

👉 To install the Numpy library, if we use the Windows Command Prompt we can run the command:

`pip install numpy`

If you want to install directly by Jupyter through Conda, we can execute the command:

`conda install numpy`

If you are having problems during installation, a good alternative is to check your version of pip and Python, when we run the command below in the Command Prompt both information are provided: 

`pip --version`

👉 To install the Matplotlib library, the process is similar. By Command Prompt we will do: 

`pip install matplotlib`

👉 By default the Os library is a package already installed together with the Python installation.

👉 Finally, the OpenCV library can be installed through the following command in the Command Prompt:

`pip install opencv-python`

⚠️ This project works with a database of images available free of charge on the [Kaggle](https://www.kaggle.com/) platform . In this project the volume of images was reduced due to the hardware limitations of the computer that performed the training.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.