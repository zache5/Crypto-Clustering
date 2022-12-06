# Crypto Clustering

The purpose of this project was to use the KMeans algorithm to sort a list of Cryptocurrencies into different clusters to try and create a different approach to measuring investment opportunities instead of solely basing it off of returns and volitlity.

## Technologies

In this code, I am using Pandas, Hvplot, Pathlib, sklearn.cluster, sklearn.decomposition, and sklearn.preprocessing.


## Installation Guide

import pandas as pd,
import hvplot.pandas,
from pathlib import Path,
from sklearn.cluster import KMeans,
from sklearn.decomposition import PCA,
from sklearn.preprocessing import StandardScaler

## Usage

I have created a few different scatter plots to demontrate the clusters that each of the cryptocurrencies belong to. Also, I have a few elbow charts within this code to identify the best number to use for k in order to get the most accurate results. Also, I am demonstrating the difference between having more features to use KMeans on, compared to using PCA in order to get a more accurate outcome.

## Contributors

I was the main contributor for this project!
