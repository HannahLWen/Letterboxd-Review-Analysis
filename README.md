# Letterboxd Reviews Sentiment Analysis Project 
### Contributors: Esther Lan and Hannah Wen
This project performs sentiment analysis on movie reviews that are webscraped from the social platform Letterboxd. 
# Procedure 
This project is coded in Python. BeautifulSoup and Selenium were utilized to first webscrape information from the first 500 pages of movies sorted by popularity, then the first 5 pages of reviews sorted by popularity for each movie.  We used MYSQL to store the reviews we collected.
Using pandas, we cleaned and tokenized the data for sentiment analysis. We used the Vader nltk and Roberta models to perform our analysis. 
# Our Findings 
We discovered that 
# Lessons Learned 
We faced many obstacles in the first portion of this project when we were webscraping. Neither of us had webscraped before and we learned how to make our code more efficient and run faster since we were facing issues with runtime. 
We ended up scraping nearly 100,000 reviews and will aim to further improve our code so that we can collect more reviews since we were unable to scrape reviews for all 36,000 movies we had originally planned for. Due to the volume of our data, we decided to use a MYSQL database, which was also a new experience for us. 
More edits were made to our code to maximize efficiency in terms of collecting and inserting the data. 

If we were to do this project again, we would have also webscraped the ratings from each individual review in order to analyze the accuracy of our sentiment analysis. 
We plan on further improving this project to include ratings and create a Letterboxd webscraping Python package. 
