# YELP
# About Dataset
This dataset is a subset of Yelp's businesses, reviews, and user data. It was originally put together for the Yelp Dataset Challenge which is a chance for students to conduct research or analysis on Yelp's data and share their discoveries. In the most recent dataset you'll find information about businesses across 8 metropolitan areas in the USA and Canada.

# Creating a SQLite Database from the Yelp Dataset
In this notebook, we will demonstrate how to create a SQLite database from a JSON file containing the Yelp dataset. We will use Python libraries such as Pandas, SQLAlchemy, and SQLite3 to load, manipulate, and query the data. This process enables us to leverage SQL for efficient data analysis.

# Steps Overview
* Setup the Environment: Install and import the required libraries.
* Load the Yelp Dataset: Read the JSON file and convert it into a Pandas DataFrame.
* Create a SQLite Database: Establish a SQLite database connection using SQLAlchemy.
* Write Data to the Database: Save the DataFrame into the SQLite database.
*Query the Database: Execute SQL queries to analyze the data.

# 1. Setup the Environment
We will start by installing the necessary libraries. If you haven't already installed them, you can do so with the following command:


# 2. Load the Yelp Dataset
We will load the JSON file containing the Yelp dataset and normalize it into a DataFrame, which allows for easier manipulation of the data.

# 3. Create a SQLite Database
Using SQLAlchemy, we will create a SQLite database where we can store our DataFrame.

# 4. Write Data to the Database
We will write the DataFrame to the SQLite database as a table, enabling us to perform SQL queries on it.

# 5. Query the Database
Finally, we will execute various SQL queries to analyze the Yelp dataset, such as filtering businesses based on ratings and counting businesses by city.

# AGENDA
* Problem Statement

* Research Objectives

* Hypothesis

* Data Overview

* Analysis and Findings

* Recommendations

# ProblemStatement
In a competitive market like the restaurant industry, 
understanding the factors that influence business is crucial for 
stakeholders. Utilizing the Yelp dataset, this project aims to 
investigate the relationship between user engagement (reviews, 
tips, and check-ins) and business success metrics (review ,count, 
ratings) for restaurants

# Research Objectives
* Quantify the correlation between user engagement(reviews , tips, check-ins)and review count/average star 
rating: This will help us determine if restaurant with higher user engagement a corresponding increase in review 
and ratings.
* Analyze the impact of sentiment on review count and average star rating: We will investigate if positive 
sentiment in review and tips translates to higher star rating and potentially influences the total number of 
reviews left.
* Time trends in User Engagement We will explore if consistent user engagement over time is a stronger indicator 
of long-term success compared to sporadic bursts of activity

# Hypothesis Testing
* Higher levels of user engagement (more reviews, tips, and check-ins)correlate with higher review 
counts and ratings for restaurant.
* Positive sentiment expressed in reviews and tips contributes to higher overall rating counts for 
restaurants.
* Consistent engagement over time is positively associated with sustained business success for 
restaurants

# Data Overview
* This dataset is a subset of Yelp and has information about business across 8 metropolitan areas in the USA and 
Canada.
* The original data is shared by Yelp as JSON files.
* The five JSON files are business, review, user, tip and check-in.
* The JSON files are stored in the database for easy retrieval of data

  # Importing Libraries
* import pandas as pd
* import matplotlib.pyplot as plt
* import seaborn as sns
* from datetime import datetime
* import numpy as np 
* import mysql.connector
* import sqlite3
* import folium
* from geopy.geocoders import Nominatim
* from matplotlib.colors import LinearSegmentedColormap
* from IPython.display import display
* import warnings
* warnings.filterwarnings('ignore')
