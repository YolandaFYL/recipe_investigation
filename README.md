# Kid-Centric Recipe Analysis  

By Rita Yujia Wu (yuw172@ucsd.edu) & Yolanda Feng (yuf019@ucsd.edu)  

This is a data science project for the DSC 80 Final Project, The Data Science Lifecycle, focusing on exploring the features of recipes that make them kid-friendly.

---
## Introduction  

Good nutrition for kids is essential for their growth, development, and long-term health. A balanced diet ensures that children receive the necessary nutrients to strengthen their immune systems, support cognitive development, and build strong bones and muscles. Proper nutrition also helps prevent childhood obesity, which has tripled in the United States since the 1970s and is linked to serious health issues like type 2 diabetes and heart disease. Additionally, instilling healthy eating habits early on not only promotes immediate well-being but also helps establish routines and habits that contribute to their overall quality of life as they grow.

With this information in mind, our project aims to **investigate the features of recipes that make them kid-friendly**. By doing so, we hope to provide valuable insights for caregivers to better support children's nutritional needs for a healthier life. To achieve this, we are analyzing two datasets consisting of recipes and ratings posted since 2008 on food.com. These datasets were originally compiled for the recommender system research paper, "Generating Personalized Recipes from Historical User Preferences" by Majumder et al.

To facilitate the investigation of our question, we examined both datasets and chose some of the highly relevant columns. The *Recipe Dataset* contains recipes from food.com, an online recipe-sharing platform. This dataset has 83,782 rows and 10 columns. The *Interactions Dataset* contains reviews and ratings submitted for the recipes in the *Recipe Dataset*.

| Column      | Description                                                                                                           |
|-------------|-----------------------------------------------------------------------------------------------------------------------|
| `name`      | Recipe name                                                                                                           |
| `minutes`   | Minutes to prepare the recipe                                                                                        |
| `tags`      | Food.com tags for the recipe                                                                                          |
| `nutrition` | Nutrition information in the form [calories (#), total fat (PDV), sugar (PDV), sodium (PDV), protein (PDV), saturated fat (PDV), carbohydrates (PDV)]; PDV stands for "percentage of daily value" |
| `n_steps`   | Number of steps in the recipe                                                                                        |
| `recipe_id` | Recipe ID                                                                                                            |
| `rating`    | Rating given                                                                                                         |

---

## Data Cleaning and Exploratory Data Analysis
### Cleaned data
### Performed univariate analyses
### Performed bivariate analyses and aggregations
---
## Assessment of Missingness
### Addressed NMAR question
### Performed permutation tests for missingness
### Interpreted missingness test results
---
## Hypothesis Testing
### Selected relevant columns for a hypothesis or permutation test
### Explicitly stated a null hypothesis
### Explicitly stated an alternative hypothesis
### Performed a hypothesis or permutation test
### Used a valid test statistic
### Computed a p-value and made a decision
---
## Framing a Prediction Problem
---
## Baseline Model
---
## Final Model
---
## Fairness Analysis
---