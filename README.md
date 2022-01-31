# Problem Statement 
This dataset is about the medical cost of an individual. This data science problem's domain is medical field and using those given datas in the datase, we try to find the medical cost. 


## Dataset

The dataset used is the [mushroom_dataset] (https://www.kaggle.com/mirichoi0218/insurance) from Kaggle.

Since the medical cost is a continuous target variable, the task is a regression task.

**Target Variable: MedicalCost**
<br>
<br>
Medical Cost refers to the medical bill based on their health conditions
<br>
**Mean Medical Cost:** 
<br>
**Max Medical Cost:** 
<br>
**Min Medical Cost:** 


## Model(s) Used

This needs to be a description of the model used and a brief overview of how it works in theory (e.g taken of a CNN Model): 

The network architecture used was a basic CNN model, with Max Pooling and ReLU Activation functions. Input images are resized to an optimal size and then fed into the **Convolutional layer**. These images are converted to their pixel values, which can be imagined as a three-dimensional matrix for the purpose of visualization. The **Convolutional layer** has a kernel. This kernel is generally a small matrix of specified kernel size mxnx3 (3 for RGB images). 
<br>

**Rectified Linear Unit (ReLU)** is the activation layer used in CNNs.The activation function is applied to increase non-linearity in the CNN. Images are made of different objects that are not linear to each other.


**Max Pooling:** A limitation of the feature map output of Convolutional Layers is that they record the precise position of features in the input. This means that small movements in the position of the feature in the input image will result in a different feature map. This can happen with re-cropping, rotation, shifting, and other minor changes to the input image. A common approach to addressing this problem from signal processing is called down sampling. This is where a lower resolution version of an input signal is created that still contains the large or important structural elements, without the fine detail that may not be as useful to the task.

## Future Work
Good ideas or strategies that you were not able to implement which you think can help  improve performance.
