# Analysis and visualization of Video games sales dataset
## Selma Laarabi
## 1.Introduction
- In this Readme file we're going through the analysis of a video games sales dataset, as well as enriching it with demographic data using API's.
- the sources used for this analysis :
   * Dataset from  https://www.kaggle.com/datasets
   * API from https://data.worldbank.org/indicator/SP.DYN.CBRT.IN
## 2.Describing the Data set
The data set used in this project contains information about the release and sales of video games in 4 different regions (North America, EU, Japan, and others),
as well as information about games genre and publishers, over the years from 1980 until 2020.
contains a list of incidents reported as shark attacks.
Their fields and data types are:
 - Rank - Ranking of overall sales, integer.
 - Name - The games name.
 - Platform - Platform of the games release (i.e. PC,Wii,PS2 etc.), object.
 - Year - Year of the game's release, float.
 - Genre - Genre of the game ,object.
 - Publisher - Publisher of the game, object.
 - NA_Sales - Sales in North America (in millions), float.
 - EU_Sales - Sales in Europe (in millions), float.
 - JP_Sales - Sales in Japan (in millions), float.
 - Other_Sales - Sales in the rest of the world (in millions), float.
 - Global_Sales - Total worldwide sales, float.
 - 
## 2.Analysis and visualization
After going through a little bit of cleaning, which involved dropping missing data from publishers column, we start our analysis, and answering some questions.
most importantly, how popular video games got over the years.
  ** add table image **
  
  - Which genre is the most popular?
    * Per release, sales, and region.
  - Which is the most popular platform?
    * Per release, sales.
   - Did Video games poularity increased over the years ?
      * Which year had the most sales?
      * In which region they got the most popular?
     
    
After answering the question above, we are crossing our dataset with data from World bank about birth rate using API,
we are going to look for some correlations between birth rate and video games popularity.
### Let's start with the first question

    
    
    
    
  
  
 




