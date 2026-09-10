Lab: Data Analysis with Pandas

Avengers action figures of Captain America, Iron Man, and Ant ManIn this lab, you will make use of everything we have learned about pandas: data cleaning, reshaping, and joining. In order to complete this lab, you’ll have to import, clean, combine, reshape, and visualize data to answer questions provided, as well as your own questions.

In particular, you will go through the process of:

Opening and inspecting the contents of CSVs using pandas dataframes
Identifying and handling missing values
Identifying and handling invalid values
Cleaning text data by removing whitespace and fixing typos
Joining multiple dataframes
Aggregating data by groups
Creating visualizations
Using visualizations and summary statistics to answer business questions.
Data Understanding
You will be working with a version of the comprehensive Superheroes Dataset, which can be found on Kaggle and was originally scraped from SuperHeroDb. We have modified the structure and contents of the dataset somewhat for the purposes of this lab. 

The data is contained in two separate CSV files:

heroes_information.csv: Each record represents a superhero, with attributes of that superhero (e.g., eye
color). Height is measured in centimeters, and weight is measured in pounds.
super_hero_powers.csv: Each record represents a superpower, then has True/False values representing
whether each superhero has that power.
Business Understanding
The business questions you have been provided are:

What is the distribution of superheroes by publisher?
What is the relationship between height and number of superpowers? And does this differ based on gender?
What are the five (5) most common superpowers in Marvel Comics vs. DC Comics?
This lab also simulates something you are likely to encounter at some point or another in your career in data science: someone has given you access to a dataset, as well as a few questions, and has told you to find something interesting.
