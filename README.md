### Neural_Style_Transfer

We have used a pretrained VGG19 model for this purpose. For the content cost, we are extracting the activation a_C from conv4_2 layer.
And, for the style cost we are taking a weighted sum of the activations of some layers.

Download VGG19 - https://www.kaggle.com/teksab/imagenetvggverydeep19.mat 
