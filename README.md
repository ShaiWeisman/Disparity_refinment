# Disparity_refinment
Calculating Disparity Images with Denoising Joint Filtering using Deep Convolutional Networks </br>

## Abstract

Disparity estimation is a challenging task in stereo vision because the correspondence technique fails in images with texture less, repetitive and\or caged regions. Our proposed network is a combination of two independent CNNs, DenseMapNet for disparity estimation and JointFilterNet  for post processing and noise reduction. The DenseMapNet is CNN implementation inspired by dense networks to reduce the number of parameters and allowing fast implantation. The JoinFilterNet is based on a CNN, that can selectively transfer salient structures that are consistent with both guidance and target images. In our end results we can see on certain images improvement between the Dense map using the JF filter than without. 

## Main refrences

Stereo Data </br>
N. Mayer and E. Ilg and P. H{\"a}usser and P. Fischer and D. Cremers and A. Dosovitskiy and T. Brox,
"A Large Dataset to Train Convolutional Network for Disparity, Optical Flow, and Scene Flow Estimation",
IEEE International Conference on Computer Vision and Pattern Recognition (CVPR),2016,arXiv:1512.02134

Disparity network:</br>
R. Atienza, "Fast Disparity Estimation using Dense Networks," 2018.

Refienment network: </br>
J.-B. H. N. A. a. M.-H. Y. Yijun Li, "Joint Image Filtering with Deep Convolutional Networks," 2017

