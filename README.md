# Recipe Rating Analysis
### DSC80 Final Project – Fall 2025

Welcome to my project website! This site presents my full data science analysis on the Recipes & Ratings dataset from Food.com.

---

## Introduction
Online recipe platforms rely heavily on user ratings to determine which recipes
are promoted, recommended, or featured. However, recipes can vary widely in
their complexity, cooking time, nutritional content, and structure. This raises
an important question: what actually makes a recipe well-rated?

In this project, I analyze the Recipes and Ratings dataset from Food.com, which
contains tens of thousands of user-submitted recipes along with user ratings and
interaction data. By combining recipe metadata with aggregated user ratings, this
dataset provides a rich opportunity to study how recipe characteristics relate
to user preferences.

The central question of this project is:

What factors influence how highly a recipe is rated, and can we predict whether
a recipe will receive a high average rating (≥ 4)?

Understanding these patterns is valuable for multiple audiences. Home cooks may
gain insights into how to design clearer or more appealing recipes, while recipe
platforms can use such insights to improve recommendation systems and search
rankings. More broadly, this project demonstrates how data science can be used to
connect human preferences with structural features in real-world datasets.

## Cleaning and Exploratory Data Analysis
This histogram shows the distribution of the number of ingredients across recipes.
Most recipes use between 5 and 15 ingredients, indicating that extremely simple or
extremely complex recipes are relatively uncommon.
<iframe
  src="assets/n_ingredients_distribution.html"
  width="800"
  height="600"
  frameborder="0"
></iframe>
This scatter plot shows the relationship between the number of ingredients and average recipe rating.
Most recipes contain between 5 and 15 ingredients, and average ratings are generally high across all levels of recipe complexity.
However, there is no clear linear relationship between ingredient count and rating, as recipes with both few and many ingredients can receive high or low ratings.
This suggests that ingredient count alone does not strongly determine how a recipe is rated, motivating the use of additional features and predictive models in later steps.
<iframe
  src="assets/ingredients_vs_rating.html"
  width="800"
  height="600"
  frameborder="0"
></iframe>

## Assessment of Missingness
*(text + plot)*

## Hypothesis Testing
*(text + plot)*

## Framing a Prediction Problem
*(text)*

## Baseline Model
*(text)*

## Final Model
*(text)*

## Fairness Analysis
*(text + plot)*

---
