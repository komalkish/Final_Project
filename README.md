# Final_Project

# Overview
Life expectancy is a key metric for understanding a country’s health. A number of economic, social, and health related variables can help predict life-expectancy. Historically, global life expectancy has risen. However, this varies by country. By examining various factors to determine the life expectancy, we can then use this data to influence solutions such as health, policy, foreign aid, and global living standards.

The project relies on accuracy of data. The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The data-sets are made available to public for the purpose of health data analysis. The data-set related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website. Among all categories of health-related factors only those critical factors were chosen which are more representative. It has been observed that in the past 15 years , there has been a huge development in health sector resulting in improvement of human mortality rates especially in the developing nations in comparison to the past 30 years. Therefore, in this project we have considered data from year 2000-2015 for 193 countries for further analysis

# Purpose
Analysis of life expectancy from a Kaggle data set. To predict what factors (such as disease, BMI, population, income, education, etc.) have the most influence on life expectancy categorized by country.

## The data-set aims to answer the following questions
### Hypothesis: 
	whether Developing countries will have lower life expectancy than developed countries? 
	Does Life Expectancy has positive or negative correlation due to a pre existing medical condition?
	Does Life Expectancy has positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc?
	Do densely populated countries tend to have lower life expectancy?
	
# Analysis 

## Machine Learning Model - 
We started with understanding Life Expectancy and learned the factors affecting it. We further visualized the affecting parameters and correlated them to derive inferences. Finally, we covered the Linear Regression and implemented it to predict Life expectancy.
One can extend their life span by adopting a healthy lifestyle, proper education, and getting vaccinated. Of course, Demographic location plays an important role. In our analysis, we found that people living in Europe have a higher lifespan than other continents. A country’s GDP and Income composition affect Life Expectancy more broadly.
Some parameters like pollution and environmental index have been missing in this analysis and are expected to be highly related to Life Expectancy.

## Database
First dataset - The first dataset contains 2938 rows and 22 columns
![image](https://user-images.githubusercontent.com/92557075/160436912-f6136c68-1dd4-4085-8887-5d8ee6043a50.png)

Second Dataset - The second dataset contains 1927 rows and 3 columns

Merging of Data - We combined two datasets and created a new column “Suicides. 
![image](https://user-images.githubusercontent.com/92557075/160437161-b1bae391-6b6b-4f03-8968-2c892bd1758e.png)
 
 Data cleanup - During our analysis, we noticed the dataset contain null vales. We have used interpolation to replace null values. 
 ![image](https://user-images.githubusercontent.com/92557075/160437501-94429159-410e-4a33-b28d-fa70f0fd1635.png)




Google Slides
https://docs.google.com/presentation/d/18z6GKDGj8QTBJSq0e9ELsOZXU9wTaID3-6Ij4ZBrpEg/edit#slide=id.p1
	

        
