# AML1
Spring 2023 CS 504 AML Project 1
https://knowyourdata-tfds.withgoogle.com/#tab=STATS&dataset=imagenette

Imagenette is a subset of 10 easily classified classes from the Imagenet dataset. It was originally prepared by Jeremy Howard of FastAI. 

The objective behind putting together a small version of the Imagenet dataset was mainly because running new ideas/algorithms/experiments on the whole Imagenet take a lot of time.

This version of the dataset allows researchers/practitioners to quickly try out ideas and share with others. The dataset comes in three variants: Full size,320 px
and 160 px.

For now, i will use 160px.
 **use TF_VGG-R50_Imagenette.ipynb for this task**
 ---
 
 
 # AML2
 
- The assignment is due by the end of the day on Thursday, March 2.
- Objective:Implement black-box evasion attacks against deep learning-based classification models.

The Boundary Attack is a black-box evasion attack based on the paper by Brendel et al. (2018), which we covered in Lecture 5

The following notebook in the Adversarial Robustness Toolbox explains the implementation of the boundary attack on ImageNet images.

The boundary attack uses only the final predicted label by a black-box model to create adversarial samples, i.e., it is a decision-based attack.

Dataset: We will use the FIGRIM dataset, consisting of 4,436 images of 11 scenes. Examples of images from the dataset are shown in Figure 1. The dataset and a Data Loader code can be downloaded from this Shared folder on OneDrive. The file with the images is named ‘SCENES_700x700.zip’ (287 MB).
