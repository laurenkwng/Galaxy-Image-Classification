# Galaxy Image Classification Through Computer Vision

The purpose of the project was to utilize computer vision techniques such as Inception V3 and Convolutional Neural Networks
(CNN) for transfer learning to obtain a highly accurate model that could predict the classifications of galaxy images. Following data
preprocessing, exploratory data analysis and feature extraction, the model achieved proved to be successful with accuracy rates
ranging from the high 80th to low 90th percentiles on tested images.

The dataset is sourced from NASA’s Sloan Digital Sky Survey and GalaxyZoo. The Sloan data consists of 61,578 images of galaxies and are sized 400 by 400 pixels. The GalaxyZoo data is a csv file of
classifications of each Sloan image based on the responses of tens of thousands of GalaxyZoo users. Users answered questions on the shape of each galaxy and then answered questions depending on the
responses to previous questions.

## CNN Transfer Learning Validation Accuracy
<img width="783" alt="Screen Shot 2019-07-07 at 5 52 42 PM" src="https://user-images.githubusercontent.com/30671201/60776313-25defd00-a0e0-11e9-8249-54ed9f52d050.png">


### Built With
* PySpark
* Python

### Methodology
* Variable and Image Transformation
* Exploratory Data Analysis
* CNN Transfer Learning
* Decision Tree Classification
* K-Nearest Neighbors Algorithm

### Conclusions
Based on previous results, the 2-Class CNN model is the champion model of our data, which has
approximately 90 percent high accuracy. The 4-Class CNN model performs high accuracy on training
dataset and low accuracy on testing dataset. Neither could we decide if regression models can be used
to classify images of spiral, edge, smooth, and otherly shaped galaxies nor could we employ the
champion model to determine the tightness of the arms of a spiral galaxy. Those questions require
further research.

Our future research will be done to construct an accurate, four-class model. This can be done by not
converting the images to grayscale and instead using Principal Component Analysis as an alternative
method of reducing file size. Should this not improve the situation, a Logit or Naive-Bayes model can
be generated and compared for relative accuracy. If any of these models prove viable, the final step is to
re-train the model on the full set of images.

### Contributors
* Lauren Wong
* Addison Luria-Robertson
* Chuqiao Liu
