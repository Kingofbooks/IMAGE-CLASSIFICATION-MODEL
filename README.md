# IMAGE-CLASSIFICATION-MODEL

COMPANY: CODTECH IT SOLUTIONS

NAME: ARYAN SHARMA

INTERN ID: CT08PBS

DOMAIN: MACHINE LEARNING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION: ML Internship Project -IMAGE CLASSIFICATION MODEL

Internship Institution: CODTECH

Task:BUILD A CONVOLUTIONAL NEURAL NETWORK (CNN) FOR IMAGE CLASSIFICATION USING TENSORFLOW OR PYTORCH.

In this project, I built an Image Classification Model using a Convolutional Neural Network (CNN) with TensorFlow or PyTorch. The goal was to classify images based on patterns learned from a dataset. Below is a detailed breakdown of the components and techniques you used:
1. Technologies & Libraries Used
Deep Learning Framework: TensorFlow/Keras (or PyTorch)
Activation Functions: ReLU and Sigmoid
Layers Used: Conv2D, MaxPooling2D, Dense (Fully Connected)
Tools: Image Downloader Extension (for dataset collection)
2. Model Architecture
Your CNN model follows a hierarchical structure, extracting features from images through convolutional layers, downsampling using pooling layers, and finally making predictions using dense layers.
a) Input Layer
The model accepts images of shape (256, 256, 3), meaning 256x256 pixels with 3 color channels (RGB).
b) Convolutional and Pooling Layers
These layers extract features from images.
Conv2D(16, (3,3), 1, activation='relu')
Applies 16 filters of size 3×3 to detect patterns like edges, shapes, and textures.
Uses ReLU activation to introduce non-linearity and avoid the vanishing gradient problem.
Stride of 1 ensures every pixel is considered in the convolution operation.
MaxPooling2D()
Reduces the spatial dimensions while keeping essential features, improving computational efficiency.
c) Additional Convolutional & Pooling Layers
These layers progressively learn more complex patterns from images.
32 filters in the second Conv2D layer increase the model’s ability to recognize finer details.
The final Conv2D layer uses 16 filters again to refine features before passing them to the dense layers.
d) Flatten Layer
Converts the 2D feature maps into a 1D vector to be fed into the fully connected layers.
e) Fully Connected (Dense) Layers
Dense(256, activation='relu')
A fully connected layer with 256 neurons.
Uses ReLU activation to introduce non-linearity.
Dense(1, activation='sigmoid'
A single neuron output layer with Sigmoid activation.
Outputs values between 0 and 1, making it ideal for binary classification (e.g., cat vs. dog, spam vs. not spam).
3. Key Features of My Model
Feature Extraction: Uses convolutional layers to detect patterns from images.
Downsampling: Uses MaxPooling to reduce computational cost.
Non-linearity: Uses ReLU for faster and better convergence.
Classification: Uses Sigmoid activation for binary classification.

OUTPUT:
![Image](https://github.com/user-attachments/assets/9494bcc1-7693-4048-8904-16e0fc08692c)
![Image](https://github.com/user-attachments/assets/03ac5823-9140-4611-8312-42b31f3c5f82)
