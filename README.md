# Building-a-Mobile-Friendly-PokeDex
A 10-way Pokemon Classification using Deep Learning.

Convolutional neural networks are deep artificial neural networks that are used primarily to classify images (e.g. name what they see), cluster them by similarity (photo search), and perform object recognition within scenes. They are algorithms that can identify faces, individuals, street signs, tumors, platypuses and many other aspects of visual data.

Note - There are two different models I used. These are based upon following research papers:-

1) Alexnet 2012 :https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf

2) Mobilenets 2017 :https://arxiv.org/abs/1704.04861

Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton created a “large, deep convolutional neural network” that was used to win the 2012 ILSVRC (ImageNet Large-Scale Visual Recognition Challenge) called AlexNet.The network was made up of 5 conv layers, max-pooling layers, dropout layers, and 3 fully connected layers.

<img src="https://sushscience.files.wordpress.com/2016/11/alexnet.jpg?w=900" alt="">

Steps involved:
1. Model-1 :Implement Alexnet in Keras

There are a number of images from 10 classes of pokemons and we want to build and train AlexNet on the given data. 

2. Model-2 :Using Transfer learning on Mobilenet

I used Use Transfer Learning/Fine-Tuning to improve the accuracy that I got from Alexnet. We can use any pre-trained network like Resnet, Inception, Mobilenet from Keras and fine tune it using small learning rate. If you want to build an efficient memory friendly network - then MobileNet can be good choice as it uses light-weight convolutions, which reduce the number of parameters and model size is of few MB's which can easily fit inside Phone Memory!
