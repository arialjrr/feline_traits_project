# Cat Personality Traits Analysis 

## Overview
This project analyzes cat personality traits to understand feline behavior and identify suitable cat breeds for new owners. The analysis is based on a dataset of 4,300 cats across 56 breed groups, collected from owner self-reported questionnaires.

## Features
  Clustering analysis to categorize cat breeds
  Statistical analysis of cat traits
  Predictive modeling for shelter use and problematic behavior
  Identification of cat-friendly traits for inexperienced owners

## Data
The dataset includes:
  Basic cat information: age, breeds, sex, presence of other cats, problematic behavior
  7 personality and behavior trait scores:
    Fearfulness
    Activity/playfulness
    Aggression toward humans
    Sociability toward humans
    Sociability toward cats
    Excessive grooming
    Litterbox issues

## Methodology

1. Clustering Analysis
Used K-means clustering to categorize cat breeds into three groups:
Cluster 0: The Moderate Cats
Cluster 1: The Bold and Demanding
Cluster 2: The Easy-going Playmates

2. Statistical Analysis
Tested hypotheses using Pearson correlation and t-tests, including:
Relationship between fearfulness and activity/playfulness
Influence of living with other cats on personality and behavior

3. Predictive Modeling
Developed classifiers to predict:
Problematic behavior in cats
Suitability for inexperienced owners

## Key Findings
  Cluster 2 cats (Easy-going Playmates) are ideal for new owners
  Cats without other cats present tend to show slightly higher aggression towards humans and more playfulness
  Logistic regression and random forest models performed best in predicting problematic behavior and suitability for new owners, respectively

## Applications
  Improve matching process in animal shelters
  Enhance adoption success and reduce return rates
  Promote cat welfare

## Limitations and Future Directions
  Questionnaire length may affect data collection
  Time constraints limited hypothesis testing
  Breed grouping may oversimplify distinctions

## Future work includes:
  Enhancing the model for predicting cat suitability for new owners
  Developing a component to specify care requirements for each cat
  Expanding hypothesis testing

## Tools and Technologies Used
Python for data analysis and modeling
Machine learning algorithms: K-means, Logistic Regression, Random Forest, etc.
Statistical tests: Pearson correlation, t-tests


Project Link: https://github.com/arialjrr/feline_traits_project
