### Condition Deep Convolution Generative Adversarial Network

The multi-condition deep convolution generation countermeasure network is applied to the implementation of Tensorflow in clothing design, which is a stable generation countermeasure network.

![sample](https://github.com/beng7777/C-DCGAN-Clothing-Design/blob/master/sample/C-DCGAN.png)

### Prerequisites

- python 3.5+
- Tensorflow 1.31.1
- Scipy
- pillow
- moviepy
- opencv-python

### Usage

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

### Results

Fashion-mnist

![sample](https://github.com/beng7777/C-DCGAN-Clothing-Design/blob/master/sample/result-f-mnist-T.png)

![sample](https://github.com/beng7777/C-DCGAN-Clothing-Design/blob/master/sample/result-f-mnist-P.png)

Clothing-co-Parsing:

![sample](https://github.com/beng7777/C-DCGAN-Clothing-Design/blob/master/sample/result-ccp-young.png)

![sample](https://github.com/beng7777/C-DCGAN-Clothing-Design/blob/master/sample/result-ccp-sports.png)

### Reference
Thank you very much to Radford et al([DCGAN](https://arxiv.org/abs/1511.06434))

Thank you very much for the code reference(https://github.com/carpedm20/DCGAN-tensorflow)

### Author
Li Minqi, Dong Zhaoxiong, Liu zhe, Li ben, Liu shan, Deng Wei, Gong Mengchan
