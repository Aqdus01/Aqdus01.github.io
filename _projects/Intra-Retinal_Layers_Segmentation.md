---
title: "Facial Emotional Recognition for People with Traumatic Brain Injury"
collection: projects
excerpt: "Deep Learning Based Automated Extraction of Intra-Retinal Layers for Analyzing Retinal Anomalies "
imageurl: '/images/projects/p3_1.PNG'
date: 2021-07-01

---

<center><img src="/images/projects/p3_1.PNG"></center>


## Abstract 
Blindness eliminates a person vision and retinal abnormalities are the second biggest reason of blindness across the globe. Each retinal abnormality affects one or more retinal layers or retinal surface. So, if we want to diagnose a particular retinal abnormality we have to extract the retinal layers to analyze the effects of that particular abnormality. Manual extraction of these retinal layers is possible but it is a cumbersome and time-consuming task. So, in our
final year project we proposed a computer aided self-diagnostic system that could help the ophthalmologists in mass screening of retinal patients. In this project we have proposed the algorithms which are based on convolutional neural network (CNN). We have used two different approaches to use the CNN along with other techniques. In first method we have
combined CNN with structure tensor and termed this method as convolutional neural network and structure tensor-based segmentation framework (CNN-STSF). In this method AlexNet (a
pre-trained model) has been used through Transfer Learning technique. AlexNet was trained on more than 1000 patches of retinal layers and then it could successfully classify each retinal layer patch pass through it. In second approach we have used Gabor filter along with CNN to find the boundaries of each retinal layer. We have also used the flattening technique before Gabor filter to increase the horizontal shape of retina by flattening the curvature of retinal layers. And then before plotting the lines on retinal layers we have de-flattened the layers to restore their original shape and to represent the boundaries of retinal layers on original OCT scan. The proposed algorithms have been tested and validated on OCT scans which were acquired from Armed Forces Institute of Ophthalmology (AFIO) dataset and Duke University publically available dataset of OCT images.


<center><img src="/images/projects/p3_2.png"></center>


## Files

- [PhD Thesis](/files/BS_Thesis.pdf)
