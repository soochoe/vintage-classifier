# Dress Code

1.  Classify a vintage dress by decade
2.  Find similar items on Etsy

## 1. Project Overview

  The initial objective of Dress Code was to see if style–specifically
  vintage–could be featurized using computer vision techniques, allowing for
  classifying vintage dresses by decade: 1950s, 1960s, 1970s, 1980s,
  or 1990s. This is the sort of classification someone knowledgeable of fashion
  might make while picking items ("popping tags") at a thrift shop. A pretrained
  Convolution Neural Network was employed to featurize the images collected
  from Etsy with classification of feature vectors by traditional models.

  The resulting model was successful in classification, obtaining a maximum
  of 87% accuracy in the binary case and 53% with all five classes. With the
  success of featurizing style with the CNN, a recommender was developed to
  that returns dresses that are similar in shape, pattern, and color–the
  visual features the model is capable of recognizing.  

  A web application was developed that allows users to:

  * Classify an image of a vintage dress by decade
  * See recommendation of similar dresses found on Etsy

  Check it out: http://52.202.180.199:8000/
                (soon: http://dress-code.tech)


## 2. Explanation

![alt text](https://github.com/mattybohan/vintage-classifier/blob/master/images/pipeline.jpg "Pipeline")

The

## 3. Code

#### Scrape

**Scrape.py** is a custom web scraper that extracts images, labels, and other relavent
information from Etsy shops.

#### Model


#### App


## 4. Installation

The following modules are required:

1. Lasagne
2. Nolearn
3. Nvidia CUDA
4. Sklearn
5. Numpy
6. Pandas
7. OpenCV
8. BeautifulSoup
