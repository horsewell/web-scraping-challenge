# Module 11 Challenge

Web-scraping and data analytics of Mars weather data

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

## Deliverable 1: Scrape titles and preview text from Mars news articles.

Using the following Jupyter Notebook: part_1_mars_news.ipynb

* Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
* The titles and preview text of the news articles were scraped and extracted.
* The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

## Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.

Using the following Jupyter Notebook: part_2_mars_weather.ipynb

* The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types.
* The data was analysed to answer the following questions:
  * How many months exist on Mars?
  * How many Martian days' worth of data are there?
* The data was analysed to answer the following questions, and a data visualisation was created to support each answer:
  * Which month, on average, has the lowest temperature? The highest?
  * Which month, on average, has the lowest atmospheric pressure? The highest?
  * How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
* The DataFrame was exported into a CSV file into the folder output.

Student Tyson Horsewell