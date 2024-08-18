# Unsupervised Tools: An Insight into Twitch Streamers

**Author:** María Ángeles Magro Garrote  
**Year:** 2022

## Overview

This project aims to analyze a dataset of the top 1000 Twitch streamers from 2020 to answer key questions about what factors contribute to a streamer's success on the platform. Although Twitch is primarily known for its gaming content, it features a variety of categories such as "Just Chatting" and sports, attracting 31 million daily viewers. The top streamers earn substantial revenue through ads, subscriptions, and donations.

## Key Questions

1. How does the language of the stream impact viewership and partnership status?
2. Does having a peak viewership affect a channel's metrics?
3. Is there a correlation between the number of viewers and the number of followers?
4. What factors are indicative of a successful streamer?

## Dataset

The dataset used in this project was created by Aayush Mishra and contains data from 2020. You can access it [here](https://www.kaggle.com/datasets/aayushmishra1512/twitchdata).

## Required R Libraries

To run the analysis, ensure you have the following R libraries installed:

- `VIM`
- `mice`
- `tidyverse`
- `gridExtra`
- `GGally`
- `factoextra`
- `lubridate`
- `quantmod`
- `mclust`
- `cluster`
- `kernlab`

### Installation

You can install the required packages using the following commands in R:

```r
install.packages(c("VIM", "mice", "tidyverse", "gridExtra", "GGally", "factoextra", "lubridate", "quantmod", "mclust", "cluster", "kernlab"))
```

## Running the Analysis

### PART 1: Data Preprocessing

- Load the data and perform initial preprocessing.
- Tasks include renaming variables, checking for missing values, duplicates, outliers, scaling, and transforming boolean variables.

### PART 2: Exploratory Data Analysis (EDA)

- Perform exploratory analysis to understand the data better.
- Includes correlation analysis and visualization of various metrics.
- General conclusions are obtained and tested later.

### PART 3: Principal Component Analysis (PCA)

- Conduct PCA to reduce dimensionality and identify key components.

### PART 4: Factor Analysis

- Perform factor analysis to uncover underlying factors influencing the data.

### PART 5: Clustering

- Apply clustering methods (k-means, hierarchical, PAM) to uncover patterns and insights.

## Final Insights

The conclusions of this analysis can be seen in the notebook (Rmd) or HTML.
