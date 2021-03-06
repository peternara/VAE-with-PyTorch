# Variational Auto-Encoder(VAE) for Fashion MNIST
PyTorch implementation of VAE for Fashion MNIST

## Description
This code is written for practice. It's almost as same as PyTorch's official example(check the reference below).

## Results
The following results are made with the default setting. (command: python main.py)

<table align='center'>
<tr align='center'>
<td> Reconstruction </td>
<td> Sampling </td>
<td> Manifold(num of z = 2) </td>
</tr>
<tr>
<td><img src = 'results/reconstruction_20.png' width = '300px'></td>
<td><img src = 'results/sample_20.png' width = '300px'></td>
<td><img src = 'results/plot_along_z1_and_z2_axis_20.png' width = '300px'></td>
</tr>
</table>


## References
The implementation is based on:  
[1] https://github.com/pytorch/examples/blob/master/vae/main.py  
[2] https://github.com/hwalsuklee/tensorflow-mnist-VAE/  

