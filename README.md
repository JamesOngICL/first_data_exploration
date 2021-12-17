# first_data_exploration
A fast 2-day project for ICDSS data brawl.https://imperialdatasoc.co.uk/data-brawl-2021-2022/?mc_cid=171d9e0468&mc_eid=e11ca7c91c

## Inspiration
I always wanted to observe the effects between academic attainment and studiousness to better understand how I could apply certain techniques to optimize my studies. I decided to also evaluate other socioeconomic factors such as parental education for the construction of this model. This was done out of curiosity and also an attempt to understand the effect of inequality on someone's academic attainment.
## What it does
This model runs a multivariate linear regression to examine the data and gain a deeper understanding of the factors involved and how they affect academic performance. 
The thesis question was:

### To what extent do socioeconomic and behavioural factors have on overall mathematics grades and how effective is linear regression at modelling a students performance in portugese maths examinations? 

## How we built it
I used approximately 90% of the data for training the model and the remaining 10% was used to test how effective the model was at making predictions (90-10 train test split). This was done by taking the first 350 rows of the math data and storing them into a new CSV file. I made this decision because the maths data set is rather small with around 400 rows and hence I thought that more data should be used in order to perform an accurate linear regression. 

I analysed a total of 8 columns to determine the effect of several given variables on performance in final exams. 
### This Included:
1. Study Time

2. Absences 

3. Father education level

4. Mother education level

5. Time spent socialising

6. Time taken to commute to school

7. Workday alcohol consumption

8. Weekend alcohol consumption

## Challenges we ran into
Time constraints of the project, needed to complete the project quickly enough. Additionally, getting familiarity with the dataset was essential to factor in which columns could and could not have been used for the linear regression model. 
 
## Accomplishments that we're proud of
Built a basic linear prediction model for determining what variables can influence academic attainment.  I also enjoyed being able to implement ML theory such as train test split (albeit done in a quite simplified manner). 

## What we learned
I learnt how to download data from a kaggle set and how I can effectively test my models and apply data-science theory. I also really enjoyed having my first project opportunity to let me learn how to graph in python as well as the multivariate analysis tools that could be used. 

## What's next for Exploratory Data Analysis
In order to obtain a more accurate prediction model machine learning algorithms should be used instead of linear regression as they can have more complicated activation functions and can also apply complex features such as dropout and weight decay. I wish to explore this in future if I get the opportunity. 
