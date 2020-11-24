# Object_Recognition.
Object recognition is a computer vision technique for identifying objects in images or videos. Object recognition is a key output of deep learning and machine learning algorithms. When humans look at a photograph or watch a video, we can readily spot people, objects, scenes, and visual details.

## Deep Neural Network - DNN.
Solve Complex Task
When it gets new information in the system, it learns how to act accordingly to a new situation.  
Learning becomes deeper when tasks you solve get harder. 
Helps to load pre-trained Model from DL frameworks such as
![image](https://user-images.githubusercontent.com/67863890/100054411-fb622100-2e47-11eb-95f8-eb97a91216cb.png)

-Tensorflow
-Caffe
-Darknet
-Torch

#### MobileNet SSD (Single shot Multibox Detector).

The MobileNet model is based on depthwise separable convolutions which are a form of factorized convolutions. These factorize a standard convolution into a depthwise convolution and a 1 × 1 convolution called a pointwise convolution.

For MobileNets, the depthwise convolution applies a single filter to each input channel. The pointwise convolution then applies a 1 × 1 convolution to combine the outputs of the depthwise convolution.

A standard convolution both filters and combines inputs into a new set of outputs in one step. The depthwise separable convolution splits this into two layers – a separate layer for filtering and a separate layer for combining. This factorization has the effect of drastically reducing computation and model size.

The SSD architecture is a single convolution network that learns to predict bounding box locations and classify these locations in one pass. Hence, SSD can be trained end-to-end. 



# ReLu.
The Rectified Linear Unit is the most commonly used activation function in deep learning models. 

The function returns 0 if it receives any negative input, but for any positive value  x  it returns that value back. So it can be written as  f(x)=max(0,x) .

the ReLu function is able to accelerate the training speed of deep neural networks compared to traditional activation functions since the derivative of ReLu is 1 for a positive input. 

Due to a constant, deep neural networks do not need to take additional time for computing error terms during training phase.

