# FemaleComicCharacters
## Problem Statement
This project was created to research the presence of female characters in Marvel and DC comics; through the use of data analysis.

## Instructions for Usage
Load the libraries as follows: pandas, matplotlib.pyplot, datetime, sklearn.tree (DecisionTreeClassifier), sklearn.model_selection (train_test_split), sklearn (metrics), sklearn (preprocessing), datetime, sklearn.model_selection (train_test_split)

## Discoveries from Analysis
Set subsets to group by the sex of a given character. The analysis testing gave insight into the imbalance between male and female characters in comic books. 
Each year there are a new characters introduction, I found there was a significant difference between the introductions of new female and male characters. I sorted the new data frames by the character's created year. The overall average of male character appearances was 17 while the average female appearances 20. I concluded that the average appearance for male characters was less than female characters because both comic producers have a ratio of three male characters to every one female character. This ratio causes the male character appearance average to be brought down because there are male characters that appear a handful of times. The appearance standard deviation of male characters was 105 while the appearance standard deviation of female characters was 82, as we can see from the standard deviations there was a larger spread between male character appearances and female character appearances.

### Decision Tree Model
In order to use categorical data columns for a decision tree analysis you have to asigned a numaric variable for each categorical characteristic. An example of how the characteristics and their numerical variables are read through the code: Align: 0 = Bad, 1 = Good, 2 = Neutral. The accuracy value is how well the decision tree model does when predicting a character's alliance given a set of characteristics (eye color, hair color, and ID). The model has a 51.4% accuracy. The module's accuracy may be improved by using a different set of characteristics.

### Introductions of new characters per year based on sex
The introduction of new characters per year based on sex. I had to first count the amount of male and female characters introduced each year then sort the data by year. After doing so I plotted the data so I could clearly see the difference between newly introduced male and female characters overtime. I will be using this new insight to develop a time series analysis to predict the number of new female characters introduced future on a yearly basis, using the observed values from FiveThirtyEight.

### Time Series Analysis
The data set was not well well suited for the time series analysis. Though the time series analysis was preformed there was no strong correlations between any of the variables.

### Regression Analysis
This data set did not have the neccessary data to complete a Regression Model.

#### Issues with the Data Set
There were issues with these data sets when it came to completeness. This lack of information may have been caused by the fact the data set is maintained by the fans of said Comic Book Producer.

<img src="images/Marvel Male vs. Female Character Introduction per Year.png">

<img src="images/DC Male vs. Female Character Introduction per Year.png">

## Decision Tree
<img src="images/Female_Comic_Characters_DecisionTree.png">
