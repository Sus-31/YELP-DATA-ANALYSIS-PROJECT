# Yelp Data Analysis Project

This project analyzes the success of restaurant businesses based on user engagement and the sentiment of reviews on the Yelp platform. The dataset used for this analysis was downloaded from [Yelp Dataset](https://www.yelp.com/dataset).

## Table of Contents

- [Introduction](#introduction)
- [Project Steps](#project-steps)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to determine factors that contribute to the success of restaurant businesses by analyzing user reviews on Yelp. Success metrics include (review_count,tip_count, checkin_count etc) and sentiment (useful, funny, and cool) analysis.

## Project Steps

1. **Download the Dataset**: 
   - The Yelp dataset was downloaded from the provided link.

2. **Create a Database**:
   - A database was created to store and manage the dataset.

3. **Install Python Libraries**:
   - Installed necessary Python libraries:
     - `sqlite3` for database management
     - `pandas` for data manipulation and analysis
     - `folium` for geographical data visualization
     - `seaborn` and `matplotlib` for statistical data visualization

4. **Remove Outliers**:
   - Cleaned the data by removing outliers to ensure accuracy in analysis.

5. **Calculate Success Scores**:
   - Calculated success scores based on user engagement metrics such as the number of useful, funny, and cool reviews.

6. **Data Analysis Using SQL**:
   - Pulled all relevant data from the database using SQL for in-depth analysis.

7. **Create a Presentation**:
   - Compiled findings and insights into a presentation to showcase the results of the analysis.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Sus-31/Yelp-Data-Analysis.git
   cd Yelp-Data-Analysis


The analysis results will provide insights into how user engagement and review sentiment influence the success of restaurant businesses on Yelp. The final presentation will summarize these findings and offer actionable recommendations for business owners. Check the PDF for the findings.
