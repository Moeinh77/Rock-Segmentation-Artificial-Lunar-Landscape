# Rock-Segmentation-Artificial-Lunar-Landscape
Kaggle's Photorealistic images of the Moon's surface with ground truth rock segmentation.

You can learn about this data set at : https://www.kaggle.com/romainpessia/artificial-lunar-rocky-landscape-dataset

I used a pretrained ResNet-34 as the backbone network for image segmentation. The training took almost 2 hours on Kaggle's tesla P-100.

### Results:

|train_loss|valid_loss|seg_accuracy|
| :---: | :---: | :---: |
|0.128909	|0.131276	|0.963635|

### Results from the trained model:

![](http://www.mediafire.com/convkey/2653/4p6yb7umb98kmpnzg.jpg)
