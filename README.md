# mars_webscraping

# Mars Data Analysis Project

## Overview

This project involves scraping and analyzing data from Mars-related websites. Utilizing Python tools such as Splinter for automated browsing and Beautiful Soup for HTML parsing, the project extracts news titles, preview texts, and weather data from specified Mars websites. The collected data is then organized, analyzed, and visually presented to uncover insights about Mars' climate and news trends.

## Project Structure

### Files
- part_1_mars_news.ipynb: Notebook for scraping Mars news articles.
- part_2_mars_weather.ipynb: Notebook for scraping and analyzing Mars weather data.
- mars_data.json: (Optional) JSON file containing the scraped Mars news data.
- mars_weather.csv: CSV file containing the processed Mars weather data.
### Directories
- data: Contains output data files from the scrapes (if exported).
- notebooks: Jupyter Notebooks used for scraping and analysis.
- scripts: Contains any additional Python scripts used for extended analysis.

## Instructions

### Part 1: Scrape Titles and Preview Text from Mars News
- Objective: Extract news titles and preview texts from the Mars news website.
- Procedure:
1- Use Splinter to navigate to the Mars news site.
2- Utilize Beautiful Soup to parse the HTML and extract required elements.
3- Store each title and preview text as a dictionary in a list.
4- Print the list in the notebook and optionally save it as a JSON file.
### Part 2: Scrape and Analyze Mars Weather Data
- Objective: Extract and analyze temperature and pressure data from the Mars Temperature Data Site.
- Procedure:
1- Use Splinter to navigate to the Mars weather data site.
2- Employ Beautiful Soup to scrape the HTML table containing the weather data.
3- Convert the scraped data into a Pandas DataFrame.
4- Analyze the data to determine weather patterns and export the results to a CSV file.

## Usage

To run the notebooks and replicate the analysis:

1- Ensure Python 3 and necessary packages (Pandas, Splinter, BeautifulSoup) are installed.
2- Navigate to the notebooks directory.
3- Open and run the Jupyter Notebooks via Jupyter Lab or Jupyter Notebook.

## Results

The analysis provides the following insights:

- The number of months and the typical duration of a Martian year in Earth days.
- Temperature and atmospheric pressure trends over different Martian months.
- Visualizations in the form of bar charts to depict temperature and pressure data.
