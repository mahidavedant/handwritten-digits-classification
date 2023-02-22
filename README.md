# MNIST - Handwritten Digits Classification Using CNN

## Libraries
Main libraries that are used for CNN model developement was consist of:
    - NumPy
    - Pandas
    - Matplotlib
    - Keras

## Data
MNIST dataset is a large dataset which has `60,000` trainning images and `10,000` testing images. All the images has `28x28` dimention and are grayscale. Below is a sample of this MNIST dataset.
![](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

- Data was scaled and reshaped for optimization.

## CNN architecture
In **Feature learning** phase, this CNN model consists of 2 convolution layers with `3x3` filters, `ReLU` activation and are followed by Max pooling layers. 
In **Classification** phase, above layers get flattened and processed for fully connected layer followed by output layer with `softmax` activation. 

## Model performance
This CNN model, performs pretty well with the training and testing accuracy of `99.73%` and `99.21%` respectively. 