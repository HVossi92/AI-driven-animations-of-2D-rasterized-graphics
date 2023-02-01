# AI-driven-animations-of-2D-rasterized-graphics
Master thesis: AI-driven animations of 2D rasterized graphics

# Abstract

Manual keyframe animation is an integral part of the post-production process for 2D animations. Despite this, little research has been undertaken to utilize advances in artificial intelligence to improve this process, which still takes considerable user effort. 

Inspired by recent progress in image manipulation and time series prediction through machine learning, this thesis examines the possibility of automatically creating animations between two rasterized graphics. The focus lies on small black and white 2D icon animations.

To this end, I create and compare different neural network architectures and present a multi-layered process built upon a convolutional neural network, called akaNet, for predicting the frames between a given input and output graphic. This approach gets augmented by a novel workflow using recursive triads for improved time series prediction results.

# Contents
- Master Thesis_v19_v04_PUBLISHED.pdf: The reworked Master thesis as pdf
- Webscraping chapter 4.2.1:    
    - https://github.com/HVossi92/gif_scraper
    - https://github.com/HVossi92/selenium_gif_scraper    
- Data processing chapter 4.2.2:
    - https://github.com/HVossi92/Gif_and_img_sequence_to_numpy_converter
    - https://github.com/HVossi92/Gif_to_image_sequence_converter
- recursiveTriads: chapter 5.2 Peri-processing: Recursive Triads
- anaconda_jupyter_lab: Contains the code of the different machine learning architectures
    - keras2.yml: The anaconda environment
    - mlp: chapter 5.5 Multilayer perceptron (MLP) architecture
    - rnn: chapter 5.6.1 Recurrent neural network (RNN)
    - lstm: chapter 5.6.2 Long Short-Term Memory (LSTM)
    - gru: chapter 5.6.3 Gated Recurrent Unit (GRU)
    - convLstm: chapter 5.7.1 Convolutional Long Short-Term Memory (ConvLSTM)
    - resNet: chapter 5.7.2 ResNet-34 
    - bbCnn: chapter 5.7.3 Convolutional Neural Network (CNN / bbCNN)
    - akaNet: chapter 5.7.7 Automated keyframe animation network (akaNet)
    - convVaei: chapter 5.7.8 Convolutional variational autoencoder (ConvV AE)

