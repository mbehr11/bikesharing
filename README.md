#Bikesharing_Analysis
Tableau week 14
# Bikesharing_Analysis
Working with Amazing Prime using SQL with PGadmin4 and python
## Overview of Bikesharing_Analysis:
After vacationing with your friend Kate in New York City, you were looking through your vacation photos when you had a brilliant idea. Part of what made your trip so enjoyable was being able to travel around the city using a service called Citibike. This allowed you to really get to know the city and the people who lived there on a more personal level. So, what if you could bring a similar bike sharing company to your hometown of Des Moines, Iowa. You immediately brought this idea up to Kate and start brainstorming on how to make this happen. She follows up with you after a few weeks and has great news. A potential investor might be interested in providing funding to explore a bikeshare program in Des Moines. But first, we need to do an analysis of how the program was successful in New York. Then, we can bring ideas to the table of how it would be successful in Des Moines. 
#### The below pseudocode provided us an outline for the analysis ####
•	Deliverable 1:  Change Trip Duration to a Datetime Format
•	Deliverable 2 Create Visualizations for the Trip Analysis 
•	Deliverable 3: Create a Story and Report for the Final Presentation
#### The following questions were also formulated to guide my analysis: ####
•	What is the average trip duration?

•	What station do most people travel to and or from?
•	What are the most popular times to ride?
•	Was the user type subscribers or customers?
•	Are the average users older or younger? What is the average user age?
•	Are the users typically male or female most commonly?
•	How many trips were recorded in total in August?

[https://public.tableau.com/app/profile/morgan.behr/viz/NYC_CitiBike_tableau/NYCCitibikeanalysis?publish=yes] (Tableau Link)

### Bikesharing_Analysis: ###
1.	#### Top Checkout Times:  ####

![alttext](https://github.com/mbehr11/bikesharing/blob/main/Resources/Top_Checkout_Times.PNG) 

•	As you can see from the above visualization, bikes were most often rented to travel for around 5 minutes. If we take this data to Des Moines, then we can set up locations and trip destinations around 5 minutes apart from each other.  

2.	#### Top Checkout Times by Gender ####

![alttext](https://github.com/mbehr11/bikesharing/blob/main/Resources/Top_Checkout_Times_by_Gender.PNG)

•	In this above visualization, we can see that males were most often using the bikes at count of 108, 087 compared to females at 34,151 and unknown at 7,389. This tells me that for eds Monies, we need to cater advertising towards males, but also find different campaign strategies to attract females as well. Such as through targeted advertising or specials for females. 

3.	#### Top Times for Bike Use by Weekday ####

![alttext](https://github.com/mbehr11/bikesharing/blob/main/Resources/Top_Times_for_Bikeuse_by_Weekday.PNG)

•	For this above visualization, we can see that the most popular time for bike use is between 5 and 6 pm. Which means people are most often using them once they get off work. For Des Moines, we could start to target those times for surge pricing and offer deals to bring more people in during that peak time. 

4.	#### Top Trip Time by Gender & Hour ####

![alttext](https://github.com/mbehr11/bikesharing/blob/main/Resources/Top_Trip_Times_by_Gender%26Hour.PNG)

In this visualization We can see that the males most often use the bikes on Thursdays between 5 and 6 pm. This seems to tie in with the time when most people are getting off work. If we were bringing the bikes to Des Moines, I would work with local businesses to tie in deals on bike trips and restaurants/bars for happy hour deals to attract more customers.  I also see a slight peak around 8 am when people are going into work, so we could provide targeted advertising and deals to increase use during those times. 

5.	#### User type & Popular Use Time by Gender ####

![alttext]( https://github.com/mbehr11/bikesharing/blob/main/Resources/Usertype%26_Popular_Use_Time_by%20Gender.PNG )

•	For this visualization, we took the previous visual and broke it down by User type as well. We can see that subscribers to the bike app are most often to use the service. Also, again it is most popular with males and on Thursdays and Fridays. 

6.	#### Top Starting Locations ####

![alttext](https://github.com/mbehr11/bikesharing/blob/main/Resources/Top_Starting_Locations.PNG )

•	I decided to add this visualization to the story because we see where most often people are picking up the bikes. This shows that latitude 40.7609 and longitude -74.0028 was the most popular starting locations. We can take this information to our startup in Des Moines to help us map out where our bikes stations need to be set up at. 
•	
7.	#### Top Ending Locations ####
![alttext](https://github.com/mbehr11/bikesharing/blob/main/Resources/Top_Ending_Locations.PNG)

•	For this visualization I decided to also add the top ending locations so we could track on a map the most common trips people were taking and where they were ending up at. The most popular ending location was 40.7609 and longitude -74.0028.  So as you can see most people rode their bikes in a circular route around that location We can take this information to our startup in Des Moines to help us map out where our bikes stations need to be and put it near popular bars and restaurants. 

•	Additionally, I would add a heatmap of the top starting location and top ending location with the end station id to help better focus on where the top stations are. I would also do a further analysis using the converted gender and comparing it to the trip duration and user type in a bar graph to see how we can target our advertising for Des Moines. 
## Contributing 
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
