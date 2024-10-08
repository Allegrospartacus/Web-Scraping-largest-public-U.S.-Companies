# Web-Scraping-largest-public-U.S.-Companies
This project involves scraping data from Wikipedia to extract information about the largest public companies in the United States by revenue. The data is processed using Pandas and then saved as a CSV file for further analysis.

**Project Description**
Using Python and the BeautifulSoup library, this script scrapes a table containing a list of the largest public companies in the U.S. by revenue from Wikipedia. 
The dataset scraped includes columns such as Rank, Company, Industry, Revenue, and more.

**The process includes**

Sending an HTTP request to the Wikipedia page.

Parsing the page's HTML to locate the table containing the desired data.

Cleaning the table's data and storing it in a Pandas DataFrame.

Exporting the final DataFrame to a CSV file.


**Website Source** https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue

**Key Python Libraries Used**

BeautifulSoup: For parsing and navigating the HTML structure.
Pandas: For data cleaning and manipulation.
Requests: For sending HTTP requests to fetch the webpage.

**How It Works**

Scraping the Table: The script locates and extracts the first table from the Wikipedia page, which contains a list of the largest public companies by revenue.

Cleaning Data: It then processes the table by removing unwanted characters and unnecessary white spaces from the data.

Storing the Data: The clean data is converted into a Pandas DataFrame, which is further processed and saved to a CSV file.

**Output**
The script generates a CSV file named largest_public_companies.csv containing the scraped data. You can use this dataset for further data cleaning & analysis.

