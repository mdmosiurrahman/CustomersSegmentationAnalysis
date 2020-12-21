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

We plot the results from hierarchical clustering using Dendrogram. We truncate the dendrogram for better readability.
It visualize 4 clustering of customers purchasing behaviour data which represnt 4 color in the x-axis. 

* K-means Clustering

![K-means](https://user-images.githubusercontent.com/32566240/100001770-e93e9f00-2dc3-11eb-8b0b-8b8971563638.png)

In our K-means clustering, we got total 4 segment of customers purchasing behaviour which indicate Segment 0 to segment 3. we add the segment labels to our table as 0:'well-off' , 1:'fewer oppertunities' , 2:'standard' and 3:'career focused.

Segment 0: It is composed man and women almost equally which average age is 56 and more than two-third of customers are in relationship, and they have the highest level of education as well as high income.

Segment 1: Two-third of the customers are male and almost all are single. Their education and income are low compare to other segments.

Segment 2: Most of the customers are young (average age 28 years) in this segment.

Segment 3: Most of the customers has good income, and they are from mid/big cities.

* PCA-Principale Component Analysis

![PCA](https://user-images.githubusercontent.com/32566240/100001939-299e1d00-2dc4-11eb-8ea5-0c91fba06dff.png)
 
 In our project we have used 3 model but Principale component analysis produced best result comapre to other two model. In PCA data is distance is very close to one data point another data point. We can describe our each cluster below:
 
 Well-off: It is composed man and women almost equally which average age is 56 and more than two-third of customers are in relationship, and they have the highest level of education as well as high income.

Standard: Two-third of the customers are male and almost all are single. Their education and income are low compare to other segments.

Fewer opportunities: Most of the customers are young (average age 28 years) in this segment.

Career focused: Most of the customers has good income, occupation, and they are from mid/big cities
