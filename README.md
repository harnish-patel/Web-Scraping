# Scraping Data from Wikipedia

This project involves scraping data from Wikipedia to create a dataset of the largest companies in the United States by revenue. The data is extracted from the Wikipedia page: [List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue).

## Overview

### Technologies Used
- Python
- BeautifulSoup for web scraping
- Requests for making HTTP requests
- Pandas for data manipulation

### Project Structure

- **Jupyter Notebook**: The project is implemented as a Jupyter Notebook for interactive development and documentation.

- **Web Scraping**: The BeautifulSoup library is used to scrape data from the Wikipedia page. The script makes an HTTP request to the Wikipedia page, extracts the relevant table, and retrieves information such as company names, industry, revenue, etc.

- **Pandas DataFrame**: The extracted data is organized and stored in a Pandas DataFrame. The DataFrame is structured to include columns such as Rank, Name, Industry, Revenue, Revenue growth, Employees, and Headquarters.

## Steps

1. **Scraping Wikipedia Page**: The script fetches the HTML content of the Wikipedia page and uses BeautifulSoup to parse the HTML.

2. **Extracting Headers**: The script identifies and extracts the headers of the table.

3. **Creating Pandas DataFrame**: A Pandas DataFrame is created with the extracted headers.

   
4. **Fetching and Populating Data**: The script iterates through the rows of the table, extracts the data, and populates the Pandas DataFrame.
