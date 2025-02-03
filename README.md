Project Title : Weather Analysis


Overview
This project analyzes weather trends using Python, Pandas to answer 14 key questions.


dataset
- source : Youtube
- Format : CSV
- key columns : Date/Time, Temp_C, Dew Point, Temp_C, Rel,Hum_%, Wind,Speed_km/h, Visibility_km, Press_kPa, Weather,Condition


Steps used to Analyse the Dataset:
- .head() : it shows the first N rows in the data (default is 5)
- .shape : it shows the number of columns and rows in the dataset
- .index : This provides the index of the dataset
- .columns : it shows each column
- .dtypes : data types of each column
- .unique() : shows all the unique values columns [Only Can be Applied to single column]
- .nunique() : show all the unique values in columns [Can be applied to whole dataset and single column]
- .count : This returns the sum of not null values [Can be applied to individual and whole dataset]
- .value_counts() : It shows all the unique values with their count [Can be only be applied to single column]
- .info : Provides information about the dataset


Questions Explored
- Q1.Find all the unique 'Wind Speed' values in the data
- Q2.Find the number of times weather is clear
- Q3.Find the number of times the 'Wind speed was exactly 4km/h'
- Q4.Find out the Null values in data.
- Q5.Rename the column name 'Weather' of the dataframe to 'Weather Condition'
- Q6.What is the mean 'Visibility'?
- Q7. What is standard deviation of 'Pressure' in this data ?
- Q8.What is the Variance of the 'Relative Humidity' in this data ?
- Q9.Find the instances when 'Snow' was recorded.
- Q10.Find all the Instances when 'Wind Speed is above 24' and 'Visibility is 25'.
- Q11.What is the Minimum and Maximum value of each column against each weather column
- Q12.Show all the records where Weather Condition is Fog.
- Q13.Find all instances when 'Weather is Clear' or 'Visibility is above 40
- Q14.Find all the instances when: A. 'Weather is clear' and 'Relative Humidity is greater than 50' OR B.'Visibility is above 40'


Technologies Used
- Python
- Pandas,Matplotlib
- Jupyter Notebook













