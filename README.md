## MNIST Autoencoder

Just an autoencoder example, specifically for the MNIST dataset.
This compresses the image from 786 dimmensions down to 8.

## Usage
```python
>>> python autoencoder.py
```

This will automatically download the MNIST dataset. Batch size is set to 1000 so you might want to change it depending on your system.
A checkpoint is included in the `checkpoint` folder, and will automatically be loaded upon running. To train your own, delete the checkpoint.

### Results

It didn't do too bad considering the images are compressed to only 8 dimensions. Below are some examples.

![img](http://i.imgur.com/Qa6HfhT.png) ![img](http://i.imgur.com/EGekJBm.png)

![img](http://i.imgur.com/HGo4Rso.png) ![img](http://i.imgur.com/WKnig11.png)

![img](http://i.imgur.com/GTM05PF.png) ![img](http://i.imgur.com/D0WpaNy.png)

![img](http://i.imgur.com/uBm7gGD.png) ![img](http://i.imgur.com/ba3vFsd.png)

