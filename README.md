# WebScrapingMovies
Practicing BeautifulSoup

**Installing Beautiful Soup:**
You can install Beautiful Soup using pip:
_pip install beautifulsoup4_

**Importing**

_from bs4 import BeautifulSoup
import requests_

**Fetching and Parsing HTML:**
You've learned to fetch and parse HTML content using lxml and html.parser from a web page using Beautiful Soup:
___________________________
response = requests.get(url)
soup = BeautifulSoup(response.content, 'html.parser')
**OR**
response = requests.get(url)
soup = BeautifulSoup(response.content, 'lxml')

___________________________
**Finding Elements:**
You've learned how to navigate the parse tree using methods like .parent, .contents, .next_sibling, and .previous_sibling

text = element.text
attribute = element['attribute_name']
___________________________

**Searching with Regular Expressions:**
Learn about Using regular Expression `re` library.

___________________________

**Pivoting Data with Pandas:**
You've used the pandas library to create DataFrames from extracted data and manipulate it.

___________________________
**Looping Through Elements:**
You've iterated through elements and performed actions based on specific conditions.

___________________________
**Web Scraping Patterns:**
You've learned patterns for web scraping, including searching for specific elements based on tags, classes, and attributes.

___________________________
**Selective Extraction:**
You've selectively extracted data based on your requirements, including excluding specific values.

___________________________
**Loops with Ranges:**
You've used loops with ranges to iterate through specific indices and retrieve data with directly arange start end and steps.

___________________________

**Creating Lists of Lists:**
You've learned how to create lists of lists by extending or concatenating multiple lists.

