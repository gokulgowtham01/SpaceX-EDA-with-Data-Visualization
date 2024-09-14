# SpaceX-EDA-with-Data-Visualization

## Overview
This repository contains Python scripts for analyzing SpaceX launch data. The analysis includes visualizations of payload mass, flight numbers, and launch sites, as well as success rates by orbit and year.

## Dataset
The dataset is loaded from the following URL: SpaceX Launch Dataset Part 2

## Analysis Steps
Load Data: The dataset is loaded into a Pandas DataFrame from the CSV file.

## Visualizations:
Payload Mass vs. Flight Number: A plot showing payload mass by flight number, colored by success class.
Launch Site vs. Flight Number: A plot showing launch sites by flight number, colored by success class.
Payload Mass vs. Launch Site: A plot showing payload mass by launch site, colored by success class.
Success Rate by Orbit: A bar plot showing the average success rate for each orbit type.
Flight Number vs. Orbit: A plot showing flight numbers by orbit type, colored by success class.
Payload Mass vs. Orbit: A plot showing payload mass by orbit type, colored by success class.
Success Rate Over Time: A line plot showing success rates over the years.

## Feature Engineering:
Extracted the year from the 'Date' column.
Created one-hot encoded features for categorical variables such as 'Orbit', 'LaunchSite', 'LandingPad', and 'Serial'.
Saved the processed DataFrame with one-hot encoded features to a new CSV file.
Files
dataset_part_3.csv: Processed dataset with one-hot encoded features.

## Dependencies
pandas
numpy
matplotlib
seaborn
Ensure these libraries are installed to run the analysis.****
