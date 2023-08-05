# Flipkart Mobiles Data Scraper

This Python script scrapes mobile data from Flipkart's website and compiles it into a CSV file. The data includes product names, prices, ratings, and details. The script fetches data from multiple pages, combining them to create a comprehensive dataset for mobiles under 50000.

## Requirements
- Python 3.x
- BeautifulSoup (`pip install beautifulsoup4`)
- Pandas (`pip install pandas`)
- Requests (`pip install requests`)

## Usage
1. Clone the repository or download the script.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the script using `python flipkart_mobile_scraper.py`.
4. The scraped data will be saved in a CSV file named `Flipkart_Mobiles.csv`.

## Code Explanation
The script sends HTTP requests to Flipkart's mobile search pages (2 to 4) and fetches the HTML content using Requests. BeautifulSoup is used to parse the HTML and extract the desired data, including product names, prices, ratings, and details. The scraped data is then stored in lists and organized into a Pandas DataFrame. Finally, the DataFrame is saved to a CSV file.

## License
This project is licensed under the [MIT License](LICENSE).

## More Information and Documentation of the code is present in the WIKI Section
### Link: [WIKI](https://github.com/Chirag529/Flipkart_Mobile_Scrapping/wiki).
