# Runners
This project was created for Data Science course. 

### Introduction 
The 100 metres, or 100-metre dash, is a sprint race in track and field competitions. 
The shortest common outdoor running distance, it is one of the most popular and prestigious events in the sport of athletics. 
In our project collected more the 1000 runners seniors and young, Analzyed their data in order to understand if we can predict this. 

#### Can we predict if a runner record yet to come? Did he reached his top of his game ?

### Abstract 

We collect our data from [World Athletics](https://www.worldathletics.org/) while using crawller and selenium.
The extracted data were analyzed by me and my parther, We learned alot on runners while looking at the data. 
We could see a clear relation between the age of the runner to his abilities, how must of the runners improving while been 18 to 25 
we were amazed to see that some runners set their record in a very young/old age (while looking at the outliers).
So for our questions above we looked at the runner proggress and by using Mechine Learning we could predict if the runner is going to set a new best record. 

### Data Science Life Cycle

<img src=https://github.com/dt170/Runners/blob/master/datacycle.png>

### Our Steps

#### Business Discovery: 
We discovered that the 100 meter is one of the most popular and prestigious events in the sport of athletics 
and chose this subject to be out project. 

#### Data Discovery:
After a long research we found [World Athletics](https://www.worldathletics.org/) website to suit our project the most. 
we had to use a crawller and selenium to get the needed information.

* Collect data from web pages.
* Download all personal pages of the runners in the dataframe. 

#### Data Preparation:
After the data was acquired we had to clean it and check for data integrity. 
* Checking data integrity (U20, df_Senior, progress_df).
* Handling Nan values.
* Adding information column to the dataframe(U20, df_Senior, progress_df).
* Save Data to csv.

#### Exploratory Analysis
Further information is in the Data Analyze page, we wrote a detailed explanation on our analysis.
* Open the csv files and save them to pd
* Analyze Senior DATA
* Conclusion Seniors
* Analyze U20 DATA
* Conclusion U20 DATA

#### Feature Engineering & Predictive Modeling
Our feature engineering was implemented on the progress data frame(df_progress).
We decided to use the following Mechine Learning to answer out questions. 

* Decision Tree
* GaussianNB
* KNeighborsClassifier

#### Conclusion

We think one of the main conclusion on this project was, that with the right information we can predicit if a runner record yet to come indeed its not 
perfect prediction, but with the little information we had and with our analyzation we succeeded to get 84 precision.
Furthermore, We were surprised to see that some runners achieved their best record on a very young/old age.
We think that if we have more information for example height,weight etc we could reach a higher precision.
Another insight we amazed to see is that a very large number of runners belong to USA nationality on the contrary from what we thought.

##### Made by 

[Dvir](https://github.com/dt170) and [Shlomy](https://github.com/ShlomyYosef)

