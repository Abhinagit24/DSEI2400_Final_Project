# Quest Query - An Advanced Web Scraping Tool

This is a data engineering project, where I worked with another student in developing a web browser that automates the processes of searching for urls for a given 'search term' and outputs a table which holds a list of urls that are displayed in the order of their relevance related to the search term, gathered from multiple web browsers. The browser is built on python using Selenium, a python package used for automation of web browser interactions. The output table is stored in MySQL database. 

- **Extract** the search data using Selenium
- **Transform** the data to usable format using regular expression and OCR
- **Load** the transformed data to MySQL database using mysql connector and sqlalchemy libraries

### Tools used 
- Selenium
- Os
- cv2
- pytesseract
- nltk, re
- PyQt5
- mysql.connector
- sqlalchemy


