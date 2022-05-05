# wayfair-twitter-api

Project Name:
Wayfair Data using Twitter API

Project Objective:
	This project is helping wayfair better target its high potential customers 
	
How are you solving this problem? 
	I am collecting data on what accounts wayfair twitter followers also follow to find commonly followed accounts among wayfair followers. Based on the popularity of accounts I will give marketing or advertising recommendations to wayfair.

Job Description:
	The company I selected was wayfair and the title is a business analyst internship position for the summer. The description for the posting highlights that this job will be focused on targeting high potential customers for wayfair. The listing gives different areas that will be targeted to reach potential customers such as search, display, email, social media, and TV/online video. 
For my project I decided to delve into the social media field and gather more information about a high potential customer through Twitter to better target ads. I am making the assumption that a high value customer is someone that follows wayfair on twitter. I will collect data on what other accounts wayfair followers also follow.

Data:
I obtained data from the twitter API where I collected information on the users that follow twitter and other accounts those users follow. I had to use tweepy, a python twitter api library to collect the data. 
The data is stored into tables where I have one that is full of the accounts that other wayfair twitter followers also follow. There is an additional table storing the username of wayfairs twitter followers have. 

Notebooks: 
presentation link: https://github.com/colemon44/wayfair-twitter-api/blob/main/presentation.ipynb This notebook is a merge of my two other analysis and data collection notebooks that has been put in presentation slide format with rise.
sql analysis link: https://github.com/colemon44/wayfair-twitter-api/blob/main/sql_analysis_cole_montoya.ipynb
My sql analysis notebook contains the queries I performed to verify and analyze the collected data along with business reccomendations and comments
data collection link: https://github.com/colemon44/wayfair-twitter-api/blob/main/TwitterAPIcollection.ipynb
The data collection notebook contains the code I used to call data from the twitter API on Wayfairs's followers

Future Improvements:
	If I had more time I would have mainly focused on getting the pagination done bug free because I was forced to abandon pagination due to my inability to solve the errors. I also ran into a problem where it would not append to the current data after the 15 minute sleep time so I was forced to run if-exists=’replace’. If either of these worked it would have allowed me to retrieve more data and get more meaningful conclusions to make better marketing recommendations to the wayfair team. 
