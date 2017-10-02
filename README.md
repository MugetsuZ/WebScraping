# WebScraping
Web scraping in Python.

Team school project for the "Software Design and Architecture" class.

The goal is to fetch all [these bands](https://www.metal-archives.com/lists/SE) from the website and store them inside a database with the help of scraping and ORM libraries.


## Libraries used:
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [Requests](http://docs.python-requests.org/en/master/)
- [URLExtract](https://pypi.python.org/pypi/urlextract)
- [SQLAlchemy](https://www.sqlalchemy.org/)


## Team:

|Team Member  |GitHub   |
|:-:|:-:|
|Jaime Villarreal   |[jvillarreal7](https://github.com/jvillarreal7)   |
|Cuauhtémoc Martínez   |[CMAREQ](https://github.com/CMAREQ)   |
|Luis Carlos Estrada   |[--]   |
|Emilio Almazán   |[--]  |
|Georgina Valenzuela   |[--]  |


## Progress Log:

- Sep. 25, 2017: 
1. Extracted band URLs from the json response, could crawl through the first 500 entries to fetch each band profile.
2. Request loop fixed, it goes beyond the first DataTable page. Everything is saved in the local directory even though it's just for testing purposes.

- Sep. 26, 2017:
A unit demo was added.

- Sep. 28, 2017:
A very basic idea of ORM was implemented to the demo.

