# b124-team10-jiehaoargelshuhaoAkaJHASH

# IMDB MetaScore Analysis
SC1015 Introduction to Data Science and Artificial Intelligence Mini-Project

# About
Mini-project for SC1015 - "Data Science and Artificial Intelligence" focusing on the detection of MetaScore in IMDB using DS concepts.

The dataset can be found here: https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows

# Contributors

@ ShuHao
@ JieHao   
@ Argel   

# Motivations and Problem Statement for Determining Meta Score

The determination of Meta score, which is a measure of critical acclaim for movies, is a significant task in the film industry. Several factors can potentially influence the Meta score of a movie, including IMDB rating, runtime, gross earnings, certificate (age rating), and the number of votes.

Understanding the relationship between these factors and Meta score can provide valuable insights to movie producers, studios, and other stakeholders in the film industry. For example:

IMDB Rating
Runtime
Gross Earnings
Certificate (Age Rating)
Number of Votes

The problem statement is to investigate and understand the relationships between these factors (IMDB rating, runtime, gross earnings, certificate, and number of votes) and the Meta score. This could involve performing exploratory data analysis, feature engineering, and applying machine learning techniques such as regression or classification to build a predictive model for determining Meta score based on these factors. The findings from this analysis could provide valuable insights to stakeholders in the film industry to make informed decisions related to movie production, marketing, and distribution strategies.

# Notebooks
1) b124_team10.ipynb



**Dependencies**

The code requires the following libraries:

numpy
pandas
matplotlib
seaborn
re
nltk
string
warnings
wordcloud
Make sure to install the required libraries before running the code.



**Dependencies**

The code requires the following libraries:
os
tensorflow
cv2
numpy
pandas
matplotlib

## Conclusion
- IMDB rating has the highest correlation with Meta score, with a positive Goodness of Fit (R-squared) and high classification accuracy for both train and test sets, indicating a positive correlation between IMDB rating and Meta score.
- Certificate (age rating) has a small correlation with Meta score, as there is a slight increase in Meta score for movies suitable for all ages compared to movies with more restrictive age ratings.
- Runtime, No. of votes, and Gross do not show any significant correlation with Meta score, as their Goodness of Fit is close to 0, indicating no clear positive or negative correlation.
- Other potential factors, such as Budget and Box Office, which were not included in the dataset, may also affect Meta score, as higher budget films may deliver more impressive visuals and effects, and box office success can indicate widespread appeal. Further exploration of these factors may be needed to better understand their impact on Meta score.

## Reflections/Learning Points
1. Acquired knowledge on the interconnectedness between jupyter notebook, VSCode and GitHub.
2. Learnt about the functionalities of the programs stated above. 
3. Soft skills - learnt how to present a DSAI project in a structured, articulate manner, training us for our professional capacities in the future. 
4. Performing Data Prep, Cleaning and EDA on a relatively large textual dataset.
6. An understanding of APIs and its documentation.

## Contributions
* JieHao   &#8594; Data Collection, Data Preparation, EDA, Supervised statistical analysis, Presentation slides and script
* Shu Hao  &#8594; Data Collection, Data Preparation, EDA, Supervised statistical analysis, Presentation slides and script
* Argel James   &#8594; Data Collection, Data Preparation, EDA, Supervised statistical analysis, Presentation slides and script
