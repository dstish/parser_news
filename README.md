# The parser of the site "Pravda Severa"
This is my university project.

Link: https://pravdasevera.ru/

## 🛠 Which modules are connected
### Requests
The requests module allows you to send HTTP requests using Python.
### csv
The csv module implements classes for reading and writing tabular data in CSV format. This allowed me to record the result in csv format.
### BeautifulSoup
Python package for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.
### datetime
The datetime module supplies classes for manipulating dates and times

## 🚀 How it works
First, the get_urls() function is launched, which collects links to all articles from the site into a text document url_list.txt. Next, the parse() function is launched, which passes through each link from the text document url_list.txt and selects each html element of the page, and later writes it to a csv file.
