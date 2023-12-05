# Mars Data Scraping Challenge

## Project Deliverables
- Deliverable 1: Scrape titles and preview text from Mars news articles.

- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Data Source

1. [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html)

2. [Mars Temperature Data Website](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

## Deliverable 1: Scrape Titles and Preview Text from Mars News

1. Used automated browsing to visit the [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html). Then, inspected the page to identify which elements to scrape.
2. Created a Beautiful Soup object and used it to extract text elements from the website.

3. Extracted the titles and preview text of the news articles that you scraped. Stored the scraping results in Python list of dictionaries.
4.  Stored the scraped data in a file. 

## Deliverable 2: Scrape and Analyze Mars Weather Data
1. Used automated browsing to visit the [Mars Temperature Data Website](https://static.bc-edx.com/data/web/mars_facts/temperature.html). Then, inspected the page to identify which elements to scrape.
2. Created a Beautiful Soup object and used it to scrape the data in the HTML table. 

3. Assembled the scraped data into a Pandas DataFrame.

4. Examined the data types that are currently associated with each column.
 
5. Analyzed your dataset by using Pandas functions to answer the following questions:

- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
- Which months have the lowest and the highest atmospheric pressure on Mars? 
- About how many terrestrial (Earth) days exist in a Martian year? 

6. Exported the DataFrame to a CSV file.
### Acknowlegment
Mentor Abbas helped me answer the 5th question of part 2 of the assignment. The code gives an exact answer to the question according to the dataset provided, instead of just a visual estimate of the count of the terrestrial days in a Martian year. 
