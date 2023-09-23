# RateMyProfessor.com-Web-Scraper
A Python script that uses Selenium to scrape all professor ratings from RateMyProfessor.com provided a unique school ID.

## Usage
Either set a unique school id (sid) for RateMyProfessor.com or pass it as an argument when running the script. The script will then scrape all professor ratings from the school and save them to a CSV file.

From the project directory, run `python3 rmp_scrape/fetch.py -s 1256` to scrape all professor ratings from the University of Wisconsin-Madison. The CSV file will be saved to the project directory in the `static_data/<school_name>_professors.csv` file. There appears to be a bug limiting the number of
professors that can be scraped from a school, there are plenty of long hanging fruit to fix this and improve the script for anyone who wants to contribute.