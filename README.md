# Covid-Mask-Detection-AI

In this project I have created an Convulation Neural Netwoork from scratch to detect wether a person is wearing a mask or not.
The Deep Learning Model has achieved a 97.1 percent accuracy 
the code for the Machine Learning Model is in the train_model.ipynb file 
We havent presented the machine Leaerning model in this file , So in order to get the model runn all the cells in train_model.ipynb file along with 
mentioning the paths correctly according to your pc evironment 
## In order to work several packages are meant to be installed 
* tensorflow 
* keras 
* numpy 
* opencv 

### The Deep Learing model is then implemented in the maskdetectcv.py file 
In this file we can pass on a video or direct camera feed which will detect faces using the haar_face.xml model 
from opencv in which we get face region of interest (face_roi)
We are passing the  face_roi as input for the deep learning model which then gives us thge label 

