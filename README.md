# web_scraping_mars_data_analysis
The goal of the project is to:
1. Scrape titles and preview text from Mars news articles.
2. Scrape and analyze Mars weather data provided in a table.

Tools used for the project include:
1. Splinter
2. Beautiful Soup
3. Jupyter Notebook
4. Pandas

This project is divided into two parts. 
Part 1: Analyzing Mars news articles.
Part 2: Analyzing Mars weather data provided as a table.

PART 1:
Analyzing Mars news articles:

1. Used automated browsing  to visit MARs NEWS SITE.
  
2. Created a Beautiful Soup object to extract text elements from the website.

3. Extracted the news articles 'titles' and 'preview text.'

4. Stored each title-and-preview pair in a Python dictionary and gave each dictionary two keys: title and preview.

5. Stored all the dictionaries in a Python list.


PART 2: 
Analyzing Mars weather data 

1. Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site. The URL used was https://static.bc-edx.com/data/web/mars_facts/temperature.html.

2. Created a Beautiful Soup object to scrape the data in the HTML table.

3. Assembled the scraped data into a Pandas DataFrame. The data frame had the following columns:
   
    id: the identification number of a single transmission from the Curiosity rover
  
    terrestrial_date: the date on Earth
  
    sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
  
    ls: the solar longitude
 
    month: the Martian month
  
    min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)

    pressure: The atmospheric pressure at Curiosity's location.
   
4 Examined and cast the data types to appropriate datetime, int, or float data types if necessary. 

5. Analyzed the dataset by using Pandas functions to answer the following questions:
   
   1. How many months exist on Mars?
  
   2. How many Martian (and not Earth) days' worth of data exist in the scraped dataset?
  
   3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  
   4. Which months have Mars's lowest and highest atmospheric pressure?
  
   5. How many terrestrial (Earth) days exist in a Martian year?
  
6. Exported the DataFrame to a CSV file.

