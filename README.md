# Image-Captioning


## Overview
Generating a description of an image is called image captioning. Image captioning requires recognizing the important objects, their attributes and their relationships in an image. It also needs to generate syntactically and semantically correct sentences. We have built a deep learning model that uses NLTK for text processing, CNN for image processing, and generates novel captions for images using LSTM.

## Motivation
Image captioning is important for many reasons. For example, they can be used for automatic image indexing. Image indexing is important for Content-Based Image Retrieval (CBIR) and therefore, it can be applied to many areas, including biomedicine, commerce, the military, education, digital libraries, and web searching. Social media platforms such as Facebook and Twitter can directly generate descriptions from images.

## Dataset
In this project, we are using the Flickr 8k dataset. This dataset has 8,092 images with image id and a particular id has multiple captions generated.

## Technical Aspect
This project is divided into three parts:

* First part is text processing where we convert the captions file of dataset into usable form.
* Second part is image processing where we extract features from training set.
* Last part is generating captions using extracted features from images.   

## Tech Stack
