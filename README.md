# Rock-Segmentation-Artificial-Lunar-Landscape
Kaggle's Photorealistic images of the Moon's surface with ground truth rock segmentation.

### Dataset:
The goal of this dataset is to provide everyone with a sample of artificial yet realistic lunar landscapes, which can be used to train rock detection algorithms. Those trained algorithms can then be tested on actual lunar pictures.
You can learn about this data set at : https://www.kaggle.com/romainpessia/artificial-lunar-rocky-landscape-dataset

### Model:
UNet is the model of choice for this taks in my project and I have used a pretrained ResNet-34 as the backbone network. Adam is has been my optimizer of choice. The training took almost 2 hours on Kaggle's tesla P-100 to reach accuracy of 0.96 on validation set.


### Results:
|train_loss|valid_loss|seg_accuracy|
| :---: | :---: | :---: |
|0.128909	|0.131276	|0.963635|

### Predictions from the trained model:

![](http://www.mediafire.com/convkey/2653/4p6yb7umb98kmpnzg.jpg)
