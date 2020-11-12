## CMPE255-Statistics of Airplane Crash Data
 
### 1) Project title
 Statistics of airplane crash data 
 
### 2) What data you’ll use and where you’ll get it? 
 https://datasetsearch.research.google.com/search?query=Airplane%20Crashes&docid=GUhYyjK%2B7677nVD6AAAAAA%3D%3D

 This dataset contains a full history of airplane crashes from 1908 to present which resulted in deaths throughout the world from civil, military, aviation, etc. 
 
 
### 3)Description of the problem you’ll solve or the question you’ll investigate. 
1) Yearly how many planes crashed? How many people were on board? How many survived? How many died?
2) Highest number of crashes by operator and Type of aircrafts.
3) ‘Summary’ field has the details about the crashes. Find the reasons of the crash and categorize them in different clusters i.e Fire, shot down, weather (for the ‘Blanks’  in the data category can be UNKNOWN) you are open to make clusters of your choice but they should not exceed 7. 
4) Find the number of crashed aircrafts and number of deaths against each category from the above step. 
5) Find any interesting trends/behaviors that you encounter when you analyze the dataset. 


##Preliminary analysis section
#### Aboard Vs Fatalities
The distribution of data in columns Aboard and Fatalities is studied by plotting distribution plots and box plots.
The box plots and distribution plots conveyed that the maximum number of fatalities and people boarding the flight for each crash are in the range 0-100, and those which are more than 100 in number for any accident in the data set are rare.

#### Fatalities Vs Accidents
The scatterplot is plotted for the each operator's accidents count and fatalities from all of its accidents, the observation obtained is as follows:
Maximum number of operators are crashed in the range of 0 - 50 accidents where the maximum fatalities for an accident are in the range 0 - 1000

#### Bar Graph for fatalities per each accident for airlines with >10 accidents 
Bar graph is plotted for fatalities on each accident for every airline. The fatalities observed for each accident are in the range of 0 - 60, when only the airlines with >10 accidents are considered. When the number of accidents are cons
