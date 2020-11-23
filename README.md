# Customer Segmentation Analysis Portfolio
Customer Segmentation Analysis project

## Table of contents
* Introduction
* Technologies
* Goal
* Dataset
* Correlation between Variables
* Standardization Data
* Model Used
* Model Results

## Introduction
A customer’s segmentations model allows for the effective allocation of marketing resources and the maximization of cross and up-selling opportunities. The ability to dynamically segment audience or customers was the top tactic for marketers when it comes to improving consumers experience.

## Technologies
Python

## Goal
Specifically, customer segmentation helps company: identify ways to improve products or new products or services opportunities. It is your key to better understanding your audience or customers. The Main goal of this project is to find customer segments based on all these information get from our data.

## DataSet
The dataset consists of information about the purchasing behavior of 2,000 individuals from a given area when entering a physical ‘FMCG’ store. All data has been collected through the loyalty cards they use at checkout. The data has been preprocessed and there are no missing values. 

![data_pict](https://user-images.githubusercontent.com/32566240/99598819-75367c80-29fa-11eb-8f79-e523d93a7ebe.png)
						
## Correlation between Variables
![correlation](https://user-images.githubusercontent.com/32566240/99599371-86cc5400-29fb-11eb-98c9-5fab1f628ac8.png)

From this heatmap we see that Age and Education, Income and Occupation has strong positive correlation where Age and Marital status has negative correlation.

## Standardization Data
In this section, we standardize our data, so that all features have equal weight. This is important for modelling. Otherwise , innour case Income would be considered much more important than Education for instance.We do not know if this the case ,so we would not like to introduce it to our model.This is what is also refered to as bias.

## Model Used
In our project, we have used 3 Model for implementation which is 
                  1. Hierarchical Clustering
		  2. K-means Clustering
		  3. PCA-Principale Component Analysis
## Model Results
* Hierarchical Clustering

![Hierarchical](https://user-images.githubusercontent.com/32566240/99999821-032ab280-2dc1-11eb-8b57-0838d14e5aab.png)

* K-means Clustering

![K-means](https://user-images.githubusercontent.com/32566240/100001770-e93e9f00-2dc3-11eb-8b0b-8b8971563638.png)

* PCA-Principale Component Analysis
