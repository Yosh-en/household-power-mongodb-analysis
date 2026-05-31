# Household Power Consumption Analysis using MongoDB Time-Series Collections

## Overview

This project analyzes the Individual Household Electric Power Consumption dataset from the UCI Machine Learning Repository using Pandas and MongoDB.
The dataset contains more than 2 million minute-level measurements of household electricity consumption collected over approximately four years.

## Technologies Used
* Python
* Pandas
* MongoDB
* PyMongo
* Jupyter Notebook

## Tasks Performed

### Data Ingestion
* Imported the dataset into a Pandas DataFrame
* Created a timestamp field from Date and Time columns
* Replaced missing values and removed incomplete records
* Converted measurement columns to numeric data types
* Inserted cleaned data into a MongoDB Time-Series Collection

### MongoDB Queries
* Peak power consumption detection
* Time range query (specific day)
* Value-based filtering
* Aggregation pipeline for mean, minimum, and maximum power
* Monthly power consumption analysis for 2008

## Dataset Source
UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption
Yoshita Upadhyay

