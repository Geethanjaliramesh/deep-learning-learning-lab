# deep-learning-learning-lab
Hands-on experiments exploring deep learning architectures and concepts using PyTorch.
refrEshhing basics of neural network by doing some handson from basics to big programs 
01_pytorch_fundamentals.ipyb includes intro to tensors and how to work with tensors
Sample_neuralnetwork.ipynb :In this experiment, I learned the basic workflow used to train a neural network:

**Input → Forward Pass → Loss → Backpropagation → Optimizer → Parameter Update**
- Neural networks learn by adjusting weights and biases.
- Activation functions such as ReLU introduce non-linearity.
- A loss function measures prediction error.
- Backpropagation calculates gradients.
- An optimizer uses those gradients to update model parameters.
- Repeating this process over multiple epochs allows the model to learn.
- During inference, gradients are not required, so `torch.no_grad()` can be used.

This small experiment provides the foundation for moving on to deeper networks, CNNs, RNNs and other deep-learning architectures.
