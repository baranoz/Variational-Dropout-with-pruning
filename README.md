# Variational Dropout with pruning the network
The code I will give will prune some weights to improve the performance. The first task is creating the neural network.
Than code applies three different drop out technique standard, Gausian and variational.
see: https://arxiv.org/abs/1506.02557
see: https://arxiv.org/pdf/1701.05369.pdf.

Also code written under a scarce data regime so it is possible to use the subset of the data or full data.
I also used some implementation from https://github.com/j-min/Dropouts/blob/master/Gaussian_Variational_Dropout.ipynb.
