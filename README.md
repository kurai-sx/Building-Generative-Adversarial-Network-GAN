# What is Fashion GAN?
The Fashion Generative Adversarial Network (GAN) is a project focused on generating realistic fashion images using advanced machine learning techniques. GANs are a class of neural networks that consist of two models: a Generator and a Discriminator. The Generator creates new, synthetic images, while the Discriminator evaluates them against real images to distinguish between generated and authentic ones.
Key Features
Image Generation: The GAN is trained to generate high-quality fashion images from random noise, simulating various clothing items and styles.
Discriminator Training: The Discriminator improves its ability to differentiate between real and generated images, enhancing the quality of the Generator’s output over time.
Visual Results: The project includes various stages of training with visual results showcasing the improvements in generated image quality.
# Creation-of-Generative-Adversarial-Network-GAN
<img src = "https://github.com/kurai-sx/Fashion-Generative-Adversarial-Network-GAN/blob/main/GAN's/Images/GAN%20Model.png" >

# Before Training Images
<img src = "https://github.com/kurai-sx/Fashion-Generative-Adversarial-Network-GAN/blob/main/GAN's/Images/Before%20Training.png" >

# Image Generated after Training
<img src = "https://github.com/kurai-sx/Fashion-Generative-Adversarial-Network-GAN/blob/main/GAN's/Images/Image%20Generation%20through%20Model.png" >

# Review Graph of Gen and Disc
<img src = "https://github.com/kurai-sx/Fashion-Generative-Adversarial-Network-GAN/blob/main/GAN's/Images/Review%20of%20Gen%20and%20Disc.png" >

### Install the Dependencies

```bash
pip install tensorflow
pip install tensorflow-gpu
pip install matplotlib
pip install tensorflow-datasets
pip install ipwidgets
```

### Import the Libraries and Models from TensorFlow 

```bash
import tensorflow as tf
import tensorflow_datasets as tfds
import matplotlib.pyplot as plt
import numpy as np
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Conv2D, Reshape, Dense, Flatten, LeakyReLU, Dropout, UpSampling2D
from tensorflow.keras.optimizers import Adam
from tensorflow.keras.losses import BinaryCrossentropy
from tensorflow.keras.models import Model
import os
from tensorflow.keras.preprocessing.image import array_to_img
from tensorflow.keras.callbacks import Callback
```

### Saving Models
```bash
generator.save('generator.h5')
discriminator.save('discriminator.h5')
```

### NOTE
```bash
Make Sure your Epoch is atleast 2000 so that you can generate good quality of images,
also it will take a lot of time to train with this epoch but it would be worth it.
```

## Contributors
<a target="_blank" href="https://github.com/kurai-sx" ><img src="https://avatars.githubusercontent.com/u/84697122?v=4" href="https://github.com/kurai-sx" alt="kurai-sx" width="50"/></a>
