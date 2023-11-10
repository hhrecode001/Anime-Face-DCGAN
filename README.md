# Anime-Face-DCGAN
**DCGAN model for anime face generator**

The Deep Convolutional Generative Adversarial Network (DC-GAN) is a widely known deep learning architecture for image generation. This project utilises DCGAN for anime-style face-generating. The result is in the /result directory.

## Lore
1. https://learnopencv.com/deep-convolutional-gan-in-pytorch-and-tensorflow/
1. https://github.com/spmallick/learnopencv/tree/master/Deep-Convolutional-GAN
1. https://arxiv.org/pdf/1511.06434.pdf

## Dataset
https://github.com/bchao1/Anime-Face-Dataset

## Train
1. Download the Dataset, put the crop folder in *anime-data/*
1. Put [image].jpg in *anime-data/* (or change the dir path in *tf.keras.preprocessing.image_dataset_from_directory*)
1. Run anime-face-train file (can change the number of epoch in train(nor_df,epochs))

## Load weight
1. Put gen_??.h5 in *dcgan\tf\training_weights*
1. Run anime-face-gen file
