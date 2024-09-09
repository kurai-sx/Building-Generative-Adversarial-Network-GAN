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

### Import the Command

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

## Contributors
<a target="_blank" href="https://github.com/kurai-sx" ><img src="https://avatars.githubusercontent.com/u/84697122?v=4" href="https://github.com/kurai-sx" alt="kurai-sx" width="50"/></a>
