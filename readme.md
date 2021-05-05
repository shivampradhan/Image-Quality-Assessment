# Image Quality Assesment

TO identify the quality of image and classifing if the image is a good quality image or bad quality image


![alt text](https://github.com/shivampradhan/Image-Quality-Assessment/blob/master/test_images/1267_in3.png)
![alt text](https://github.com/shivampradhan/Image-Quality-Assessment/blob/master/test_images/1332.png)


# Approach 

## Data Augmentation,Cleaning and Splitting
As the number of good quality images in our dataset is less we have performed several data augmentation technicse
Once we have certain amount of data we have split the data in train and validation/test sets.
since this is a image dataset we have used split-folders to perform this data.

## Transfer Learning
Once Data Augumentation and Data splitting is done we have the a good dataset .
but still this amount of dataset is not sufficient for training a model from scratch so we have use Transfer Learning.

We have efficient net model trained on imagenet dataset
we removed the end few layers and make it robust to be used as a binary classifier.
## Training the Classifier
Once we are done with that, we have trained on model on GPU using google collab.

## Prediction
After the training is done we have saved the model and use it for prediction on sample dataset to showcase our model results.
