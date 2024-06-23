# REVISION_PANDAS-LIBRARY #

# WEATHER 
Q. 1) Find all the unique 'Wind Speed' values in the data. 

Q. 2) Find the number of times when the 'Weather is exactly Clear'. 

Q. 3) Find the number of times when the 'Wind Speed was exactly 4 km/h'. 

Q. 4) Find out all the Null Values in the data.

Q. 5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'. 

Q. 6) What is the mean 'Visibility' ? 

Q. 7) What is the Standard Deviation of 'Pressure' in this data? 

Q. 8) What is the Variance of 'Relative Humidity' in this data ?

Q. 9) Find all instances when 'Snow' was recorded. 

Q. 10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.

Q. 11) What is the Mean value of each column against each 'Weather Condition ? 

Q. 12) What is the Minimum & Maximum value of each column against each 'Weather Condition? 

Q. 13) Show all the Records where Weather Condition is Fog. 

Q. 14) Find all instances when 'Weather is Clear' or 'Visibility is above 40'. 

Q. 15) Find all instances when: A. 'Weather is Clear' and 'Relative Humidity is greater than 50' or B. 'Visibility is above 40'



#CARS

Q. 1) Find all null values in the data. If there is any null value in that column then fill that value with mean of that column.

Q.2) Check what are the types of makes are there in our dataset, and what is the count(occurrence) of each make in the data.

Q.3) Show all the records where origin is Asia or Europe.

Q.4) Remove all the records where weight is above 4000.

Q.5) Increase all the values of MPG_City by 3.


#POLICE

Q.1) Remove all the column that contain only missing values. Drop unnecessary columns.

Q.2) For speeding, were Men or Women stopped more often?

Q.3) Does gender affect who gets searched during a stop?

Q.4) What is the mean stop_duration?	

Q.5) Compare the age distribution for each violation?

#COVID DATA

Q. 1) Show the number of Confirmed, Deaths and Recovered cases in each Region. 

Q. 2) Remove all the records where the Confirmed Cases is Less Than 10.

Q. 3) In which Region, maximum number of Confirmed cases were recorded? 

Q. 4) In which Region, minimum number of Deaths cases were recorded? 

Q. 5) How many Confirmed, Deaths & Recovered cases were reported from India till 29 April 2020?

Q. 6-A) Sort the entire data wrt No. of Confirmed cases in ascending order. 

Q. 6-B) Sort the entire data wrt No. of Recovered cases in descending order.

#LONDON HOUSING DATA


Q. 1) Convert the Datatype of 'Date' column to Date-Time format. 

Q. 2) Add a new column ''year'' in the dataframe, which contains years only.(B.2) Add a new column ''month'' as 2nd column in the dataframe, which contains month only.

Q. 3) Remove the columns 'year' and 'month' from the dataframe. 

Q. 4) Show all the records where 'No. of Crimes' is 0. And, how many such records are there ?

Q. 5) What is the maximum & minimum 'average_price' per year in england ?

Q. 6) What is the Maximum & Minimum No. of Crimes recorded per area ? 

Q. 7) Show the total count of records of each area, where average price is less than 100000.

#CENSUS

Q. 1) How will you hide the indexes of the dataframe.

Q. 2) How can we set the caption / heading on the dataframe.

Q. 3) Show the records related with the districts - New Delhi , Lucknow , Jaipur.

Q. 4) Calculate state-wise : A. Total number of population. B. Total no. of the population with different religions. 

Q. 5) How many Male Workers were there in Maharashtra state ? 

Q. 6) How to set a column as index of the dataframe ?

Q. 7a) Add a Suffix to the column names. Q. 7b) Add a Prefix to the column names.

#Udemy
Q. 1) What are all different subjects for which Udemy is offering courses ? 

Q. 2) Which subject has the maximum number of courses. 

Q. 3) Show all the courses which are Free of Cost. 

Q. 4) Show all the courses which are Paid. 

Q. 5) Which are Top Selling Courses ? 

Q. 6) Which are Least Selling Courses ? 

