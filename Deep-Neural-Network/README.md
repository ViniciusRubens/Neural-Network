<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/DEEP%20NEURAL%20NETWORK%20Logotipo.png alt="DEEP NEURAL NETWORK" width="200">
<br>
<br>
DEEP NEURAL NETWORK
</h1>

<p align="justify">
My project is based on the development of a machine learning using the concepts of Deep Neural Network. 

Logistics Regression is a case of a Shallow Neural Network, while a Deep Neural Network are networks that have a much larger number of hidden layers. 
Each Hidden Layer is endowed with a number of neurons determined by the designer.The Input Layer remains with the number of neurons corresponding to the characteristic vector that was obtained in image processing. This project is a binary classification of 0 for cats and 1 for dogs, so the Output Layer remains with a single neuron.
</p>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/Deep%20neural%20network%20model.png alt="DEEP NEURAL NETWORK" width="550" height = "350">
<br>
</h1>

<p align="justify">
The values that are transmitted through the different layers are called activation values and are stored in the matrix called AL in this project. As it is a model with L layers, both Forward and Backward propagation are performed by each layer with increments and decrements in repeating for loops. 

Each layer is associated with parameters W and b, which will be updated according to Forward and Backward propagation, decreasing the value of the Cost Function, improving the accuracy and precision of the project.
</P>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/sequence.png alt="DEEP NEURAL NETWORK" width="210">
                    
  <img src=https://github.com/ViniciusRubens/Deep-Neural-Network/blob/main/Images/calculus.png alt="DEEP NEURAL NETWORK" width="300">
<br>
</h1>

<p align="justify">
Moreover, it is important to note that this project is a Deep Neural Network model for study and knowledge of how machine learning works for simple situations, without using mechanisms and frameworks, which would have a more significant efficiency, but which is not the goal in this work. This can be seen, by the uses of various functions of calculations such as RELU and Sigmoid (Activation Function for Output Layer), Cost Function, Forward Propagation and Backward Propagation.

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