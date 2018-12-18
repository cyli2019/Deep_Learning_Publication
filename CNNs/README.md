[//]: # (Image References)

# Publications on Convolutional Neural Networks

*Must reading: [Introduction to Convolutional Neural Networks][intro] - Jiaxin Wu*

## Index

*There is already brief summaries for some of those on [this medium post][medium]*

- 1: [LeNet][lenet] — LeCun 1998 
- 2: [AlexNet][alexnet] — Krizhevsky 2012 
- 3: [GoogLeNet][googlenet] / Inception — Szegedy 2014
- 4: [VGG][vgg] — Simonyan / Zisserman 2014 
- 5: [ResNets][resnet] — He - 2015
- 6: [DenseNets][densenets] - Huang - 2016 
- 7: [FractalNets][fractalnets] — Larsson — 2016
- 8: [SENets][senets] — Hu — 2018 
- 9: [MobileNets][mobilenets] — Howard — 2016 

[//]: # (General Links)
[intro]: https://pdfs.semanticscholar.org/450c/a19932fcef1ca6d0442cbf52fec38fb9d1e5.pdf
[medium]: https://towardsdatascience.com/deep-convolutional-neural-networks-ccf96f830178

[//]: # (Index Links)
[lenet]: http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf
[alexnet]: http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf
[googlenet]: https://arxiv.org/pdf/1409.4842.pdf
[vgg]: https://arxiv.org/pdf/1409.1556v6.pdf
[resnet]: https://arxiv.org/pdf/1512.03385.pdf 
[densenets]: https://arxiv.org/pdf/1608.06993.pdf  
[fractalnets]: https://arxiv.org/pdf/1605.07648.pdf  
[senets]: https://arxiv.org/pdf/1709.01507.pdf  
[mobilenets]: https://arxiv.org/pdf/1704.04861.pdf  


(TO BE IMPLEMENTED)  

## 1 - LeNet
...

## 2 - AlexNet

![alexnetpic][alexnetpic]
#### What are the key innovations?
- Increase depth of previous state-of-art CNN models
- Multi-GPU implementation of a CNN, resulting on: 
  - Higher accuracy
  - Lower training time
- Introduce the Dropout strategy ![dropoutpic]
- Demostrated big improvement caused by Rectified Linear Units (ReLU)


## 2 - GoogleNet

![googlenetpic][googlenetpic]
#### What are the key innovations?
- Introduce the use of filters of different sizes to handle multiple scales  
- Use of 1x1 convolutions (after the [Network in Network][nin] paper). Why?
  - It would be benefitial to move to sparsely connected architectures to mimick the biological systems for vision explained by the [Hebbian Principle][hebbian]. BUT, today computing infrastructure are not efficient enough with sparse data structure to pay off the swithc.  
  
- Inception Module:
  - How can an optimal local sparse structure in a CNN can be approximated by dense components?


...


[//]: # (LeNet Links)  


[//]: # (AlexNet Links)  
[alexnetpic]: https://github.com/Udacity-PyTorchChallenge-Students-Group/Deep_Learning_Publication/blob/master/CNNs/images/alexnet/architecture.png?raw=true
![dropoutpic]: https://github.com/Udacity-PyTorchChallenge-Students-Group/Deep_Learning_Publication/blob/master/CNNs/images/alexnet/dropout.png?raw=true 


[//]: # (GoogleNet Links)   
[googlenetpic]: https://www.researchgate.net/profile/Ronojoy_Adhikari/publication/313248299/figure/fig10/AS:457566913339400@1486103861987/The-Inception-Module-in-GoogLeNet_W840.jpg
[nin]: https://arxiv.org/pdf/1312.4400.pdf 
[hebbian]: https://en.wikipedia.org/wiki/Hebbian_theory

...
