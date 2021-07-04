# WebScraping

Web Scraping has many names, such as Web Harvesting, Screen Scraping, and others. It is a method of extracting large quantities of data from websites and storing it at a particular location (a local file in your computer or a database in a table). 

In data science, to do anything, you need to have data at hand. To get that data, you’ll need to research the required sources, and web scraping helps you. Web scraping collects and categorizes all the required data in one accessible location. Researching with a single, convenient location is much more feasible and more comfortable than searching for everything one-by-one.

So I used BeautifulSoup, Request library and Selenium to scrape the data from some commonly known websites and collected some useful datasets.

# Request 

The requests module allows you to send HTTP requests using Python.The HTTP request returns a Response Object with all the response data (content, encoding, status, etc).

### Installinge Requests Module
#### >pip install requests

### Importing Requests Library
#### import requests
#### source = requests.get(url)

# BeautifulSoup

BeautifulSoup is used to parse the HTTP returned response object in a tree like structure so that we can extract required data from the response object easily.

### Installinge BeautifulSoup Module
#### >pip install beautifulsoup4

### Importing BeautifulSoup
#### from bs4 import BeautifulSoup as bs
#### soup = bs(source.content)

