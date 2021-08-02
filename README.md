# Image-Steganography-Using-Deep-Learning

# Deep Learning
Deep Learning in simple words is an Artificial Intelligence that initiates the working of human brain in processing data and creating patterns for use in decision making.

# Refer:-

For Deep Learning
https://www.ibm.com/cloud/learn/deep-learning

For Neural Networks
https://www.ibm.com/cloud/learn/neural-networks

The diagram belowe shows the pictorial representation of neural networks.

![image](https://user-images.githubusercontent.com/64018679/127902156-59a1c4b5-2ba5-4bfe-aac7-8e0da3379dd0.png)

Types of Activation Function

![image](https://user-images.githubusercontent.com/64018679/127903310-8ea306ff-8994-4721-b00e-42c46229ee7b.png)

With the use of Simple Neurons,algorithm can learn complex structure present in the dataset.

# CONVOLUTIOAL NEURAL NETWORK

In this project, I am going to use Covolutional Neural Network. Reason being CNN works well with Image classification.
Whenever we use DL Neural Netowrk, it performs overfitting. n order to avoid overfitting, we have to coe up with a way that can identify essential features (which are more important then anything else present in data).

How CNN learns ?

There is a technique called template matching. Template matching is a technique in Digital Image processing for find small parts of the image which match the given template.

To understand the important features of image data, we do some operations / processing on the input image. This is called convolutioal operation.

![image](https://user-images.githubusercontent.com/64018679/127906018-9118d29d-d71d-46f8-8395-1b022554feef.png)

The central matrix is called kernel. The kernel moved left to right and top to bottom. The dot product of kernal values with input image value occurs and transformed values are projected in a new matrix. (Simply, we are applying some filters so that all essential features can  be  estimated properly). 

PADDING LAYER
Padding layer adds some extra dimesionality to the input image so that at the time of processing, no dimesnionality will be missed(when advanced filtering tehniques are used).

POOLING LAYER
We have two types of pooling layer 1) Max pooling layer  2) Average pooling layer

In max pooling layer, the kernel is placed at the specifi portion and takes maximum value of the portion as transformed value.

*The next step after processing of image is Flattening Operattion

Flattening is the reduction of 2D array into 1D array.

Input image -> Processing + Max Pooling -> (to an number of hidden layers) + Processing + Max_pooling -> Fully Connected Neural Network -> Output

![image](https://user-images.githubusercontent.com/64018679/127907611-1e701b20-eddb-4ebf-a6ca-5d5a07e461ae.png)


# Steganography


