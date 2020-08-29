# ComputerVision_CatAndDog
#### About:
This Repository originated from a Computer Vision Challenge at [linkit](https://www.linkit.tech), where teams of up to 3 persons had a week to submit predicitons of a test-data set with pictures of cats and dogs. The data-set the model is trained on is from kaggle.

We achieved a accurracy of 98.18%


#### Code:
Our Model uses transfer-learning to achieve such high accuracy. We froze all layers, except the last 4 of the InceptionResnetV2. Also we used [imagaug](https://imgaug.readthedocs.io/en/latest/source/examples_basics.html) a heavy Image Augmentation to make our model more robust.

For more information just take a glimpse on the code.
