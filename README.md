# WebScrapping
🕸️ Web Scraping: Largest U.S. Companies by Revenue
Overview
This project focuses on web scraping the Wikipedia page listing the largest companies in the United States by revenue. The project is implemented in two different Google Colab notebooks—one using BeautifulSoup and the other using Pandas. Each approach demonstrates how to extract and process tabular data from the webpage.

Project Structure

1. Companies_webscrapping_beautifulsoup.ipynb:

Uses BeautifulSoup for scraping the table.
Offers more granular control over the scraping process.
Multiple lines of code for parsing HTML, finding the table, and cleaning the data.

2. Companies_webscrapping_pandas.ipynb:

Uses Pandas for scraping the table.
One-line solution for directly extracting tables from the webpage.
Simple, efficient, and ideal for structured HTML tables.
Key Differences Between BeautifulSoup and Pandas
Code Simplicity:

Pandas: Requires just one line of code to scrape the table, making it very straightforward.
BeautifulSoup: Requires multiple steps and lines of code for parsing and data extraction.
Flexibility:

BeautifulSoup: More flexible, allowing for detailed control over how data is extracted and parsed. Ideal for complex or irregular HTML structures.
Pandas: Best suited for well-structured HTML tables but less flexible when dealing with non-tabular data.
Ease of Use:

Pandas: Easier to use, especially for those familiar with data analysis in Pandas.
BeautifulSoup: Requires a deeper understanding of HTML structure and parsing techniques.

Run the Notebooks:

Open Companies_webscrapping_beautifulsoup.ipynb to see how to scrape the data using BeautifulSoup.
Open Companies_webscrapping_pandas.ipynb to see how to scrape the data using Pandas.
Compare the Approaches:

Review the steps in each notebook to understand the differences in implementation and output.


Conclusion
This project highlights the differences between using BeautifulSoup and Pandas for web scraping. Whether you need the flexibility of BeautifulSoup or the simplicity of Pandas, these notebooks provide a clear comparison to help you choose the right tool for your task.
