# Timesjobs-scraper
A Python script that scrapes job listings from TimesJobs.com and saves them to text files based on a specified skill filter.

Features

Scrapes job listings from TimesJobs.com
Filters job listings based on a specified skill
Saves job listings to text files
Runs continuously, scraping new job listings every 10 minutes

Requirements
Python 3.x
BeautifulSoup
requests
time

How it Works
The script sends a GET request to TimesJobs.com to retrieve the HTML content of the job listings page.
The script uses BeautifulSoup to parse the HTML content and extract the job listings.
The script filters the job listings based on the specified skill and saves them to text files.
The script runs continuously, scraping new job listings every 10 minutes.

Acknowledgments
TimesJobs.com for providing the job listings data.
BeautifulSoup and requests for providing the libraries used in this project.
