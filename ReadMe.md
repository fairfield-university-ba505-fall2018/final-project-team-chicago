## This is a read me file ##

## Introduction ##
This is the final project of BA505 for Angus Hastings, David Sacco, and Jonathan Uy. For our final project we used a data set that showed crime statistics in Chicago from 2012 to 2016.  We would ultimatly like to identify where the most crimes happened throughout Chicago. We were also interested in established what kind of crime occured where, and at what time. This data can be used to decide where is the safest place to live in Chicago. It can also show us where we shouldn't be and at what times we shouldn't be there. 

## Data Cleaning ##
The data set oringally crashed Jupyter Hub due to the fact it was so large. Thus, we decided to only use data from the top of the spread sheet. We used about 18,000 rows. We sliced the original date column to split up date and time into two seperate columns. We deleted all of the spaces from column names to make it easier to work with in the notebook. We deleted two columns because we believed them to be immaterial. 

## Data Analysis ##
1) We looked at the frequency of each crime. 
2) We found the frequency of crimes occuring at each location description. 
3) We looked at what specific dates had the most overall crimes. 
4) The time of day that has the most crimes. 
5) Then we looked at which district in Chicago had the most crimes. 
6) We replaced all crime description with numeric values, to allow us to run a correlation matrix. 
7) We ran a logisitic regression. 

## Conclusion ##
We think that we answered our original questions. We now know where the most crimes occur and also where the least crimes occur. We also answered at what time crimes occur, as well as what factors contribute to a person being arrested or not at the scene of the crime.