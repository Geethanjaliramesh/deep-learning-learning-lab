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

Sample_P_Dataset_Dataloader.ipynb ## Key Takeaways

In this experiment, I learned how PyTorch handles datasets that are too large to process all at once.

The main training workflow was:

**Dataset → DataLoader → Batches → Forward Pass → Loss → Backpropagation → Parameter Update**

Key observations:

- A Dataset represents samples and their labels.
- A DataLoader controls how samples are provided to the model.
- Batch size determines how many samples are processed together.
- Shuffling changes the training sample order between epochs.
- Model parameters are updated after each training batch.
- An epoch represents one complete pass through the training dataset.
- Average epoch loss gives a better view of training progress than the loss of a single batch.
- Accuracy can be used to evaluate classification predictions.
- Tensor shape and `dtype` are important things to inspect when debugging PyTorch errors.
