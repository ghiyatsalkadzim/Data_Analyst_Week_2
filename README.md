# Data_Analytic_Week_2
# Types of Data analysis
## 1) Descriptive analysis
Descriptive analysis is a form of data examination that assists in the portrayal, illustration, or informative consolidation of data points, enabling the emergence of patterns that fulfill all the criteria of the dataset.

## 2) Diagnostic analysis
Diagnostic analytics examines data to understand the root causes of events, behaviors, and outcomes. Data analysts use diverse techniques and tools to identify patterns, trends, and connections to explain why happened.

## 3) Predictive analysis
Predictive analytics seeks to anticipate future events by examining historical data, employing statistical modeling, machine learning, and artificial intelligence to project potential outcomes.

## 4) Prescriptive analysis
Prescriptive analytics delves beyond predictive analytics, examining the correlation between specific variables and their influence on the ultimate result. Its emphasis lies in determining the actions necessary to achieve desired outcomes.

### Example
dataset: 

![Screenshot (864)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/134476980/f111d3d8-59cd-4ee7-aa5d-327003f6e309)

uses df.describe() to display data such as mean, median, mode, max, min.

![Screenshot (862)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/134476980/d0c3f75c-4272-4446-a129-03762eba28cf)

COVID-19 is an infectious disease caused by a newly discovered strain of coronavirus. This new virus and the disease it causes were unknown before the start of the outbreak in Wuhan, China, in December 2019. COVID-19 has become a pandemic in many countries around the world. In the analysis of COVID-19 data from several selected countries, there are approximately 50 million total covid cases in the world. The average total deaths were 31 thousand, where the lowest number of deaths was 21 out of a total of 62 thousand cases in Bhutan. On the other hand, India stands out with the highest number of deaths, reaching a total of 532 thousand deaths from . Although India has the largest population among the selected countries, the high testing effort with 930 million tests shows commitment in handling the pandemic. However, the complexity of handling the pandemic in India is compounded by the large scale of the population. This highlights the importance of an adaptive and effective coping strategy in the face of the COVID-19 pandemic.
    India's high testing and population suggest continued COVID-19 challenges. Without effective containment and vaccination, cases and deaths may rise. Other countries with successful vaccination efforts may see declines, but new variants could alter outcomes globally.

## T-Tests
T-tests are a family of statistical procedures used to compare the means of two groups. They are a fundamental tool in inferential statistics, allowing to assess whether the observed difference between two groups is likely due to random chance or reflects a true underlying difference in the population.

There are different types of t-tests depending on the characteristics of your data and the research question:
1.	Independent Samples T-test: Used to compare the means of two independent groups.


2.	Paired Samples T-test: Used to compare the means of two groups where the same subjects are involved.


3.	One-Sample T-test: Used to compare the mean of a single sample to a hypothesized value.

Example (Paired Sample T-Test) :

## Machine Learning Regression
Regression is a statistical method used to understand and model the relationship between one or more independent variables and a dependent variable. The main purpose of regression analysis is to understand the extent to which the independent variables contribute to the variation in the dependent variable, as well as to predict the value of the dependent variable based on the values of the independent variables.
- There must be historical data
- The historical data must be patterned
- Complex algorithm

### Preprocessing Model
An important stage in the development of a good model. It involves a series of steps to clean, transform and prepare the data to make it suitable for use in regression models.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/454a9509-09ab-4603-bec8-32fb378e3153)

#### Splitting Training and Test Set
This allows us to evaluate the model's performance on never-before-seen data, which helps ensure that the model not only learns the patterns in the training data but is also able to generalize well to new data.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/a2445626-400d-4fe5-9dda-3ec49c909716)

#### Filling Into Training
The process of filling in (imputing) missing values in the training dataset before training the regression model. This is important because most machine learning algorithms cannot handle missing values, so special handling of incomplete data is necessary.
![image](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_2/assets/165861920/8d88c937-8f55-4c92-b656-686195ec1968)





