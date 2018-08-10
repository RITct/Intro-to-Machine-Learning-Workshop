# Intro to PyTorch and Deep Learning!

## Traditional programming and Machine learning

Machine learning is making sense of data.

![](https://scontent.fcok1-1.fna.fbcdn.net/v/t1.0-9/38647232_1065262550318293_8878660628852506624_o.jpg?_nc_cat=0&oh=23aa585957059eed98c0526dbce4075d&oe=5BFFE65D)

## Machine learning and Deep learning

In traditional machine learning, the learning process is supervised and the programmer has to be very, very specific when telling the computer what types of things it should be looking for when deciding if an image contains a dog or does not contain a dog. This is a laborious process called feature extraction and the computer's success rate depends entirely upon the programmer's ability to accurately define a feature set for "dog."

Computer programs that use deep learning go through much the same process. Each algorithm in the hierarchy applies a nonlinear transformation on its input and uses what it learns to create a statistical model as output. Iterations continue until the output has reached an acceptable level of accuracy. The number of processing layers through which data must pass is what inspired the label deep.

![](https://qph.fs.quoracdn.net/main-qimg-6c1dc5666bd31bf16120d332957b4059)

## Neural Networks

Neural networks are universal function optimisers.

### Feed forward neural networks

<p>
  <img src="https://cdn-images-1.medium.com/max/1600/1*Gh5PS4R_A5drl5ebd_gNrg@2x.png" alt="feed forward" height="350" width="600"/>
</p>

### Recurring neural networks


<p>
  <img src="https://iamtrask.github.io/img/backprop_through_time.gif" alt="recurring" height="350" width="600"/>
</p>

### Convolutional Neural Networks

<p>
  <img src="http://cs231n.github.io/assets/cnn/cnn.jpeg" alt="convnet"/>
</p>

## Intro to PyTorch

Its a scientific computation package in python which helps to use the power of GPUs and its a deep learning research platform.

### Tensors

Tensors are similar to numpy ndarrays but it can be also be used on GPUs for fast computations.

```python
import torch
```

Lets construct an empty matrix

```python
x = torch.empty(5, 3)
```
output..
```
tensor([[-5.0254e+18,  4.5609e-41, -5.0254e+18],
        [ 4.5609e-41,  1.6395e-43,  1.3873e-43],
        [ 1.4574e-43,  4.4842e-44,  1.4293e-43],
        [ 1.4714e-43,  1.5134e-43,  1.4153e-43],
        [ 4.4842e-44,  1.5554e-43,  1.5975e-43]])
```

other tensor operators are ```torch.rand()```, ```torch.zeros()```, ```torch.tensor()``` ..etc. 

### Operations

Addition,

```python
print(torch.add(x, y))
```

Converting a torch tensor to numpy and vice versa is simple in PyTorch.

```python
a = torch.ones(5)
a = a.numpy()
```
In reverse,

```python
import numpy as np
a = np.ones(5)
b = torch.from_numpy(a)
```

