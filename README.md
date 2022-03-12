# Movie Webscraper
Selenium web scraper for real-time data at Maoyan movies with corresponding data completion from search at Douban. With https proxy rotation, custom digit font recognition using pytesseract, to bypass anti-scraping measures at Maoyan. 

## Codebase structure
`logs/`: Folder storing data scraped from two website, grouped by timestamp. 
`logs/development`: Sample data gathered during development.
`scraper.py`: Combined python script for automation, outputs csv to corresponding folder in `logs/`.
`Scraper with Tesseract.ipynb`: Development process with notes and explanation of how each part functions. 
`Automation Testing.ipynb`: Combined code to copy and paste to the scraper.py, safe to delete. 
`legacy/`: Nothing intereting here, just junk I felt like keeping, safe to delete. 
`temp/`: Folder storing fonts data and fonts url during scraping, generated every scrape. Safe to delete. 
## Set up
Simply run `pip install -r requirements.txt` to install all requirements, 
Then run `python scraper.py` at root folder. 
