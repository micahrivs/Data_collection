# Web Scraping and Data Analysis Project

This README file provides an overview of the web scraping and data analysis project focusing on Mars. The project consists of two main parts: scraping titles and preview text from Mars news articles, and scraping and analyzing Mars weather data.

## Part 1: Scrape Titles and Preview Text from Mars News

In this part of the project, we will leverage automated browsing with Splinter and HTML parsing with Beautiful Soup to visit the Mars News website and extract the relevant information.

To get started, follow the steps below:

1. Open the Jupyter Notebook named **part_1_mars_news.ipynb** located in the starter code fol
2. Utilize automated browsing techniques to visit the Mars news site and carefully inspect the page to identify the specific HTML elements that need to be scraped.

3. Create a Beautiful Soup object and utilize it to extract the desired text elements from the website.

4. Extract the titles and preview text of the news articles and store the scraping results in Python data structures. 

5. Print the resulting list in your Jupyter Notebook.

6. As an optional step, you can export the scraped data to a JSON file to facilitate sharing the data with others. However, please note that there are no additional points awarded for completing this step.

## Part 2: Scrape and Analyze Mars Weather Data

The second part of the project focuses on scraping and analyzing Mars weather data using automated browsing and Beautiful Soup.

To complete this part of the project, please follow the steps below:

1. Open the Jupyter Notebook named **part_2_mars_weather.ipynb** located in the starter code folder.

2. Use automated browsing techniques to visit the [Mars Temperature Data Site](Links to an external site.) and carefully examine the page to identify the HTML elements that need to be scraped. The URL for the site is [https://static.bc-edx.com/data/web/mars_facts/temperature.html](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

3. Create a Beautiful Soup object and utilize it to extract the data from the HTML table. While it is possible to use the Pandas `read_html` function for this task, we will continue using Beautiful Soup to enhance our web scraping skills.

4. Assemble the scraped data into a Pandas DataFrame. Ensure that the columns in the DataFrame have the same headings as the table on the website. The columns should include the following information:

   - id: The identification number of a single transmission from the Curiosity rover.
   - terrestrial_date: The date on Earth.
   - sol: The number of elapsed sols (Martian days) since Curiosity landed on Mars.
   - ls: The solar longitude.
   - month: The Martian month.
   - min_temp: The minimum temperature in Celsius for a single Martian day (sol).
   - pressure: The atmospheric pressure at Curiosity's location.

5. Take a look at the data types associated with each column in the DataFrame. If necessary, cast or convert the data to the appropriate datetime, int, or float data types.

6. Analyze the dataset using various
