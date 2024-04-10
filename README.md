# Skin Lesion Classification
## Project for BME450 at Purdue, Spring 2024
Xaver Gross, Daniel Florness


[![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15_w0VSNHTs70Wzu87iyhlGC6mOaz3q-x#scrollTo=FVuJTP98-OUX) [Presentation Video]()

Classifications of skin lesions using dermatoscopic images from the DermaMNIST dataset, a dataset found in a large-scale MNIST-like collection of standardized biomedical images, provided by some universities. It's underlying focus is on melanoma detection (a kind of skin cancer).


### Architectures for Multiclass Image Classification
We try Convolutional Neural Networks and Transformers separately for the multiclass classification.

## Time Plan
![Plan](plan.png)

## Installation and Requirements

To run the code, set up the required environments and install `medmnist` as outlined in the corresponding [repository](https://github.com/MedMNIST/MedMNIST), as well as `Pandas` and `Pytorch`. e.g. with the following command
```
pip install medmnist numpy pandas torch
```
The code was run and tested using the following versions:
- Python 3 (X.X)
- Pytorch==X.X
- pandas==X.X



