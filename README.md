# Twitter_Scrapping_Streamlit

This project allows you to scrape the tweets within the range of date and tweet limit for specific keyword or hastag.The project is built using 'Python', 'Pandas', Snscrape', 'Streamlit'.

REQUIRED SKILLS

1.Python 

2.MongoDB

3.Snscrape

4.Streamlit

OVERVIEW:

GUI is created using streamlit that contains the follwing features

1.Can enter any keyword or Hashtag to be searched,

2.Enter the starting date

3.Enter the ending date

Tweets Limit

After Scrapping 

1.Displays all the scraped data

2.Uploads data to DATABASE

3.Download data as CSV

4.Download data as JSON

HOW IT WORKS

Step 1: Initially keyword/hastag is collected and the starting and ending date is selected along with the tweet limit

Step 2: The details are feb to TwitterSearchScrapper and a dataframe is created to store the entire scraped data.

Step3: A database connection is estabilished using pymongo.New collection will be created and data is uploaded into that collection.

Step 4: The scraped data can be downloaded as CSV or JSON format.




