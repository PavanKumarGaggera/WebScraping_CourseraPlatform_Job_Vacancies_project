# Web Scraping Project: Extracting Job Information from Coursera Careers Page

This Python web scraping project aims to extract job titles, departments, and locations from the Coursera Careers page.

## Project Overview

The project involves the following steps:

1. **Web Page Selection:** Identify the HTML structure of the Coursera Careers page.

2. **Scrape Job Information:** Implement logic to scrape job titles, departments, and locations from the page using web scraping tools.

3. **Data Extraction:** Extract the relevant information and store it for further analysis.

4. **CSV Export:** Save the extracted data to a CSV file for easy sharing and analysis.

## Usage

To run the script and obtain the job information:

1. **Install Required Libraries:**
    ```bash
    pip install requests beautifulsoup4
    ```

2. **Run the Script:**
    ```bash
    Web_Scrapping_Job_Vacancies.ipynb
    ```

   This will scrape the job information from the Coursera Careers page and save it to a CSV file.

## Code Structure

The main script is `scrape_coursera_jobs.py`, which includes:

- HTML structure identification.
- Web scraping logic using `requests` and `BeautifulSoup`.
- Data extraction and CSV export.

## Results

After running the script, the extracted job information will be saved in a CSV file for further analysis.

## Disclaimer

This project is intended for educational purposes only. Make sure to review and respect the terms of service of the website you are scraping.

Happy coding!
