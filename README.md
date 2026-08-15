# Neural Network Implementation from Scratch

## Student Information

- **Name:** Chirag Nagawade
- **PRN:** 202502110009
- **Batch:** A3
- **Class:** T.Y. B.Tech
- **Department:** CSE AIML
- **College:** MIT Academy of Engineering, Alandi, Pune
- **Course:** Generative AI Lab
- **Practice Lab:** Neural Network 1
- **Date of Submission:** 15/08/2026

## Objective

The objective of this assignment is to implement a simple feedforward neural network from scratch using Python and NumPy without using in-built deep learning libraries.

The implementation includes:

- Forward propagation
- ReLU activation
- Softmax activation
- Categorical Cross-Entropy loss
- Backpropagation
- Gradient Descent
- Model training and evaluation

## Dataset

The Iris dataset is used for this classification task.

The dataset contains:

- 150 samples
- 4 input features
- 3 target classes

### Input Features

1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

### Target Classes

1. Setosa
2. Versicolor
3. Virginica

The dataset is loaded using:

```python
from sklearn.datasets import load_iris

iris = load_iris()

Neural Network Architecture
Input Layer
4 Neurons
     ↓
Hidden Layer
8 Neurons + ReLU
     ↓
Output Layer
3 Neurons + Softmax

Architecture

4 → 8 → 3

Methodology

The neural network follows these steps:

    Load the Iris dataset.
    Split the dataset into training and testing sets.
    Standardize the input features.
    Convert target labels into one-hot encoded format.
    Initialize weights and biases.
    Perform forward propagation.
    Calculate categorical cross-entropy loss.
    Perform backpropagation.
    Update weights using gradient descent.
    Train the model for multiple epochs.
    Evaluate the model using test data.
Technologies Used
    Python
    NumPy
    Pandas
    Matplotlib
    Scikit-learn
    Google Colab
    GitHub
Evaluation

    The model is evaluated using:
    
    Training Loss
    Test Accuracy
    Classification Report
    Confusion Matrix

Conclusion

A feedforward neural network was successfully implemented from scratch using Python and NumPy. The model performs multi-class classification on the Iris dataset using forward propagation, backpropagation, and gradient descent.
