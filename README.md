# Pneumonia-detection-using-CNN
This project is a image classification of chest x-rays consisting of 5856 files which are  1.26GB of size in total

This project has two models model_1 and model_2 which have different activation layers and have a total of 9 layers each
The dataset was taken from kaggle (https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)


Both the models use convolutional neural network


 Model_1 
________________________________

This is a standard CNN model containg 9 layers no measures have been taken to prevent overfitting and hence this model performed relatively poorly when compared to model_2
An overall accuracy of ~ 75% was reached even after training for 50 epochs


Model_2
________________________________

This is a standard CNN model containg 9 layers measures such as data agumentation and dropout have been taken to prevent overfitting and hence this model
performed relatively better when compared to model_1
An overall accuracy of ~ 85% was reached even after training for 50 epochs


To test the models performance few images from the internet from various sources were tested in which model_2 performed better whwn compared to the first model
