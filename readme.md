## Ford GoBike System Data Set
## by Onyeogulu Tochukwu .R.

## Dataset Summary

> The Ford GoBike System data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data set used for this project spans from january  to april 2020. Some Data wrangling techniques was carried on the data set in other to prepare the data for visualization. New features where also created in other to extract more meaningful information from the data. The oringinal data set contains 14 features while 4 new features where created from the start time and end feature of the data set. 

### Data Wrangling Steps
> The original data set where saved in three different data frames which required us to concatenate the data frames into one data frame. New features which are start_day, end_day, Start_month, End_month where created in other to extract meaningful insights from the data. Some transformations where also carried out from on some feature in the data set.

## Summary of Findings
> The summary of the findings from this project will be summarized in three different stages which are;
> - Summary for Univariate Visualization
> - Summary for Bivariate Visualization
> - Summary for Multivariate Visualization

## Univariate Visualization
> Analysis of the main features in the data set shows that majority  (60%) of the riders are of user type subscribers. The most popular rental access method is through the app as visualization shows that alomot 90% of the population access their bike through their app. Analysis of support features showed that most prefered start and end day was wednesday, thursday and friday. while most prefered start and end month was february. while the least start and end month is april and the least prefered start day are saturday and sunday. Majority of the population start and end station latitude lies between 37 to 38. while the start and end station longitude lies between -120 t0 -122.

## Bivariate Visualization
> Bivariate exploration of the user type feature and the start day and end day features shows that there exists a relationship between a these features and the user type feature. The chart shows that we have majority of the user type of category subscribers and there preferred start day where wednesday, thursday and friday. The bivariate exploration of the rental access method feature and the start day and end day features shows that there is a relationship between the features and the rental access method. majority of the rider are of rental acces method category app and prefered start and end day lie between wednesday, thursday and friday. The user type feature and the start month and end month feature shows a relatiomship as user type category subscriber has the higest number of riders with prefered start and end month as feburary. The rental access method feature shows a relationship with the start month and end month feature as majority of the rider are of the rental access method category app and most prefered start and end month to be feburary. other variable such as duration in seconds, start station latitude, end station latitude, start station longitude, end station longitude do not shows much difference with respect to the user type and rental access method feature as the categories of the user type and rental access method feature follows the same distribution. Another findings is the presence of outliers.

## Multivariate Visualization
> The multivariate analysis carried out between the start day, end day, duration in seconds and user type shows that the customer category has all the days with the same median and quartiles except for saturday and sunday while for the subscriber category  has all day have the same median and quartiles. the same applies for multivariates analysis between end day, duration in second and user type. The multivariate visualization carried out between the start month, duration in seconds and user type showed that in the customer category the month of april has a higher duration second spent than other month. In the subscriber category all the month followed the same distribution with april showing a slight difference. The same is seen i the multivariate visualization between end month, duration in seconds and user type.

## Key Insights for Presentation
> The following relationships below are the key insights that i will be polishing up for my presentation.

> - Chart showing the realtionship between start day, end day and user type
> - Chart showing the relationship between start month, end month and user type
> - Chart showing the relationship between start day, end day, duration in seconds and user type
> - Chart showing the relationship between start month, end month, duration in seconds and user type
> - Chart showing the relation between start station latitude, stop station latitude and duration in second. 
