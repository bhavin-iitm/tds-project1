# TDS Project 1 (3-pointer Overview for peers)
* I have scraped the data using 2 menthods, 1 is with directly working with the API and 2 using PyGithub python library, you can check TDS-Proj1-Scrape.ipynb for low level details and I found we can avoid lot of API intrecasies using the Python library but miss out on the wonderful design Github has adopted for API.
* The most interesting fact after the analysis is surely the language adoption and stargazers, Javascript is the most popular language against my earlier perception of Python, Java etc and second of all I found Pascal has the most stargazers which I believed is long gone, legacy language.
* My recommendation to the developers is that hone up your Javascript skills which seems the most relevant language as per the analysis and the usefulness of Javascript is beyond one's imagination, be it building interactive UI, debugging on the fly, web scraping and so much more so mastering Javascript will definitely add a lot to your resume.

# Repository Content Quick Glance
1. Scraped Data (a. users.csv and b. repositories.csv)
2. Python code for scraping (TDS-Proj1-Scrape.ipynb). This file contains 2 sections. 1st section contains data scraping using the bare APIs to understand the API design and its low level details. 2nd section contains data scraping using PyGithub library to understand the ease it brings after against bare API scraping.
3. Python code for Quiz analysis (TDS-Proj1-Quiz-Questions.ipynb). This file contains the questions along with the code to find out the answers.

# Cool references about Github APIs
1. https://docs.github.com/en/rest/using-the-rest-api/best-practices-for-using-the-rest-api?apiVersion=2022-11-28
2. https://docs.github.com/en/webhooks/about-webhooks
