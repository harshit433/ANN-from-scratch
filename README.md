# ANN_from_scratch

This repository implements a custom artificial neural network from scratch using PyTorch. The network architecture is built without relying on pre-defined layers like nn.Linear or activation functions like nn.Tanh. It is trained on a regression dataset and achieves an accuracy of 87%, outperforming a Keras model trained on the same data (84% accuracy).

### Key Features:

#### Custom Network Construction: 
Builds the neural network architecture from scratch using PyTorch tensors and operations.

#### PyTorch Integration: Leverages 
PyTorch for automatic differentiation and efficient loss calculation.

#### Regression Focused: 
Designed for regression tasks, demonstrating strong performance on a chosen regression dataset.

### Benefits:

#### Deeper Understanding: 
Provides a hands-on exploration of neural network fundamentals by building the components from scratch.

#### Customization Potential: 
Offers the flexibility to tailor the network architecture and activation functions to specific problem requirements.

#### Benchmarking: 
Achieves competitive results compared to models built with higher-level abstractions.

### Getting Started:

#### Clone the Repository:

```
Bash
git clone https://github.com/<your-username>/from-scratch-nn-pytorch.git
```

#### Install Dependencies:

```
Bash
pip install torch
# Additional dependencies for your specific dataset (if required)
```

#### Run the Script:

```
Bash
python train.py
```

This script loads the dataset, trains the model, and evaluates its performance.

### Further Exploration:

Explore different network architectures and activation functions.

Implement additional features like early stopping and regularization.

Test the model on various regression datasets.

#### Feel free to contribute! 
We welcome pull requests and suggestions for improvement.
