# Property Scraper

This Python script scrapes property data from Property24.com and saves it as a CSV file. The script fetches information such as title, price, area, and location of properties listed for sale or rent.

## How to Use

- Download the Property24.ipynb on your local machine or upload to Google Colab / Kaggle.
- Run all the cell sand in the final cell just input the two arguments. 
- scraper = PropertyScraper("for-rent", "for_rent.csv")

### Prerequisites
- Python 3.x installed on your system
- Required libraries: `requests`, `BeautifulSoup`, `pandas`, `tqdm`

You can install the required libraries using pip:
```bash
pip install requests beautifulsoup4 pandas tqdm
