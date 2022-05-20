# Wrangling, analyzing, and visualizing a tweet archive from Twitter

## Overview

Wrangling WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage. Using the data set, we will answer the following questions:
- Which are the ten most popular dog names?
- Which dog stage is most frequent in our dataset according to number of dogs it has?
- Which dog stage has the highest average rating?
- Are high rated dogs more likely to be favorited than low rated ones?


## Tools

- Python (numpy, pandas, matplotlib, seaborn, requests, BeautifulSoup, tweepy, json, sqlalchemy)

## Findings

- **Which are the ten most popular dog names?**: Lucy and Charlie are the two most popular names for female and male dogs, respectively. Followed by Cooper, Oliver, and Tucker. And at number 10 we have Toby.
- **Which dog stage is most frequent in our dataset according to number of dogs it has?**: The dog stage with the most dogs is pupper followed by doggo, floof, puppo, and at the end comes blep with only 3 dogs.
- **Which dog stage has the highest average rating?**: Keeping in mind the varying number of dogs in each stage, and that the number of dogs in blep stage are so few that they cannot be representative(only 3 dogs), the stage with the highest average rating is the puppo stage which has an average rating of 12.166667 for 30 dogs, followed by the doggo stage with an average rating of 11.717391 for 92 dogs.
- **Are high rated dogs more likely to be favorited than low rated ones?**: There is a positive relationship between dog ratings and favorite counts .The higher the dog rating the more likely it is to get favorited.


