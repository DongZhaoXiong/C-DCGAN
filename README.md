# C-DCGAN in Tensorflow

The multi-condition deep convolution generation countermeasure network is applied to the implementation of Tensorflow in clothing design, which is a stable generation countermeasure network.

![sample](https://github.com//sample//C-DCGAN.png)

## Prerequisites

- python 3.5+
- Tensorflow 1.31.1
- Scipy
- pillow
- moviepy
- opencv-python

## Use

First, prepare dataset，Here we used the Fashion- Mnist and Clothing-co -Parsing dataset

- Fashion-Mnist
- Clothing-co-Parsing(CCP)

To train a model with dataset:

~~~
python train.py --dataset your_train_dataset --input_height=image_h --output_height=new_image_h --train
~~~

To test with an existing model:

~~~
python train.py --dataset your_test_dataset --input_height=image_h --output_height=new_image_h
~~~

## Results

Fashion-mnist

![](D:\C-DCGAN-Clothing-Design\sample\result-f-mnist-T.png)

![](D:\C-DCGAN-Clothing-Design\sample\result-f-mnist-P.png)

Clothing-co-Parsing:

![](D:\C-DCGAN-Clothing-Design\sample\resutl-ccp-young.png)

![](D:\C-DCGAN-Clothing-Design\sample\result-ccp-sports.png)

