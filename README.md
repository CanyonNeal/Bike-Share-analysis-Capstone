# Bike-Share-analysis-Capstone
Ask 

This project follows the fictional bike-share company Cyclistic. The topic I am exploring today is the difference between how Casual and Membership (annual subscription) use the Cyclistic bike-share services differently. 

Prepare 

The primary tool I will be using is OfficeSuite Sheets for its multi-faceted utility. 
Does the data ROCCC? Yes! 
Reliability: This data is fairly reliable. Since it is internally collected, we can more easily trust the data are reliable.
Originality: This data is fully original as it was collected by the company. 
Comprehensive: Ultimately the data are comprehensive enough for our purposes, however, there are some concerns. We are missing demographic data which might lead to valuable insights. This dataset is also very limited to the locality of Cyclistic, so it cannot be generalized to other areas. Due to my own limitations, we will only be working with the first quarter of 2023. There may be more interesting patterns to uncover throughout the years of data available. 
Current: Yes, this data is very recent. We cannot assume 2023 will be identical to 2024, but trends will still likely be similar. 
Cited: Yes, the company is credibly supplying its own data. 

Data used: https://divvy-tripdata.s3.amazonaws.com/index.html files: 202301-divvy-tripdata.zip,  202302-divvy-tripdata.zip, and 202303-divvy-tripdata.zip


Process

Due to processing speeds, I chose to limit the data to only what was valuable to this analysis. This meant from each file, I took only the columns: ride_id,	rideable_type,	started_at, ended_at, and member_casual. I then made sure the formatting for each column was correct, which is especially noteworthy for starting and ending times. I set it to the 37:30:55 time format. 
I subtracted the starting from ending time and labeled that column ride_length. 
I then used the WEEKDAY function to determine the day each ride was started into a column labeled day_of_week

Analyze and Share: 


Figure Descriptions 
Please see files
Total Ride Length Sum Percentage 
	Casual users represent 52% of the total amount of time spent with a Cyclistic bike, while members represent 48%. 

Total Number of Rides 
	Members make up 77% (494,199) of the total number of rides initiated. 
Together these paint an interesting picture: While casual users only make up approximately a quarter of the rides, they account for about half the total hours Cyclistic bikes are being used. While casual members take fewer rides, they are longer in duration. 
Number of Rides by Weekday 
	While there are many more members than casual users, they follow a similar weekly curve. Members don't as often use the bikes on weekends, but pick up on Monday, with the mode being Tuesday. They slow down again Wednesday and Thursday but a spike occurs on Friday as well. Casual users follow a similar, though flattened curve. 
Average Ride Length (Hrs) 
	Members spend a relatively consistent amount of time on an average outing regardless of what day of the week it is, that is 30-45 mins. Casual members, however, spend the longest on Sundays where they average nearly 4 hours. They also average over 3.5 hours on Monday before the lowest average day, Tuesday at about 1hr 45 mins. 
This suggests that for members, Cyclistic bikes are part of their routine. Casual users, however, spend their time in longer bursts that likely cannot be sustained daily, so are special occasions.  
Total Rides with a Classic Bike 
	Casual members make up only 17% of the total number of rides with a classic bike. 
Total Rides with an Electric Bike 
	Casual members make up 26% of the rides with an electric bike. This is an increase from the classic bikes, which suggests casual riders are more likely to sign up with Cyclistic for an electric bike over a classic bike. 



Act 
Since casual users are currently treating Cyclistic’s services as an irregular treat instead of the consistent schedules of members, I would suggest some advertisements that highlight how convenient Cyclistic is. Anything that encourages using the bike-share as a regular part of routines would be beneficial. 
This is highlighted with the casual user’s preference for electric bikes over classic bikes. That convenience seems to be an important drive for casual users. Members also start more rides with electric than classic bikes. Since it’s the preference for both groups, this is a great opportunity to draw in more casual users to become annual members without needing to de-prioritize the already existing members. 
