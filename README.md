# Artificial-Intelligence-Comprehensive-Course-Design

## Datasets
[Caltech-UCSD Birds-200-2011](https://data.caltech.edu/records/20098), [Standford Cars](https://ai.stanford.edu/~jkrause/cars/car_dataset.html), [Standford Dogs](http://vision.stanford.edu/aditya86/ImageNetDogs/main.html), [*mini*ImageNet](https://arxiv.org/abs/1606.04080v2), [*tiered*ImageNet](https://arxiv.org/abs/1803.00676) and [WebCaricature](https://arxiv.org/abs/1703.03230) are available at [Google Drive](https://drive.google.com/drive/u/1/folders/1SEoARH5rADckI-_gZSQRkLclrunL-yb0) and [百度网盘(提取码：yr1w)](https://pan.baidu.com/s/1M3jFo2OI5GTOpytxgtO1qA).

## Train

在Config文件夹中放置了DeepBDC对于不同数据集的训练细节调整，在run_trainer.py中读取不同yaml即可。

## Test

在run_test.py中调整PATH，也就是训练后在results中生成的文件夹路径。
