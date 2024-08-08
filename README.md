# Property Scraper

This Python script scrapes property data from Property24.com and saves it as a CSV file. The script fetches information such as title, price, area, and location of properties listed for sale or rent.

## How to Use

When you run the scraper, the values for transaction type can be either "for-rent" or "for-sale"
file name can be anything of your choice.
scraper = PropertyScraper("for-rent", "for_rent.csv")

### Prerequisites
- Python 3.x installed on your system
- Required libraries: `requests`, `BeautifulSoup`, `pandas`, `tqdm`

You can install the required libraries using pip:
```bash
pip install requests beautifulsoup4 pandas tqdm
