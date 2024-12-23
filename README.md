# prediction-of-handwritten-digital-numbers-between-0-9
Prediction of handwritten digital numbers between 0-9

The project uses the MNIST dataset to develop and compare various neural network topologies for handwritten digit categorization. With an emphasis on attaining at least 85% accuracy, models such as DNN, ConvNet, VGG, and ResNet are assessed. TensorFlow/Keras or PyTorch were used for training and testing all models, and hyperparameters, optimization strategies, and model evaluation were thoroughly examined.

**Dataset**

Source: MNIST handwritten digit dataset
- Total Samples: 70,000 images (60,000 training, 10,000 testing)
- Image Dimensions: 28 x 28, normalized to pixel values between 0 and 1
- Labels: Digits 0−9
- Data Split:
  -Training: 80% of training data
  - Validation: 20% of training data
  - Testing: 100% of test data

**Models Implemented**

The following models were implemented and evaluated:
1. DNN (Deep Neural Network)
2. ConvNet (Convolutional Neural Network)
3. VGG (Visual Geometry Group)
4. ResNet (Residual Neural Network)

**Key Techniques and Parameters**

1. Loss Function: Cross-Entropy Loss
2. Optimizer: Adam Optimizer
3. Learning Rates: Tested 0.1, 0.01, 0.001.
4. Regularization Techniques:
   a. Early Stopping: Monitors validation loss to prevent overfitting.
   b. Dropout Layers: Randomly deactivates neurons during training.
   c. L2 Regularization: Penalizes large weights to reduce model complexity.

**Top Model**

With an accuracy of 98.89%, the ConvNet model outperformed the others in the majority of measures. Strong performance was guaranteed while keeping training periods comparatively short thanks to its sturdy design and effective convolutional layers.



