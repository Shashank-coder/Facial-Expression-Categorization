# Facial-Expression-Categorization
A model which categorizes a facial expression in one of seven categories namely happy, sad, angry, disgust, surprise, contempt, neutral

The New Data Set

This time we are approaching from the very basic. We have collected the images of some people having various emotions 
along with their labels denoting which emotion is depicted

## Data Collection
The above code makes another directory and stores all the images in distinct directories belonging to their emotions.

## Image Cropping
The above code detects the faces and crops the image such that the final image contains only the face. 
This decreases the noises in our data that we faced initially.

## Landmark Detection
The above code is used to mark some special points on a face and a mean point using dlib library and opencv. These are 68 Landmark points. 
Then we take angles from the mean points of each landmark points. Now we take these angles as the features for our training process.

## SVM
Accuracy = 83.88%

## Shallow Neural Network
Accuracy = 75.20%

## Logistic Regression
Accuracy = 89.25%
