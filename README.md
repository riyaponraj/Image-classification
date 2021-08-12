

# Project Title : IMAGE CLASSIFICATION USING CIFAR - 10 DATASET

In this project, I'm classifying images from CIFAR-10 dataset using CNN.

CIFAR-10 is an image dataset which can be downloaded from here. It contains 60000 tiny color images with the size of 32 by 32 pixels. The dataset consists of 10 different classes (i.e. airplane, automobile, bird, cat, deer, dog, frog, horse, ship and truck), in which each of those classes consists of 6000 images. On the other hand, CNN is used in this project due to its robustness when it comes to image classification task.	 


# Table of contents


- [Project Name](#project-title)
- [Table of contents](#table-of-contents)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Tensorboard](#Tensorboard)


# Installation
[(Back to top)](#table-of-contents)
 

```conda create --[envname]```

```conda install TensorFlow```

```conda activate [env]```

```jupyter notebook```

# Dependencies

* Jupyter 
* Keras
* Tensorflow
* Matplotlib


# Usage
[(Back to top)](#table-of-contents)

This dataset can allow researchers to quickly try different algorithms to see what works.
In this model, I used CNN to train the model.

#Tensorboard

To set the directory for saving logs,

```log_dir = "logs/fit/" + datetime.datetime.now().strftime("%Y%m%d-%H%M%S")```

Setting up Callbacks,

```tensorboard_callback = tf.keras.callbacks.TensorBoard(log_dir=log_dir, histogram_freq=1)```

To view tensorboard,

```%load_ext tensorboard```
```%tensorboard --logdir logs/fit```

![alt text] (https://github.com/riyaponraj/Image-classification/blob/main/cnn.png)






