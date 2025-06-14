# Recognition-of-Handwritten-Digits


## Handwritten Digit Recognition from Scratch

A deep neural network implemented from scratch (without ML frameworks) for recognizing handwritten digits, trained on the MNIST dataset.

## Key Features

- **From-Scratch Implementation**: Built without using ML frameworks like TensorFlow/PyTorch
- **High Accuracy**: Achieves ~90% prediction accuracy on MNIST test data
- **Optimized Architecture**: Enhanced with modern deep learning techniques:
  - Batch normalization
  - Skip connections
  - Strategic hyperparameter tuning
- **Bias Mitigation**: Carefully designed to reduce model bias

## Technical Details

### Model Architecture
- Fully connected deep neural network
- Custom implementation of:
  - Forward/backward propagation
  - Activation functions (ReLU/Softmax)
  - Loss computation (Cross-entropy)
  
### Optimization Techniques
- Hyperparameter tuning (learning rate, batch size, epochs)
- Batch normalization between layers
- Skip connections to improve gradient flow
- Weight initialization strategies

## Dataset
Trained and evaluated on the standard [MNIST dataset]:
- 60,000 training images
- 10,000 test images
- 28×28 grayscale handwritten digits (0-9)

## Requirements
- Python 3.x
- NumPy
- Matplotlib (for visualization)

