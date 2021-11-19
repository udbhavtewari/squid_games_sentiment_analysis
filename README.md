# squid_games_sentiment_analysis
![This is an image](https://image.scoopwhoop.com/w1200-h667-cfix/https://s4.scoopwhoop.com/anj2/6156a3188a373a1f9294f868/8125c2da-1b04-4a4d-8820-55969bf17164.jpg) <br /> 
We all saw the massive popularity of Squid Games on Netflix. Since I was an exception, I decided to run a sentiment analysis to see whether it was worth the hype or not.
The sentiment analysis was done broadly in 3 parts.  

- Part I ) Scrapping of Squid Games reviews. 
  - I scrapped 1600 reviews from the [IMDB website](https://www.imdb.com/title/tt10919420/reviews?spoiler=hide&sort=reviewVolume&dir=desc&ratingFilter=0). 
  - Extracted reviews,ratings & its corresponding dates
  - Appended those to empty lists
- Part II) Cleaning of the data
  - Since the reivews had inconsistent formatting, I firstly deleted the duplicate rows.
  - Fixed the rating column and its data type
  - Did some EDA 
 - Part III) Running the sentiment analysis 
   - Imported TextBlob to get polarity & subjectivity
   - Constructed a word cloud to visualise the reviews
   - Calculated the % of positive,negative & neutral reviews & visualised them via a bar chart 


### Library used : 
1. pandas
2. requests 
3. BeautifulSoup
4. numpy
5. Selenium 
6. TextBlob


