# IBB-project-2
Image detection/segmentation

## Object detection
In this assignment I am going to implement R-CNN from scratch in Keras using Airplane data-set from http://www.escience.cn/people/JunweiHan/NWPU-RESISC45.html.

### Procedure

1. Image preprocessing and preparation
2. Running selective search algorithm to obtain 2000 most interesting regions
3. From those 2000 regions obtain 30 (sub)images that have the highest IoU (positive cases) and 30 that have the lowest IoU
4. Using a pretrained model VGG16 trained on ImageNet and apply/fit the model to our problem
5. Use the final model to predict bounding box areas of test images
