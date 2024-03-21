# scrapping_app

Overview
This project involves scraping data from various sources related to Mars, including Mars news articles and Mars weather data. The data is extracted using automated browsing techniques with Splinter and Beautiful Soup, and then analyzed to answer specific questions.

Part 1: Scrape Titles and Preview Text from Mars News (40 points)
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
The titles and preview text of the news articles were scraped and extracted.
The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.
Part 2: Scrape and Analyze Mars Weather Data (60 points)
The HTML table was extracted into a Pandas DataFrame using either Pandas or Splinter and Beautiful Soup. The columns have the correct headings and data types.
The data was analyzed to answer specific questions, including:
How many months exist on Mars?
How many Martian days' worth of data are there?
Which month, on average, has the lowest temperature? The highest?
Which month, on average, has the lowest atmospheric pressure? The highest?
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
The DataFrame was exported into a CSV file.
Getting Started
To run the code and replicate the analysis, follow these steps:

Clone this repository to your local machine.
Install the required dependencies specified in the requirements.txt file.
Run the Python scripts for scraping and analysis.
Usage
scrape_mars_news.py: Script for scraping titles and preview text from Mars news articles.
scrape_mars_weather.py: Script for scraping and analyzing Mars weather data.
Requirements
Python 3.x
Splinter
Beautiful Soup
Pandas
License
This project is licensed under the MIT License.

