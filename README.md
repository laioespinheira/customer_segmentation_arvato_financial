# Customer Segmentation Report for Arvato Financial Solutions

## Project Motivation

This was my chosen capstone project for the Udacity - Data Science Nanodegree. 
It's an end-to-end customer segmentation project that analyzes demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population.

## Project Description

The project is divided in two sections. 

- 1st Part: We will use unsupervised learning techniques to describe the relationship between the demographics of the company's existing customers and the general population of Germany.
- 2nd Part: Now that we've found which parts of the population are more likely to be customers of the mail-order company, we will build a prediction model. We want to be able to use the demographic information from each individual to decide whether or not it will be worth it to include that person in the campaign.

## Project Guidelines

This project is composed of the following steps:

1. Data cleaning

```data_cleaning.ipynb```: Preparation of the data provided.

2. Customer Segmentation Report

```customer_segmentation.ipynb```: Attribute analysis of established customers and the general population in order to create customers segments and be able to identify people of interest within the population.

3. Classification Model

```classification_model.ipynb```: The previous analysis will be used to predict what individuals will respond to the marketing campaing so that the company can focus on them instead of the entire population. I decided to use PyCaret library for this task!

## Data files

Our files used for this project can be found on the ```data``` folder.
On it we will find:

- ```clean_TRAIN.csv```,  ```clean_TEST.csv```, ```Udacity_MAILOUT_052018_TRAIN.csv``,  ```Udacity_MAILOUT_052018_TEST.csv```: Clean and prepped data exported at the end of the data_cleaning notebook.
- ```data/attributes_description/```: Description of attributes used on the datasets.
- ```data/predictions/```: contains ```pred.csv``` file which is the clean test dataset with predictions made by the model.

## Results

A ```medium``` post was made with details about the findings presented on this project. You can find it at [my medium post](https://medium.com/@laioespinheira/customer-segmentation-on-demographics-data-eab4ba140bac).

# Acknowledgements

[Arvato Financial Services](https://www.bertelsmann.com/divisions/arvato/) for providing the data.

[Udacity](https://www.udacity.com/) as this project was developed during the Data Science Nanodegree Program.


