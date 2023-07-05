# Mars Data Scraping and Analysis

This project involves scraping data from two different websites related to Mars and analyzing the scraped data using Python libraries like Splinter, BeautifulSoup, and Pandas. The project consists of two parts: Mars News Scraping and Mars Temperature Data Analysis.

## Part 1: Mars News Scraping

### Dependencies
- Splinter
- BeautifulSoup

In the first part of the project, automated browsing is used to visit the Mars news site and extract text elements from the website. The steps involved in scraping the Mars news site are as follows:

1. Use automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html).
2. Create a Beautiful Soup object to parse the HTML of the visited site.
3. Extract all the text elements on the page using appropriate HTML tags and class attributes.
4. Store the extracted title and preview text pairs in a list of dictionaries, with each dictionary representing an article.
5. Print the list of dictionaries containing the scraped data.

## Part 2: Mars Temperature Data Analysis

### Dependencies
- Splinter
- BeautifulSoup
- Pandas
- Matplotlib

In the second part of the project, the Mars temperature data site is scraped to extract data from an HTML table. The steps involved in scraping the Mars temperature data site are as follows:

1. Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
2. Create a Beautiful Soup object to parse the HTML of the visited site.
3. Extract the rows of data from the HTML table and the column headers.
4. Assemble the scraped data into a Pandas DataFrame, ensuring the columns have the same headings as the table on the website.
5. Prepare the data for analysis by examining and modifying the data types if necessary.
6. Analyze the dataset using Pandas functions to answer questions about the Martian climate.

## Questions Analyzed in Part 2

The following questions are answered using the scraped Mars temperature data:

1. How many months exist on Mars?
2. How many Martian days' worth of data are there?
3. What are the coldest and warmest months on Mars at the location of the Curiosity rover?
4. Which months have the lowest and highest atmospheric pressure on Mars?
5. About how many terrestrial (Earth) days exist in a Martian year?

The answers to these questions are obtained by performing various calculations and visualizations using the Pandas and Matplotlib libraries.

---

Please make sure to install the required dependencies mentioned above before running the code. You can use package managers like pip or conda to install them.