# CNN_Data_Augmentation
<p>Data augmentation is a technique to artificially create new training data from existing training data. This is done by applying domain-specific techniques to examples from the training data that create new and different training examples.</p>
<p> In this technique, we generate new instances of images by cropping, flipping, zooming, shearing an original image. So, whenever the training lacks the image dataset, using augmentation, we can create thousands of images to train the model perfectly.</p>
<br>

### Dataset used : [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)

Fashion-MNIST is intended to serve as a direct drop-in replacement for the original MNIST dataset to benchmark machine learning algorithms, as it shares the same image size and the structure of training and testing splits.
You can import it directly using:
```
from keras.datasets import fashion_mnist
```
This is a dataset of 60,000 28x28 grayscale images of 10 fashion categories, along with a test set of 10,000 images.
The class labels are:


| Label |	Description |
| :- | :- | 
| 0 |	T-shirt/top 
|1 |	Trouser
|2 |	Pullover
|3 |	Dress
|4 |	Coat
|5 |	Sandal
|6 |	Shirt
|7 |	Sneaker
|8 |  Bag
|9 |	Ankle boot

## Python environment [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1r4rxciDUI79QMEj_26rMJeZ_jZHugrbT?usp=sharing)
Give it a try, no need of installations!
<br>

## Notes
If you still insist to run it on your PC, the `requirements.txt` file should list all Python libraries that the notebook
depends on, please install them on a virtual env using:
<br>


Anaconda:
```
$ conda create --name newenv --file requirements.txt
```
Python3
```
$ pip3 install -r requirements.txt
```
