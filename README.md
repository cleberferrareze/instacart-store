# Instacart Store

## Overview
* Instacart is an online grocery store that operates through an app. 
* They can’t target everyone using the same sales strategy so they now want to target different customers with applicable marketing campaigns to see how will be the positive effect on the sales. 
* Instacart is most interested in the variety of customers in their database along with their purchasing behaviours. 

## Objective
* As a Data Analyst, I have been asked to uncover more information about the sales patterns, derive insights and suggest strategies for better segmentation based on the provided criteria.

## Dataset and Population Flow
* Started the project by exploring and cleaning the original data, then organised the datasets before merging everything to the final dataset. 
* These key steps of the process were:
 - Cleaning “products, orders, orders_products_combined and customers” data.
 - Wrangling “orders, customers, ords_prods_cust_PII” data.
 - Deriving new variables from “orders_products_merged, ords_prods_cust_PII, ords_prods_non_low_act_cust”.
 - Grouping data.
 - Merging dataframes.
 - Visualizing data in Python to identify insights.

Citation: “The Instacart Online Grocery Shopping Dataset 2017”, accessed from https://www.instacart.com/datasets/grocery-shopping-2017 on date."

**[Original Datasets](https://drive.google.com/drive/folders/1LXQGPnlueYXbzg0Ql8XQM-JANdoH2Cne?usp=sharing)**

## Python Skills
* Exploring
* Preparing
* Visualizing
* Click [here](https://drive.google.com/file/d/1nfFrlsGLkpVGfkTMFQSUUqVeByiLgfSR/view?usp=sharing) to access the **Python scripts (.ipynb)**.

## Challenges and Decisions

#### Grouping large datasets
* The challenge was to combine columns with different formats from distributed data storage into the same dataset. 
* To resolve that, I executed frequent data consistency checks before and after the data wrangling and grouping.

#### Grouping the right data for the right insights
* The challenge was to produce effective insights from an amount of data and a variety of data visualisations. 
* To resolve that, I focused on the key sales and marketing questions that could be more relevant for the Instacart initial objective.

#### Performance issue for Visualisations
* The challenge was to generate insights from data visualisations using Python charts, specifically “Line charts”.
* To resolve that, I defined a subset of data and split the data frame to reduce the size of the dataset. Jupiter Notebook slowed down when working with the entire dataset which had approximately that 7GB of size and more than 30 million records.

## Key Questions
* What are the busiest days of the week and hours of the day?
* Are there particular times of the day when people spend the most money?
* Is there a connection between age and family status in terms of ordering habits?
* What differences can you find in ordering habits of different customer profiles?
* Click [here](https://docs.google.com/spreadsheets/d/1ul9EdYDYwkDG_HcgzPkJ3dmVjrSqLbZIcQCgEIi70DE/edit?usp=sharing) to access the **"Key Questions Answered"**, process documentation, visualisations, and recommendations (.gsheet)

## Recommendations
* Offer profitable products to married customers between 30-49 years old with a salary range between 100000-150000. This segment of customers buy the most expensive products during the nights, from 0 and 5 am on Saturdays and Sundays.
