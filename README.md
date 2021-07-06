# HebbianCNNPyTorch

This code demonstrate a very easy way to implement Hebbian learning in multi-layer convolutional networks: just define a special loss whose gradient is equal to the Hebbian update!

Ready-made expressions are available for plain Hebb's rule (dw ~= xy), Grossberg's Instar rule (dw ~= y(x-w)) and Oja's rule, (dw ~= y(x-wy)). All code is available as Jupyter notebooks with PyTorch, ready to use on Google Colab.

* The [simple version](https://github.com/ThomasMiconi/HebbianCNNPyTorch/blob/main/HebbGrad_Simple_Github.ipynb) contains a simple but fully functional implementation. It is **highly recommended** to look at this version first.

* The [full version](https://github.com/ThomasMiconi/HebbianCNNPyTorch/blob/main/HebbGrad_Github.ipynb) contains the code that generates the actual results described in the paper. It is more complex, mostly because it has a lot more options.

* The [checking code](https://github.com/ThomasMiconi/HebbianCNNPyTorch/blob/main/HebbGrad_CheckHebb.ipynb) just verifies that the PyTorch-generated gradients are equal to (hand-computed) Hebbian updates, for the various rules.

For more details, see our preprint at https://arxiv.org/abs/2107.01729.
