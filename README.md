### Cyclistic-Bike-Share
Aim: The given case study is focused on analysing the bike uses trends and converting the casual riders into members.
Dataset : Dataset is taken from a fictional company cyclistic.

### Steps to approach the case study:
#### 1. Download the Datasets and combine it into one file
We have to download the dataset from the 'https://divvy-tripdata.s3.amazonaws.com/index.html'. 
Downloaded dataset is in 12 files(12 files are for 12 months). 
So we have to combine the these files into single file for further steps.

#### 2. Perform necessary data cleaning
Now we will have clean our dataset so that it is perfect for analysis.
(a) Convert 'started_at' and 'ended_at' columns to datetime format.
(b) Calculate 'ride_length' in minutes.
(c) Extract 'day_of_week' from 'started_at'.
(d) Remove rows with missing station names or negative ride lengths.
(e) Handle the duplicate values.
(f) Save the cleaned dataset as a new .csv file.

#### 3. Data analysis phase:
During data analysis phase we will extract the insights from the given data so that aforemensioned business task can be fulfilled:
(a) Now we will calculate the total overall rides across 12 months.
(b) How many rides were done by the casual riders vs members.
(c) Overall average ride duration.
(d) Overall ride duration by user type.
(e) Bike type usage.
(f) Hourly bike usage.

#### 4. Visualize the insights.
Now we have to visualize the extracted insights using charts such as pie chart and line charts etc.

#### 5. Recommend the necessary steps such as:
(a) Target Casual Riders with Weekend Promotions.
(b) Sell the membership to casual riders.
(c) Optimize Bike Distribution etc.


