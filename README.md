# Emotion recognition using Deep Learning

This project is implemented using deep-learning method of Convolutional Neural Networks (CNN), which integrates the step of handcrafted feature extraction with training of classifier. This system is able to achieve the relatively most optimal solution through the process of backpropagation.

## Install

This project requires Python 3.2 or higher version and following Python libraries:
*	Keras 1.1.2
*	Scikit Learn 0.18
*	Numpy 1.11.1
*	Pandas 0.18.1
*	Matplotlib 1.5.1
*	Seaborn 0.7.1
*	NLTK 3.2.4

## Datasets
The data set used to train the model is FER2013 which is an open-source data set that was made publicly available for a Kaggle competition. It contains 48 X 48-pixel grayscale images of the face. There are seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral) present in the data. 
The other dataset used for validation purpose is COCO dataset. The images from COCO are fetched, filtered, resized, converted to gray scale and then used for testing the model.
Coco dataset: https://cocodataset.org/#home

To run the iPython notebook, simply enter:
```
$ jupyter notebook ER_code.ipynb
```
