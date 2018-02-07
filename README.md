# CNN-GoogLeNet
🕵🏻 Vision : Model 4: GoogLeNet : Image Classification


GoogleNet V-1 ( Inception_V1 ) : 
-
<b>Paper : </b> " [Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842) "  <b>Talk :</b> [ILSVRC 2014](https://youtu.be/ySrj_G5gHWI) <b> CVPR Presentation : </b> [CVPR 2015](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Szegedy_Going_Deeper_With_2015_CVPR_paper.html)

2014 [ILSVRC](http://www.image-net.org/challenges/LSVRC/) ([ImageNet](http://www.image-net.org/) Large-Scale Visual Recognition Challenge) <b>Winner</b>.

It is a benchmark competition where teams across the world compete to classify, localize, detect ... images of 1000 categories, taken from the imagenet dataset.The imagenet dataset holds 15M images of 22K categories but for this contest: 1.2M images in 1K categories were chosen.Their goal was, Classification i.e, make 5 guesses about label for an image.Team " GoogLeNet ", achieved top 5 test error rate of 6.7%. It was a better than any other model's performance at that time. Check ILSVRC 2014 [results](http://www.image-net.org/challenges/LSVRC/2014/results).

This paper is important as it is one of the first CNN architectures that really strayed from the general approach of simply stacking conv and pooling layers on top of each other in a sequential structure.The authors of the paper also emphasized that this new model places notable consideration on memory and power usage.

<img src="https://github.com/SKKSaikia/CNN-GoogLeNet/blob/master/img/GoogleNet.gif">

Overview
-

Architecture
-

model.summary()
-

Important Points
-

Practical
-

<img src="https://github.com/SKKSaikia/CNN-GoogLeNet/blob/master/img/g1.jpg">


<img src="https://github.com/SKKSaikia/CNN-GoogLeNet/blob/master/img/g2.jpg">

GoogleNet V-2 ( Inception_V2 )
-
Paper : " [Rethinking the Inception Architecture for Computer Vision](https://arxiv.org/abs/1512.00567) "

GoogleNet V-3 ( Inception_V3 )
-
Paper : " [Rethinking the Inception Architecture for Computer Vision](https://arxiv.org/abs/1512.00567) "

GoogleNet V-4 ( InceptionResNet_V2 )
-
Paper : " [Inception-ResNet and the Impact of Residual Connections on Learning](https://arxiv.org/abs/1602.07261) "

References
-
    
      CS231n : Lecture 9 | CNN Architectures - GoogLeNet
      adeshpande3.github.io for /gif 
