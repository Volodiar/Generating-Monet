# Generating-Monet
## Kaggle competition: I’m Something of a Painter Myself?


We recognize the works of artists through their unique style, such as color choices or brush strokes. The “je ne sais quoi” of artists like Claude Monet can now be imitated with algorithms thanks to generative adversarial networks (GANs).

Computer vision has advanced tremendously in recent years and GANs are now capable of mimicking objects in a very convincing way. But creating museum-worthy masterpieces is thought of to be, well, more art than science.

Since the dataset contains unpaired images, we are going to use a CycleGAN architecture model (https://arxiv.org/pdf/1703.10593.pdf). 


### The data

The dataset contains four directories: `monet_tfrec`, `photo_tfrec`, `monet_jpg`, and `photo_jpg`. The `monet_tfrec` and `monet_jpg` directories contain the same painting images, and the `photo_tfrec` and `photo_jpg` directories contain the same photos.

The `monet` directories contain Monet paintings. Use these images to train your model.

The `photo` directories contain photos. 