# Data-Visualization
We used the datasets athlete_events and noc_regions.
The athlete dataset has all the information about the olympics except their regions,the noc_regions has only the participants regions so we had to merge between both of them.
Our motivation is to visualize the data and study how the performance is affected by varies factors. For example player's characteristics that increase performance in different sports.
Moreover,we tested if the country is hosting the olympics,would the performance increase? And if a team won a gold medal, does this affects the performance positively later on?
Steps:
1-We added the 2 datasets and merged them.
2-We dropped duplicates from the merged dataset.
3-We calculated the null_values_percentages for every column.
4-We divided the data into males and females and grouped them by region and sports then we calculated the mean of females' height and weight and males' height and weight .
5-We started dealing with outliers in height and weight,First, we dropped all the null values,second, we visualized the outliers on 4 boxplots "female height","male height",
"female weight","male weight",third we calculated the IQR and removed all the outliers in all the plots.
6-We added the null values of weight and height to new dataframes males and females and filled them with the means we calculated before. 
7-We concatenated the 2 frames males and females into 1 dataframe and calculated the null_values_percentages for every column again.
8-In order to see the effect of hosting on the performance, we had to convert each region to its country and added new column 'Host_Country'.
9-We grouped the new data by 'Year','Host_Country','region','Medal' in a new dataframe and filled the null values in medal with 0, then we added cloumn 'Is_Host' to check if the medal country is 
the same hosting country or not.The column's values are either 1 if hosting,0 if not.
10-We added a new column to calculate the total medals for each country in each year, then we sorted it ascendingly in a new dataframe.
11-We plotted 3 graphs to prove how the countries' performance is affected due to their hosting.
To prove the relationship between characteristics and performance:
12-We plotted a graph to show the difference between males and females performance in Weightlifting with respect also to their weights.
13-We plotted a graph to show the relationship between performance and height in the Basketball sport.
14-We plotted a graph to show the relationship between performance and age in the Gymnastics sport and in all sports.
15-We plotted a graph to show Women medals per edition of the Games.
16-We plotted a graph to show men medals per edition of the Games.
17-We plotted a pie chart, 2 scatter plots to show the relationship between performance and season.
To visualize data after cleaning:
1-We plotted a graph to show the participants' age.
2-We plotted a graph to show variation of Age for Male Athletes over time.
3-We plotted a graph to show variation of Age for Female Athletes over time.
4-We plotted a graph to show Height and Weight Variation between males and females.
5-We plotted a graph to show total Medals by Country
6-We plotted a graph to show Gender Distribution
7-We plotted a graph to show Variation of Female Athletes over time.
8-We plotted a graph to show Variation of Sports for Males over time.
9-We plotted a graph to show Variation of Sports for Females over time.
Questions:
1)Does being the host improve the performance?
2)Is there characteristics that improve the chances of winning a medal?
