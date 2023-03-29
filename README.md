# Rockbuster Stealth Data Analysis Project
Analysis of the Rockbuster Stealth LLC Data using SQL


## Overview
Rockbuster Stealth LLC is a movie rental company that used to have stores around the world. Facing stiff competition from streaming services such as Netflix and Amazon Prime, the Rockbuster Stealth management team is planning to use its existing movie licenses to launch an online video rental service to stay competitive.
As a data analyst at Rockbuster Stealth’s business intelligence (BI) department, my job is to help with the launch strategy for the new online video service. The BI department helps other departments, from inventory to customer insights, with data-related queries. 

## Data
The Rockbuster Stealth LLC data includes information about customers, rentals, movies etc. The data is stored in the following tables:

**customer**: Contains information about customers such as name, address, and email.  
**rental**: Contains information about rentals such as rental date, return date, staff id.  
**film**: Contains information about movies such as title, release year, and genre.  
**payment**: Contains information about rental payments such as amount, customer id, staff id, payment date etc.  
**store**: Contains information about the store such as manager id, store address id etc.  
**film_actor**: Contains information about the actor who acted in a particular film such as film id, actor id etc.  
**inventory**: Contains information about the movie inventory such as film and store id.  
**film_category**: Contains information about the category the film belongs to.  
**staff**: Contains information about store staff such as name, email id, address etc.  
**actor**: Contains information about an actor such as name and id which link to the film_actor table.  
**category**: Contains information about all the film categories such as id and name.  
**address**: Contains information about the addresses such as district, city id, postal code etc.  
**city**: Contains information about the cities such as name and id which link to the address table.  
**country**: Contains information about the countries such as name and id which link to the address table.  
**language**: Contains information about the languages and links to the film table.  

## Methodology
The analysis was performed using SQL queries. The queries were executed using the PostgreSQL database management system. The analysis includes the following steps:

_**Data exploration**_: The data was explored to understand its structure and identify any issues such as missing values or duplicates.  
_**Data cleaning**_: The data was cleaned to remove duplicates and missing values.  
_**Data analysis**_: The data was analyzed using SQL queries to extract insights about customer behavior, movie popularity, and rental trends. 
_**Data visualization**_: The data was visualized using Tableau to draw patterns and identify trends over the years.  

## Key Questions and Objectives
The Rockbuster Stealth Management Board has asked a series of business questions and they expect data-driven answers that they can use for their 2020 company strategy.
Here are the main questions they’d like to answer:

● Which movies contributed the most/least to revenue gain?  
● What was the average rental duration for all videos?  
● Which countries are Rockbuster customers based in?  
● Where are customers with a high lifetime value based?  
● Do sales figures vary between geographic regions?  

## Tableau Visualizations Link
https://public.tableau.com/app/profile/snigdha.sharma1523/viz/Task3_10FinalProject

## Results
The analysis revealed several insights about customer behavior, movie popularity, and rental trends:

- India, China and the USA contain almost 25% of all Rockbuster customers and have together generated 25% of the total revenue.  
- Sports, Sci-fi and Animation genre films have been rented the maximum.  
- PG and PG-13 rated films are most popular rentals.  
- English language films such as Telegraph Voyage, Zorro Arcand Wife Turn are most rented.  


Based on these insights, several recommendations were made to improve business operations:

- India, China and the USA should be the market of focus as Rockbuster’s customer base is already strong in these countries.  
- The database should have more copies of Sports, Sci-fi and Animation films in English language as  they are popular and generate maximum revenue.  
- Since PG and PG-13 films are generating large revenue the inventory should have movies that are rated such.  
- To promote loyalty among users a credit point-based system should be developed, and the top 5 customers can get 100 extra points at the launch of the application.  
- The marketing team should track the customer lifetime and send them relevant emails suggesting movies that match their profile, to increase engagement.  

## Files
**Analysis and Result**: Contains the Final Presentation with results of the analysis.  
**Data**: Contains the dvdrental.zip file to load the data into local database.  
**Project Overview**: Contains the Business Requirement Document.  
**Scripts**: Contains *.sql files with queries of the analysis.  
README.md: This file.  

## Installation
To run the analysis, you will need to install PostgreSQL database management system and import the dvdrental.zip data into the database. You will also need to run the queries in the *.sql files.
