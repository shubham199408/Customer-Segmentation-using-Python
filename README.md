# Customer-Segmentation-using-Python

Customer segmentation is an effective tool for businesses to closely align their strategy and tactics with, and better target, their customers. Customer segmentation is the process by which you divide your customers up based on common characteristics – such as demographics or interest, so businesses to understand their target audience.

Many unsupervised machine learning algorithms which can be used by companies to help them identify their user base and create consumer segments.

For this project we will be using K-means clustering which is an unsupervised learning technique. It uses machine learning algorithms to analyze and cluster unlabeled datasets.

In this project, we will be focussing on Exploraotry data analysis, data pre-processing for K-mean, building a k-means clustering algorithm, performance metrics to evaluate clustering models, visualizing clusters and interpretation of cluster built.

# Importing all the libraries required

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import matplotlib.cm as cm
from scipy.stats import norm
from plotly.subplots import make_subplots
from kneed import KneeLocator
from sklearn.datasets import make_blobs
from sklearn.cluster import KMeans
from sklearn.metrics import silhouette_score
from sklearn.preprocessing import StandardScaler
from sklearn.decomposition import PCA
from mpl_toolkits.mplot3d import Axes3D

#Loading the dataset

myData = pd.read_csv('Mall_Customers.csv')

