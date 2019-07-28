# Prediction Analysis on The Olist dataset

## Contents
* [Problem Statement](#problem-statement)
* [Need for a Solution](#need-for-a-solution)
* [Data Source](#data-source)
* [Data Description](#data-description)
* [Technologies Used](#technologies-used)

## Problem Statement
> Our problem is to find a way to estimate, based on data about the product and order, what will be the customer review score.

 ## Need for a Solution
 Olist is a player in the Brazilian e-commerce industry, which is a rapidly evolving field with unpredictable dynamics. Most companies in the E-commerce industry around the world are adapting a customer centric approach to boost their sales. Analysing customer data to check for any existing gap between customer expectation and the service provided by Olist and understanding the reason for the gap can spur Olist’s sales.
Feedback is the cornerstone of customer-centricity. Olist collects feedback from its customers in the form of a review score and a review message. Review score is based on a scale of one to five, with one representing lowest customer opinion of the service and five representing the highest customer opinion. Understanding current patterns in the review score and finding a way to predict customer review score, based on data about the product and order, can springboard Olist’s revenue.

## Data Source
This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants can sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.
After a customer purchases the product from Olist Store a seller gets notified to fulfil that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

## Data Description
This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allow viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. It also includes a geolocation dataset that relates Brazilian zip codes to latitude and longitude coordinates.
![](Olist.png)

## Technologies Used
R
> ggplot, dplyr, forcast, leaps, tidyverse, caret, corrplot, nnet, MASS, randomForest, lubridate, pROC, gains

SAP
> Lumira
