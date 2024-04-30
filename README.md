# Zillow Real Estate Scraper: Property Data Scraping & Excel Export

**Project Duration**: 1 days

**Technologies Used**: Python for web scraping, Excel for data presentation

**Website**: [Zillow](https://www.zillow.com/il/sold/?searchQueryState=%7B%22isMapVisible%22%3Atrue%2C%22mapBounds%22%3A%7B%22north%22%3A43.452113556104415%2C%22south%22%3A36.24337847292101%2C%22east%22%3A-78.8899200859375%2C%22west%22%3A-100.8845489921875%7D%2C%22filterState%22%3A%7B%22ah%22%3A%7B%22value%22%3Atrue%7D%2C%22fsba%22%3A%7B%22value%22%3Afalse%7D%2C%22fsbo%22%3A%7B%22value%22%3Afalse%7D%2C%22nc%22%3A%7B%22value%22%3Afalse%7D%2C%22cmsn%22%3A%7B%22value%22%3Afalse%7D%2C%22auc%22%3A%7B%22value%22%3Afalse%7D%2C%22fore%22%3A%7B%22value%22%3Afalse%7D%2C%22rs%22%3A%7B%22value%22%3Atrue%7D%2C%22sort%22%3A%7B%22value%22%3A%22globalrelevanceex%22%7D%7D%2C%22isListVisible%22%3Atrue%2C%22mapZoom%22%3A7%2C%22regionSelection%22%3A%5B%7B%22regionId%22%3A21%2C%22regionType%22%3A2%7D%5D%2C%22pagination%22%3A%7B%7D%7D)

**Outcome**: Extracted properties sold in Illinois, with a total of [620,822 records](https://docs.google.com/spreadsheets/d/1w0UluS-dUlCvtOiazcvrhZJ6ajYSXlILp8PuV-I_9ik).

**1. Client Request:**
The client requested a program to scrape data specifically for sold properties from Zillow. The focus was on properties in Granite City, East Saint Louis, and Decatur, all in Illinois.

**2. Implementation Method:**
Overcame the Zillow API's restriction of 41 records per request by utilizing map points to increase data retrieval capacity up to 500 records at a time, significantly enhancing data scraping efficiency and reducing security blocks.

**3. Results Obtained:**
Successfully delivered a comprehensive dataset of 620,822 sold properties, organized neatly in Excel for immediate use. Additionally, provided the client with the Python script, enabling them to extract new data whenever needed, ensuring long-term utility and flexibility in data handling.

## Data fields to be extracted from Zillow website.
[![Zillow](https://github.com/TechBeme/Zillow/assets/101749351/da57402d-2aed-4071-b179-0b348c1be2fb)](https://www.zillow.com/il/sold/?searchQueryState=%7B%22isMapVisible%22%3Atrue%2C%22mapBounds%22%3A%7B%22north%22%3A43.452113556104415%2C%22south%22%3A36.24337847292101%2C%22east%22%3A-78.8899200859375%2C%22west%22%3A-100.8845489921875%7D%2C%22filterState%22%3A%7B%22ah%22%3A%7B%22value%22%3Atrue%7D%2C%22fsba%22%3A%7B%22value%22%3Afalse%7D%2C%22fsbo%22%3A%7B%22value%22%3Afalse%7D%2C%22nc%22%3A%7B%22value%22%3Afalse%7D%2C%22cmsn%22%3A%7B%22value%22%3Afalse%7D%2C%22auc%22%3A%7B%22value%22%3Afalse%7D%2C%22fore%22%3A%7B%22value%22%3Afalse%7D%2C%22rs%22%3A%7B%22value%22%3Atrue%7D%2C%22sort%22%3A%7B%22value%22%3A%22globalrelevanceex%22%7D%7D%2C%22isListVisible%22%3Atrue%2C%22mapZoom%22%3A7%2C%22regionSelection%22%3A%5B%7B%22regionId%22%3A21%2C%22regionType%22%3A2%7D%5D%2C%22pagination%22%3A%7B%7D%7D)

## Sample output table with the extracted data.
[![sample](https://github.com/TechBeme/Zillow/assets/101749351/b44c4cd3-1c1f-403b-9e4f-d7df0ce42177)](https://docs.google.com/spreadsheets/d/1w0UluS-dUlCvtOiazcvrhZJ6ajYSXlILp8PuV-I_9ik)
