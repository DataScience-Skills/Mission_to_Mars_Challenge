# Mars Web Scraping and Data Analysis

![Mars Atmospheric Pressure](https://github.com/robert-z-lehr/Scraping-and-Analyzing-Mars-News/blob/main/images/mars-atmospheric-pressure.png)
![Mars Minimum Temperature](https://github.com/robert-z-lehr/Scraping-and-Analyzing-Mars-News/blob/main/images/mars-daily-minimum-temperature.png)

## Background
Information is webscraped from the [Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html#) and [Mars Temperature Data webste](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

## Purpose
To  web scrape relevant information from the [Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html#) and [Mars Temperature Data webste](https://static.bc-edx.com/data/web/mars_facts/temperature.html). The extracted titles, preview text, and weather data, will be organizated, analyzed, and visualized.

## Tools
- Splinter: Automated browsing
- Beautiful Soup: HTML parsing and data extraction
- Pandas: Data manipulation and analysis
- Python: Scraped data stored in dictionaries and lists
- Matplotlib: Visualizing insights through bar charts
- os: To ouput results to csv

## Results
This project will yield the following deliverables:
### Deliverable 1: Scrape Titles and Preview Text from Mars News
- Use automated browsing and Beautiful Soup to extract titles and preview text from Mars news articles.
- Store the scraped data in Python dictionaries and a list.
- Print the list of dictionaries containing title and preview pairs.

### Deliverable 2: Scrape and Analyze Mars Weather Data
- Use Beautiful Soup to scrape weather data from the Mars Temperature Data Site.
- Assemble scraped data into a Pandas DataFrame with specific columns.
- Analyze the data using Pandas functions to answer various questions.
- Visualize findings by plotting bar charts.
- Export the DataFrame to a CSV file.