# Diverse ML notebooks

This repository contains several notebooks implementing/testing machine learning algorithms and techniques. 

## List of files

 - `GAN_for_anime_faces.ipynb` : In this notebook, we implement a DCGAN to generate faces in a manga-like style. For this project, we used [this dataset from WANG Yaohui](https://gitlab.inria.fr/yaowang/gan_class_images.git). This notebook uses PyTorch as its ML framework.
 - `Autoencoder_Image_Compression.ipynb` : In this notebook, we implement an autoencoder to perform image compression. We study the [PSNR](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) with different compression rates (i.e. different latent space dimensions). This notebook uses tensorflow as
 - ⭐ `classification-on-plantnet.ipynb` : This notebook comes from a Kaggle competition (using [this subset](https://gitlab.inria.fr/cgarcin/plantnet_dataset) of the [Plantnet dataset](https://plantnet.org/en/)). This notebook comprehensively goes through the whole process of building a classifier on image data, from custom datasets, samplers, models, etc, using PyTorch. Model-wise, this notebook uses CNNs, homemade residual networks, and a fine-tuned ResNet152. This notebook is extensively commented, and documents all of the tested configurations and their scores during the competition.


Note : Some of these notebooks are the products of uni labs or projects, and may thus have a few obscure headers (for example, when they reference exercise questions or subject codes).
