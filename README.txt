# Netflix Shows and Movies Data Cleaning and Exploration

This project involves cleaning, exploring, and visualizing a Netflix dataset containing information about shows and movies available on the platform. The goal is to handle missing values, explore categorical variables, and create meaningful visualizations to better understand the data.

# Project Outline
- Rename and load the dataset
- Handle missing values
- Perform basic data exploration
- Visualize distributions of categorical and numeric variables
- Cross-tabulate show types and ratings
- Analyze ratings and genre distributions

#Installation and Setup

Make sure you have the following Python packages installed:
pip install pandas numpy seaborn matplotlib missingno

and 
magik for R

Dataset:

The dataset originally comes from a CSV file named netflix_data.csv, which was renamed to: 
Netflix_shows_movies.csv

How to Run the code:
The notebook will:
-Rename and load the Netflix dataset.
-Fill missing values in text fields with 'Unknown'.
-Check and confirm the removal of missing data.
-Explore numeric and categorical variables.
-Save generated charts as .png files for further use

Key features
#Data cleaning:
- Handling missing data by filling with text missing with "Unknown"
- Checked for duplicate show_id entries

#Data Exploration
-Summarized numeric variables using .describe().
-Generated frequency plots for categorical variables.
-Created crosstab visualizations for type vs rating.

#Data Visualization
-Pie Charts:
--Distribution of rating categories.
--Distribution of genres (after exploding the listed_in column into multiple rows).
--A new exploded version of the dataset (exploded_items.csv) is saved for genre analysis.
--Integrate the image into R with the help of the magik library; I loaded the Rating distribution png chart

-Bar Charts:
 --Cross-tabulation of type by rating.

Saving Outputs
-Visualizations are saved as .png files.
-To ensure the image is succesfully integrated in R, the R script has to be in the same directory as the image

#Error Handling
-Handles errors when renaming files (e.g., file not found).

#License
This project is for fufilment of module 4 assignment

#Author
Gloria Eden Zion Ayesiga
Date: 4/28/2025


