# EENTITY RESOLUTION: USE OF LOCALITY SENSITIVE HASHING & MACHINE LEARNING BASED APPROACHES

### 1. Introduction
1.1 An entity is defined as unique person, event or object and may have been referred to in different ways in multiple data records. The task of ‘resolution’ refers to reducing or separating something into its constituents. Thus, Entity Resolution (ER) in its very basic definition refers to the task of identifying and linking/grouping various manifestations of the same Entity across and within datasets or data sources. For example, there could be different ways of addressing the same person in text, addresses for
businesses, or photos of a particular object. The goal of ER is to resolve entities, by identifying the records that represent the same entity and reconcile them to obtain one record per entity.

1.2 Despite the fact that the world is saturated in profound amounts of data, the unfortunate reality is that data was never designed to be used in conjunction with other datasets for informed decision making. As such, datasets containing different aspects of information about a particular Entity are often found across the storage landscape in different places, within different schemas, and without consistent join keys. Moreover, the problem that arises when we search for similar items of any kind in a large dataset is that there may be far too many pairs of items to test each pair for their degree of similarity. This is where ER is useful, to methodically integrate the large, dissimilar data source and provide a all-inclusive view on the entity of interest. (Huang, 2020).

### 2. Motivation for ER
2.1 The motivation for ER stems from its ability to unlock value from data through data integration. A complete data picture, created by integrating different pieces of data about the entity of interest, is much more effective at informing decision making than a partial or an incomplete view. For example, an investor can be much more effective at selecting the best investment if she had an integrated view of all the data on potential companies, starting from the quality of its team, to its traction in the market and the buzz surrounding it. (Huang, 2020)

### 3. Methods for ER
3.1. A large number of ER libraries exist both in python and R, however, Locality Sensitive Hashing technique forms the basis of almost all algorithms2 used for ER. Recently, Machine Learning techniques have been utilized for Entity Resolution or its close process of Named Entity Resolution (NER). Many new approaches including use of single layer perceptron, crowdsourcing etc. are also being developed to improve the efficiency and also to reduce the time of entity resolution.

### 4. Objective
4.1. The paper aims at studying ER as an application of LSH and implementation of a working program for ER in python utilization libraries incorporating LSH as well as shallow machine learning techniques. The paper has been structured as follows: -
a. Part I. Study of LSH and the methodology of carrying out ER using LSH.
b. Part II. Implementation of an ER program in python using LSH.
c. Part III. Implementation of ER program utilizing customized python libraries incorporating machine learning aspects.

### 5. Dataset
5.1 The dataset being used comprises of 270 rated computer science programming books. The dataset has been obtained from Kaggle and the link is: -
https://www.kaggle.com/thomaskonstantin/top-270-ratedcomputer-science-programing-books?select=prog_book.csv
