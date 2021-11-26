# VRDL_HW2

## The link of my Colab
#### Remember to use the NYCU account
https://colab.research.google.com/drive/1R7_y5zeQV7vMwxg-fRECrMuVT1AYf5Zb?usp=sharing

or just run SVHN.ipynb

## Dataset Download
```
!gdown --id '1lrKueI4HrySQDGvpkilQN9BfaMUN7hZi' --output train.zip

!apt-get install unzi
!unzip -q 'train.zip' -d train

!gdown --id '1Fm-avdeNgzhPxhvia0iw9yZzcoOggy7I' --output test.zip
!unzip -q 'test.zip' -d test
```
## Model Configurations

import config directory to train the models
```
%cd mmdetection
%mkdir checkpoints
%cd checkpoints

config = '/content/mmdetection/configs/faster_rcnn/faster_rcnn_r50_fpn_1x_coco.py'

!wget https://download.openmmlab.com/mmdetection/v2.0/faster_rcnn/faster_rcnn_r50_fpn_1x_coco/faster_rcnn_r50_fpn_1x_coco_20200130-047c8118.pth
```

## Training
Use Faster R-CNN

## inference
#### Remember to use the NYCU account

https://colab.research.google.com/drive/1Bzbm64kh8B-YKJxlsNXlZYBLZQwarPXx?authuser=7#scrollTo=otPgm84G8usO

or just run inference.ipynb
