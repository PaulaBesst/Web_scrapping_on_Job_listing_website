# Web Scraping Project

A Python-based web scraping project focused on extracting job listings from the "Jobs in Ghana" website using BeautifulSoup and Requests libraries. This project demonstrates both basic HTML parsing and dynamic website scraping techniques.

## Features

- **Basic Web Scraping**: Parse local HTML files to extract and save data
- **Dynamic Website Scraping**: Fetch job categories and listings from the Jobs in Ghana website
- **CSV Export**: Store extracted job data in CSV format for easy analysis and reuse
- **Interactive Input**: Allow users to select specific job categories to scrape
- **Error Handling**: Include basic checks for missing data and invalid inputs

## Project Structure

### 1. Simple HTML Scraping
Parses a local HTML file to extract and save data into a CSV file.

### 2. Jobs in Ghana Website Scraping
- Fetch job categories dynamically
- Allow users to select a category and scrape listings
- Save job details including title, company, location, salary, and expiry date into a CSV file

### 3. Function Optimization
Encapsulates scraping logic into reusable functions for better code organization.

## Challenges Faced

- **Data Consistency**: Inconsistent formats in the salary column require post-extraction data cleaning
- **Dynamic Elements**: Dynamic website elements necessitated careful inspection of HTML structure for reliable scraping

## Requirements

- Python 3.x
- Required libraries:
  - `BeautifulSoup4`
  - `requests`
  - `csv` (built-in)
  - `os` (built-in)

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/Web_Scraping_Project.git
   cd Web_Scraping_Project
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the project:**
   ```bash
   python Web_Scrapping_Project.ipynb
   ```
   *Note: If using Jupyter Notebook, open the .ipynb file in Jupyter and run the cells*

4. **Follow the interactive prompts** to select job categories and initiate scraping.

## Output

Job listings and their details are automatically saved in a CSV file (`jobsin_gh_scrape.csv`) in the project directory. The CSV contains structured data including:
- Job title
- Company name
- Location
- Salary information
- Expiry date

## Usage Example

The scraper will prompt you to:
1. Select from available job categories
2. Choose specific listings to scrape
3. Automatically save results to CSV format

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## Acknowledgements

- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Requests Documentation](https://docs.python-requests.org/)

---

**Note**: This project is for educational purposes. Please ensure you comply with the website's robots.txt and terms of service when scraping.

⭐ **If you found this project helpful, please give it a star!** ⭐
