# Name of Project

ML_CA06_KNN_Recommender


# Project Overview

At scale, this would look like recommending products on Amazon, articles on Medium, movies on Netflix, or videos on YouTube. Although, we can be certain they all use more efficient means of making recommendations due to the enormous volume of data they process. However, we could replicate one of these recommender systems on a smaller scale using what we have learned here in this article. Let us build the core of a movies recommender system.
• Number of attributes (Columns): 11
• Number of records (Rows): 30

# What question are we trying to answer?

Given a movies data set, what are the 5 most similar movies to a movie query?

# The project objective

Building a movie recommendation to help users find similar movies when they type in one movie's name. 


# Dataset

No need to download dataset, the code contain data url

1. Dataset: https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv

# Open colab:
https://colab.research.google.com/drive/1TYIF8ASxSAfBw4yp_cK0F63XlLKlaGnz?usp=sharing

# Import packages list below:

```bash
#Import packages
import pandas as pd
import numpy as np

#Import viz packages
import matplotlib.pyplot as plt

#Import KNN package
from sklearn.neighbors import KNeighborsClassifier

```


# Installation

- Mounted the google drive to make files readable: drive.mount('/content/drive/')
- Read the csv URL in Colab
- Run the code
- Get the result of 5 similar movies

# Contact info

Name: Mandy He
Email: she3@lion.lmu.edu

