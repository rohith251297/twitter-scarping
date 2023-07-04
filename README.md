**Project Title:** Twitter Scraping

**REQUIRED SKILLS:**
Python scripting
MongoDB
Snscrape
Streamlit

**OVERVIEW:** I used streamlit to design a GUI that has the features I've listed below. 

1.to enter the keword or hashtag to be searched
2.to select the starting date and ending date of the tweets to be searched
3.to select the range of the data to be searched 
4.it has four columns with scrape,upload,download and saved 
  

**WORK FLOW:**

**Step1:** 
Initially I collected the Keyword, Start date, End date, and Number of tweets from the user using streamlit

**Step 2:**
TwitterSearchScraper and TwitterHashtagScraper are provided the aforementioned information. The complete scraped data is stored in a dataframe, which is now available for download in CSV or JSON format.

**Step3:**
With pymongo, the database connection is made. If a user chooses to upload data, a new collection is formed and the data is uploaded there.

**Step4:**
All of the collections that are uploaded to the database are displayed in a separate column named saved. We can view the documents in any collection by clicking it.



