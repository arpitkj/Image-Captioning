# Image-Captioning
&nbsp;

![image caption model representation](https://iq.opengenus.org/content/images/2020/06/CNN-RNN-1.jpeg)

&nbsp;
## Overview
Generating a description of an image is called image captioning. Image captioning requires recognizing the important objects, their attributes and their relationships in an image. It also needs to generate syntactically and semantically correct sentences. We have built a deep learning model that uses NLTK for text processing, CNN for image processing, and generates novel captions for images using LSTM.

## Motivation
Image captioning is important for many reasons. For example, they can be used for automatic image indexing. Image indexing is important for Content-Based Image Retrieval (CBIR) and therefore, it can be applied to many areas, including biomedicine, commerce, the military, education, digital libraries, and web searching. Social media platforms such as Facebook and Twitter can directly generate descriptions from images.

## Dataset
In this project, we are using the __Flickr 8k__ dataset. This dataset has 8,092 images with image id and a particular id has multiple captions generated.

![sample image from dataset](https://www.researchgate.net/publication/323779361/figure/fig4/AS:941729574297654@1601537235438/Examples-of-image-description-pairs-of-the-three-benchmark-datasets-From-the-top-to-the.gif)

&nbsp;
## Technical Aspect
This project is divided into three parts:

* First part is text processing where we convert the captions file of dataset into usable form.
* Second part is image processing where we extract features from training set.
* Last part is generating captions using extracted features from images.   

## Tech Stack

* Tensorflow
* Keras
* Pandas
* NumPy
* nltk ( Natural language toolkit)
* Jupyter

