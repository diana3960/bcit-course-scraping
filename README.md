# bcit-course-scraping
Assignment 4 – Scraping Unstructured Data (BCIT Program Page)
Project Overview

For this assignment, I chose to scrape data from the BCIT Business Information Technology Management (BITMAN) program webpage. The goal was to work with unstructured HTML data and turn it into something structured and usable.

Using Python, I pulled the webpage content, parsed the HTML, and extracted relevant text. I then organized the data into a table format and saved it as a CSV file.

What This Project Does

- Connects to the BCIT BITMAN program webpage

- Pulls the raw HTML content

- Uses BeautifulSoup to read and parse the HTML

- Extracts paragraph text

- Converts the data into a structured DataFrame

- Saves the final result as a CSV file

Tools Used

- Python

- requests

- BeautifulSoup (bs4)

- pandas

Data Source

- BCIT Business Information Technology Management Diploma Program:

- https://www.bcit.ca/programs/business-information-technology-management-diploma-full-time-5500dipma/

Output

The cleaned and structured data is saved in:

results/bcit_program_data.csv

AI Use Statement

I used an AI coding assistant to help guide parts of the scraping process and troubleshoot errors. I made sure to test the code myself and understand what each section was doing before submitting.
