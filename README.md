Image Caption Generator
 
 Image caption generator is a model which generates caption based on the features present in
 the input image.
 Introduction
 The basic working of the project is that the features are extracted from the images using pre
trained VGG16 model and then fed to the LSTM model along with the captions to train. The
 trained model is then capable of generating captions for any images that are fed to it.
 Dataset
 The dataset used here is the 
FLICKR 8K which consists of around 8091 images along with 5
 captions for each images. If you have a powerful system with more than 16 GB RAM and a
 graphic card with more than 4 GB of memory, you can try to take 
30,000 images with captions.
 Dependencies
 Keras
 Tensor ow GPU
 Pre-trained VGG-16 weights
 NLTK
 Matplotlib
