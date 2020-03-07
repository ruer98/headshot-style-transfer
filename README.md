# headshot-style-transfer
I implement a neural style transfer algorithm on my professional headshot and use NumPy docstrings to document each function that I use for the process.

### Neural Style Transfer
Neural style transfer is a type of algorithm that merges two images: one is this "content" image (C) and the other is a "style" image (S). These two are blended to create a "generated" image (G) which presents the content of image C with the style of image S. While most neural net algorithms optimize a cost function to get parameter values, this algorithm optimizes a cost function to get pixel values.

The neural style transfer algorithm that I implement in this project was created by Gatys et al. (2015) (https://arxiv.org/pdf/1508.06576.pdf)

### NumPy Docstrings
Numpy style has a lot of details in the documentation compared to other documentation styles. It is more verbose than other documentation, but it is an excellent choice if you want to do detailed documentation, i.e., extensive documentation of all the functions and parameters. I figured that I could get some practice in using this format even though this is not typical for deep learning. Here is a guide on NumPy docstrings: https://numpydoc.readthedocs.io/en/latest/format.html
