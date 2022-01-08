# Anime-Face-DCGAN
DCGAN model for anime face generator

## Lore
https://learnopencv.com/deep-convolutional-gan-in-pytorch-and-tensorflow/
https://github.com/spmallick/learnopencv/tree/master/Deep-Convolutional-GAN
https://arxiv.org/pdf/1511.06434.pdf

## Train
1. Put [image].jpg in *anime-data/* (or change the dir path in *tf.keras.preprocessing.image_dataset_from_directory*)
2. Run anime-face-train file (can change the number of epoch in train(nor_df,epochs))

## Load weight
1. Put gen_??.h5 in *dcgan\tf\training_weights*
2. Run anime-face-gen file
