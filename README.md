# Automatic Seismic Salt Interpretation with Deep Convolutional Neural Networks

Author: Yu (Jason) Zeng  &nbsp; &nbsp;| &nbsp; &nbsp; Email: yu.zeng.duke@gmail.com  &nbsp; &nbsp;| &nbsp; &nbsp; Date: Feb. 08, 2019

This folder contains sample Python codes to prepare input data staring from SEGYs and to construct / train convolutional neural networks for automatic seismic salt interpretation with Deep Convolutional Neural networks. The great potential of CNN-based salt boy interpretation is demonstrated by using a state-of-art network structure U-Net, along with the residual learning framework ResNet, to delineate salt body with high precision. Network adjustments, including the Exponential Linear Units (ELU) activation function, the Lovasz-Softmax hinge loss, and the stratified K-fold cross-validation, have been deployed to further improve the prediction accuracy.

> Our paper entitled **Automatic Seismic Salt Interpretation with Deep Convolutional Neural Networks** ([arxiv:1802.01101](https://arxiv.org/abs/1812.01101)) has summarzied this work and has been accepted by *The 3rd International Conference on Information System and Data Mining* ([ICISDM 2019](http://icisdm.org/)). My co-authors of this paper are Kebei Jiang and Jie Chen.

Two main Jupyter notebooks are posted here:
1. *[salt_body_segyin_data_prep.ipynb](salt_body_segyin_data_prep.ipynb)* 
   * This notebook covers data preparation from SEGY, image upsampling, image cropping.
   
2. *[salt_body_interpret_deep_cnn.ipynb](salt_body_interpret_deep_cnn.ipynb)* 
   * This notebook covers evaluation metric, network architecture, network training, model improvements, discussion and conclusion. 

Suggestions or comments are welcome!
