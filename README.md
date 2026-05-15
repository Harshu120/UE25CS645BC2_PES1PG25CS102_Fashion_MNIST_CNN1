# UE25CS645BC2_PES1PG25CS102_Fashion_MNIST_CNN1
CNN
Fashion MNIST CNN Implementation from Scratch
**1.Introduction**
This project implements a Convolutional Neural Network (CNN) from scratch using Python and NumPy. The aim of the assignment is to understand the internal working of CNNs by manually implementing different CNN layers such as Convolution, Pooling, Flattening, and Fully Connected layers along with forward propagation and backward propagation.
**2. About Convolutional Neural Networks**
Convolutional Neural Networks (CNNs) are deep learning models mainly used in computer vision tasks such as image classification, object detection, and pattern recognition. CNNs use convolution operations to extract important image features such as edges, shapes, and textures.
•	Convolution Layer
•	Pooling Layer
•	Fully Connected Layer
**3. Dataset Description**
The Fashion MNIST dataset contains 70,000 grayscale images of clothing and fashion accessories. Each image is of size 28 × 28 pixels and belongs to one of 10 classes.
•	T-shirt/top
•	Trouser
•	Pullover
•	Dress
•	Coat
•	Sandal
•	Shirt
•	Sneaker
•	Bag
•	Ankle boot

**4. Code Description**
Importing Libraries
The project imports NumPy for numerical computations and TensorFlow/Keras for loading the Fashion MNIST dataset.
Loading the Dataset
The Fashion MNIST dataset is loaded into training and testing sets using keras.datasets.fashion_mnist.
Data Preprocessing
Pixel values are normalized by dividing by 255.0 to scale image values between 0 and 1 for efficient training.
Convolution Layer
The ConvLayer class is implemented manually to perform convolution operations using filters/kernels. The forward pass extracts important features from the input image.
Max Pooling Layer
The MaxPool class reduces the dimensions of feature maps while retaining important features using max pooling operation.
Flatten Function
The flatten() function converts the 2D feature maps into a 1D vector before passing it to the dense layer.
Fully Connected Layer
The Dense class implements a fully connected neural network layer with weights and biases for classification.
Softmax Function
The softmax() function converts the output scores into probability values for all classes.
Cross Entropy Loss
The cross_entropy() function calculates the loss between predicted probabilities and actual labels.
Forward Pass
The forward() function performs convolution, flattening, dense layer computation, softmax activation, and loss calculation.
Training Function
The train() function performs forward propagation, calculates gradients, applies backpropagation, and updates weights using gradient descent.
Training Loop
The model is trained for multiple epochs on the Fashion MNIST training dataset.
Model Evaluation
The trained CNN model is tested on unseen test images and accuracy is calculated.

**5. CNN Workflow**
1.	Input Image
2.	Convolution Layer
3.	Feature Extraction
4.	Max Pooling
5.	Flattening
6.	Fully Connected Layer
7.	Softmax Classification
8.	Prediction Output
   
**6. Training and Evaluation**
The CNN model is trained using forward propagation and backpropagation. Weights and filters are updated using gradient descent to minimize loss and improve accuracy.

**7. Learning Outcomes**
•	Understanding convolution operations
•	Implementing CNN from scratch
•	Learning forward and backward propagation
•	Understanding pooling and flattening
•	Training neural networks manually
•	Working with image datasets
**8. Conclusion**
This project successfully demonstrates the implementation of a Convolutional Neural Network (CNN) from scratch using Python and NumPy on the Fashion MNIST dataset. Through this project, the CNN model was able to learn important image features such as edges, textures, and shapes using convolution and pooling operations. The network was trained using forward propagation and backpropagation, and the model achieved successful classification of fashion images into different categories.

The project provided practical understanding of how CNN architectures work internally without relying on high-level deep learning libraries. It also improved knowledge of convolution operations, feature extraction, gradient descent, and neural network training mechanisms.
The CNN model achieved an accuracy of approximately 81.2% on the Fashion MNIST test dataset after training.
**9. Outcomes Achieved**
Through the completion of this project, the following outcomes were achieved:
Successfully implemented a CNN from scratch using Python and NumPy
Understood the working of convolution, pooling, flattening, and fully connected layers
Learned how forward propagation and backpropagation work in CNNs
Gained practical experience in image classification using the Fashion MNIST dataset
Understood feature extraction and dimensionality reduction techniques
Learned weight updating using gradient descent optimization
Improved understanding of deep learning fundamentals and CNN architecture
Successfully trained and evaluated a CNN model on real image data
