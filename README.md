# Deep Neural Network for MNIST Classification
- It is a deep learning algorithm that detects which digit is written in provided MNIST dataset and classify all into 10 classes i.e. 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9).
- TensorFLow includes a data provider for MNIST that we used.

## Action Plan :
1. Prepare our data and process it. Create training, validation and testing dataset.
2. Outline the model and choose the activation function.
3. Set the appropiate optimizer and loss function.
4. Make the model learn.
5. Test the accuracy of the model.

- Convert each image in a vector of length (784*1), with input values of range 0 to 255. (0 for purely black and 255 for purely white)
- We built a neural network with 2 hidden layers.
- We built the model using "ADAM" optimeizer and "Softmax" as output activation function.
- The final test accuracy should be roughly around 97%.
- We used One hot encoding method for categorical data preprocessing.
