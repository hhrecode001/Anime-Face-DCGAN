# Anime-Face-DCGAN
DCGAN model for anime face generator

## Lore
https://learnopencv.com/deep-convolutional-gan-in-pytorch-and-tensorflow/
https://github.com/spmallick/learnopencv/tree/master/Deep-Convolutional-GAN
https://arxiv.org/pdf/1511.06434.pdf

## Dataset
https://github.com/bchao1/Anime-Face-Dataset

## Train
1. Download the Dataset, put the crop folder in *anime-data/*
1. Put [image].jpg in *anime-data/* (or change the dir path in *tf.keras.preprocessing.image_dataset_from_directory*)
1. Run anime-face-train file (can change the number of epoch in train(nor_df,epochs))

## Load weight
1. Put gen_??.h5 in *dcgan\tf\training_weights*
1. Run anime-face-gen file
