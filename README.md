# DeepHuman
------------
<br>Human related deep learning papers datasets, models and comments.<br />

## Segmentation  
1. Mask R-CNN: [[PDF](https://arxiv.org/pdf/1703.06870.pdf)]  
Abs: We present a conceptually simple, flexible, and general framework for object instance segmentation. Our approach efficiently detects objects in an image while simultaneously generating a high-quality segmentation mask for each instance. The method, called Mask R-CNN, extends Faster R-CNN by adding a branch for predicting an object mask in parallel with the existing branch for bounding box recognition. Mask R-CNN is simple to train and adds only a small overhead to Faster R-CNN, running at 5 fps. Moreover, Mask R-CNN is easy to generalize to other tasks, e.g., allowing us to estimate human poses in the same framework. We show top results in all three tracks of the COCO suite of challenges, including instance segmentation, bounding-box object detection, and person keypoint detection. Without tricks, Mask R-CNN outperforms all existing, single-model entries on every task, including the COCO 2016 challenge winners. We hope our simple and effective approach will serve as a solid baseline and help ease future research in instance-level recognition. Code will be made available.  





2. Semantic Segmentation: [Presentation](http://www.robots.ox.ac.uk/~sadeep/files/crfasrnn_presentation.pdf)  




## Pose  
1. Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields:[[paper](https://arxiv.org/pdf/1611.08050.pdf)]
https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation  
imagenet presentation: [link](http://image-net.org/challenges/talks/2016/Multi-person%20pose%20estimation-CMU.pdf)  
<br>experiment :<br/>
<br>The model works realtime one any computer/laptop.<br/>

Pro:  
Realtime on images/video on most desktop  
Track multiple people (>30)  
Works well with overcoat/hijaab etc  
Works across scale  

Cons:  
Confuses when two people are very close.  
Very far are not recognized well  

![alt tag1](https://github.com/nishathussain/DeepHuman/blob/master/pose/11.png )
![alt tag1](https://github.com/nishathussain/DeepHuman/blob/master/pose/22.png )
![alt tag1](https://github.com/nishathussain/DeepHuman/blob/master/pose/33.png )
![alt tag1](https://github.com/nishathussain/DeepHuman/blob/master/pose/44.png )

Pytorch implementation of the same: [[GitHub](https://github.com/tensorboy/pytorch_Realtime_Multi-Person_Pose_Estimation)]


2. Deepcut-cnn:[[paper]()][[dataset]()]  

## Skin

## Body parts
1. SSD: Single Shot MultiBox Detector [[paper](https://arxiv.org/abs/1512.02325)] , [[GitHub Pytorch](https://github.com/nishathussain/ssd.pytorch)]
results will be published soon.
Pro:
Fully conv approach
## Clothings
1. Cross-Scenario Clothing Retrieval and Fine-grained Style Recognition: [[paper](http://vision.unipv.it/CV/materiale2016-17/2nd%20Choice/0132.pdf)] ,[dataset]  

2. Convolutional Neural Networks for Fashion Classification and Object Detection: [paper](https://pdfs.semanticscholar.org/68ec/d5468644a0cdcffea0915e839667c500d4f5.pdf), [dataset]  

3. Learning Visual Clothing Style with Heterogeneous Dyadic Co-occurrences:[[paper](https://cseweb.ucsd.edu/~jmcauley/pdfs/iccv15.pdf)],[dataset]  

4. DeepFashion: Powering Robust Clothes Recognition and Retrieval with Rich Annotations: [[Paper](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DeepFashion_Powering_Robust_CVPR_2016_paper.pdf)], [[dataset](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)]  
exploring the dataset  
5. Apparel Classifier and Recommender using Deep Learning:[[paper](https://pdfs.semanticscholar.org/68ec/d5468644a0cdcffea0915e839667c500d4f5.pdf)],[dataset]  
## Style