Q. 7) Show all courses of Graphic Design where the price is below 100 ? 

Q. 8) List out all the courses that are related to 'Python'. 

Q. 9) What are courses that were published in the year 2015 ? 

Q. 10) What is the Max. Number of Subscribers for Each Level of courses ?


#UDEMY
Q. 1) What are all different subjects for which Udemy is offering courses ? 

Q. 2) Which subject has the maximum number of courses. 

Q. 3) Show all the courses which are Free of Cost. 

Q. 4) Show all the courses which are Paid. 

Q. 5) Which are Top Selling Courses ? 

Q. 6) Which are Least Selling Courses ? 

Q. 7) Show all courses of Graphic Design where the price is below 100 ? 

Q. 8) List out all the courses that are related to 'Python'. 

Q. 9) What are courses that were published in the year 2015 ? 

Q. 10) What is the Max. Number of Subscribers for Each Level of courses ?
	
#NETFLIX

Task. 1) Is there any Duplicate Record in this dataset ? If yes, then remove the duplicate records. Task. 2) Is there any Null Value present in any column ? Show with Heat-map. 

Q. 1) For 'House of Cards', what is the Show Id and Who is the Director of this show ?

Q. 2) In which year the highest number of the TV Shows & Movies were released ? Show with Bar Graph. 

Q. 3) How many Movies & TV Shows are in the dataset ? Show with Bar Graph. 

Q. 4) Show all the Movies that were released in year 2000. 

Q. 5) Show only the Titles of all TV Shows that were released in India only. 

Q. 6) Show Top 10 Directors, who gave the highest number of TV Shows & Movies to Netflix ? 

Q. 7) Shosw all the Records, where "Category is Movie and Type is Comedies" or "Country is United Kingdom". 

Q. 8) In how many movies/shows, Tom Cruise was cast ? 
Q. 9) What are the different Ratings defined by Netflix ? 

Q. 9.1) How many Movies got the 'TV-14' rating, in Canada ? 

Q. 9.2) How many TV Shows got the 'R' rating, after year 2018 ? 

Q. 10) What is the maximum duration of a Movie/Show on Netflix ? 

Q. 11) Which individual country has the Highest No. of TV Shows ? 

Q. 12) How can we sort the dataset by Year ? 

Q. 13) Find all the instances where: Category is 'Movie' and Type is 'Dramas' or Category is 'TV Show' & Type is 'Kids' TV'.

#SURVEY

1 - Load the dataset into a pandas dataframe. Name the variable as “survey”. 

2 - How many samples were collected on each day? 

3 - What proportion of the total respondents were aged less than 45? 

4 - Create a new column in the dataframe “age_group”. This column should contain the age group the respondent belongs to. The age groups are 18-25, 25-40, 40-55 and 55+. The dataframe should look like this after the column creation. 

5 - How many samples were collected for each age-group? Which age-group had the most samples? 

6 - What proportion of the respondents had opted for the RJD party in both the Vote_Now and the Past_Vote questions? 

7 - For each day of sample collection, determine the proportion of respondents who were fully satisfied with the performance of the CM. So if there were a total of 1000 samples on day 1 and 300 out of those said 
they were fully satisfied, then our answer for that day would be 0.3. 

8 - In a similar fashion create a day-wise proportion of respondents that opted fully dissatisfied with their MLA. Create a line plot of the result with date on x-axis and proportions on the y-axis. 

9 - Create a pivot-table (or crosstab) with index as Past_Vote, Column as Vote_Now and cell values as the count of samples. Answer - survey.pivot_table(index = 'Past_Vote', columns = 'Vote_Now', values = 'response_id', aggfunc = 'count') 

10 - Repeat the above question with the cell values as the sum of “weight”. 

11 - Create a dataframe by performing a group by over age_group and calculate the count of total samples under each age_group. 

12 - Create a dataframe by performing a group by over age_group and finding the count of total samples for each age_group that opted for the JD(U) party in Vote_Now. 

13 - Join/Merge the two dataframes from questions 12 and 11 with the common column as age_group.


