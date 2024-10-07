# Recipe-Visualization-Application
![image](https://github.com/user-attachments/assets/2261fb8d-03a8-48e5-8b40-407e3d1add06)

## Overview
This project aims to analyze a recipe dataset to derive valuable insights that can enhance user engagement and satisfaction on a recipe platform. By examining ingredient usage, recipe ratings, and nutritional content, we provide actionable recommendations for improving the platform's offerings.
## Table of Contents
### 1. Project Objectives
### 2. Data Overview
### 3. Data Cleaning Process
### 4. Insights
### 5. Suggestions and Solutions
### 6. Conclusion
## Project Objectives
The primary objective of this project is to analyze recipe data to identify trends, popular ingredients, and correlations between nutritional values. This analysis is aimed at guiding strategic decisions to improve user engagement on the recipe platform.

## Data Overview
The dataset includes various features, such as:
* Title : Name of the recipe
* Date : Date of recipe added
* Ingredients: List of ingredients used in recipes.
* Categories: Classification of recipes.
* Directions: steps required to make a dish.
* Nutritional Information: Includes calories, fat, protein, sodium, and ratings.
 ## Data Cleaning Process
### The data cleaning process involved the following steps:

* **Handling Missing Values:** Imputed missing values for key nutritional columns (calories, fat, protein, sodium).


* **Ingredient Cleaning:** Removed unnecessary descriptors from the ingredients list while preserving essential delimiters (commas).

* **Exploding Categories:** Exploded the categories to analyze the frequency of each category effectively.

* **Outlier Detection:** Identified and handled outliers using IQR capping for columns such as calories, fat, and sodium.

* **Data Type Conversion:** Ensured that the date format was consistent, and numerical columns were properly formatted for analysis.

## Challenges Faced

* **Unwanted Descriptors:** Removing common culinary descriptors while preserving important ingredient information proved challenging.


* **Handling Duplicates:** Ensuring unique entries in categories required careful management to prevent analysis errors.
  
## Assumptions Made

* **Categorical Data Integrity:** Assumed that categories were consistent and accurately represented the recipes.
  
* **User Engagement:** Assumed that highlighted ingredients and categories would resonate with the target audience based on their ratings.
  
## Insights:

* **Ingredient Popularity:** Sugar, salt, olive oil, and water are the most common ingredients in highly-rated recipes.
  
* **Category Distribution:** The "Bon Appetit" category has the highest distribution at 23.6%, followed by "Peanut Free" at 21.1%.
  
* **Nutritional Analysis:** Top recipe categories are characterized by high sodium and calorie content, with low protein and fat levels.

* **Skewness:** Most nutritional columns exhibit positive skewness, while ratings are negatively skewed.

* **Correlations:** A positive correlation exists between sodium and calories, while fat and calories are also highly correlated.

## Suggestions and Solutions

* **Promote Popular Ingredients:** Highlight recipes featuring top ingredients to boost user engagement.
  
* **Capitalize on Top Recipe Categories:** Feature popular categories prominently to drive traffic.
  
* **Offer Healthier Recipe Options:** Create and tag low-sodium, low-calorie recipes to attract health-conscious users.
  
* **Introduce Ingredient Substitution Tool:** Allow users to swap ingredients for healthier alternatives.
  
* **Focus on Nutritional Optimization:** Optimize recipes to balance nutritional content and enhance overall health benefits.

## Conclusion:
The insights derived from this project can significantly impact the recipe platform's approach to content delivery, allowing for a more engaging and health-focused user experience. By implementing the suggested solutions, the platform can attract a broader audience and enhance user satisfaction.
