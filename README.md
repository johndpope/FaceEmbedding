# EasttoWest
![Python 3.7.6](https://img.shields.io/badge/python-3.7.6-green.svg?style=plastic)
![TensorFlow 1.15.0](https://img.shields.io/badge/tensorflow-1.15.0-green.svg?style=plastic)
![Pytorch 1.1.0](https://img.shields.io/badge/pytorch-1.1.0-green.svg?style=plastic)
![Keras 2.2.4](https://img.shields.io/badge/keras-2.2.4-green.svg?style=plastic)

Embed Eastern Faces to Western Faces using StyleGAN.

![image](./teaser.jpg)
**Figure:** *Embedding result for a Korean celebrity.*

Original Codes from : 

https://github.com/Puzer/stylegan-encoder/

https://github.com/jacobhallberg/pytorch_stylegan_encoder

# Usage

I used the pre-trained models from https://github.com/jacobhallberg/pytorch_stylegan_encoder/releases/tag/v1.0 . As mentioned, place the StyleGAN model in ./InterFaceGAN/models/pretrain/ . Place the Image To Latent model at the root of the repo.

1) Align raw images
> python align_images.py PATH_TO_RAW_IMAGES/ inputs/

2) Convert images using Pre-trained StyleGAN.
> python test.py

