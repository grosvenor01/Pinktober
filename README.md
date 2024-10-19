# Pinktober

### Description : 
trying to build a deep learning model to predict if the picture is begnin breast cancer or malignine, we us the approach of CNN (convlutional neural network) which is a deep learning architecture based pcture preprocessing and predicting depend on pixels value, our accuracy by the end was 0.66 with 0.4 value of loss 

### model architecture
- Input Layer:
Accepts the input images with the specified shape.
- Convolutional Layer (Conv2D):
64 filters of size 3x3, with 'same' padding.
- Activation function specified by activ.
- Max Pooling Layer (MaxPool2D):
Reduces the spatial dimensions by taking the maximum value in a 2x2 pool.
- Dropout Layer:
Drops 25% of the neurons to prevent overfitting.
- Convolutional Layer (Conv2D):
Another layer with 64 filters of size 3x3 and 'same' padding.
Same activation as before.
- Max Pooling Layer (MaxPool2D):
Again reduces the spatial dimensions.
- Dropout Layer:
Drops another 25% of the neurons.
- Flatten Layer:
Flattens the 2D matrix into a 1D vector.
- Dense Layer:
Fully connected layer with 128 neurons and 'relu' activation.
- Output Layer (Dense):
Final layer with num_classes neurons and 'softmax' activation for multi-class classification.
