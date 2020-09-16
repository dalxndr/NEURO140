# NEURO140

### Elastic Weight Consolidation (DeepMind Paper Implementation with Tensorflow)

This is an implementation of "Overcoming catastrophic forgetting in neural networks" (https://arxiv.org/abs/1612.00796) for supervised learning in TensorFlow.

### model.py: 
  Defines a simple fully-connected network and methods to compute the diagonal of the Fisher information matrix.

### experiment.ipynb:
  Trains and tests a single network on three MNIST classification tasks sequentially (i.e., once the network begins training on a given task, it is never exposed     to previous task training data again).
