# G2Crowd_scrapper
 
 G2Crowd Web Scraper
This is a web scraper that extracts company information from G2Crowd pages and saves the data in a JSON file.

Installation
Clone the repository:
shell
Copy code
git clone https://github.com/your-username/g2crowd-web-scraper.git
Navigate to the project directory:
shell
Copy code
cd g2crowd-web-scraper
Install the required dependencies using pip:
shell
Copy code
pip install playwright
Usage
Prepare the CSV file:

Use the CSV file generator.

Run the scraper:

shell
Copy code
python scraper.py
Output:

The script will launch a Chromium browser and start scraping the G2Crowd pages one by one.
The company information, including the company name, rating, and reviews count, will be extracted from each page.
The scraped data will be saved in a JSON file named g2crowd_data.json.
The JSON file will include an object for each URL containing the company information.
Check the output:

After the script finishes running, you can find the JSON file g2crowd_data.json in the project directory.
Open the JSON file to view the scraped company information.

Customize the Scraper
You can customize the scraper by modifying the locator strategies in the code.
