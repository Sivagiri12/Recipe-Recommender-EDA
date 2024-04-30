# Recipe-Recommender-EDA

Hello and welcome to the Recipe Recommendation assignment. 

 

If you visit any recipe websites, let’s say [food.com](https://www.food.com/recipe/chilaquiles-with-chicken-67921), for example, you will notice a section called “You’ll also love.” Under this section, the website recommends recipes related to the one you are looking at or based on your past rating patterns. 


The end objective of this entire assignment is to perform Exploratory Data Analysis and feature extraction from the raw data. 

For this case study, you will need to use Spark on Elastic Map Reduce service (EMR). 

We recommend that you use a master node with m4.xlarge and 1 cluster node with m4.large configuration. This cluster should give you sufficient processing power to work with this data. 

Note: Terminate your cluster when not in use.  

# Problem Statement

Step into the shoes of an ML engineer working at food.com. Your job is to design a recommender system to recommend recipes to users based on their choice and the current recipe they are looking at. 

 

The recommendation engine is a way to increase the website's user engagement. If a user is shown relevant recipes, they are more likely to spend more time on your site reading about recipes. Higher user engagement will likely result in more business opportunities like collaborations, promotions, etc.

 

The performance of a recommendation engine will significantly impact the revenue your recipe site can generate. 

 

Designing a recommender from scratch is a time-consuming task.  In this assignment, you are expected to explore the data and create features that will be used to build the recommender. 

 

Data you will be working with

You will be working with the two CSV files linked below. 

# raw recipe data
s3a://raw-recipes-clean-upgrad/RAW_recipes_cleaned.csv

# raw ratings data
s3a://raw-interactions-upgrad/RAW_interactions_cleaned.csv
 

 

Alternatively, you can download the files from the links below:

# raw recipe data
https://raw-recipes-clean-upgrad.s3.amazonaws.com/RAW_recipes_cleaned.csv

# raw ratings data
https://raw-interactions-upgrad.s3.amazonaws.com/RAW_interactions_cleaned.csv


Feature extraction at such a detailed level gets overwhelming, so you need to document your thoughts. In the video below, Prakhar introduces one version of a document you can use to organize the EDA and feature extraction.   


Google sheet link https://docs.google.com/spreadsheets/d/1hzMaCpofnOZqxRLJk6XgZ_j_mKIhldGEdQjp8y-aZx4/edit?usp=sharing

We are sharing some template notebooks to make it easier for you to perform the detailed EDA and feature extraction exercise. These templates are not mandatory. These notebooks have prewritten code and directions to help you. You can also build the feature on your own; as long as you get the same output and your data passes the assert checks, you are good.  


