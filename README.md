### Objective:
Collect data from VPBank's "Branch and ATM" page to build a dataset including branch names, addresses, service types, GPS coordinates and phone numbers. Crawling dynamic data containing JavaScript. Save data to .csv file

### Techniques & techniques used:
- Python
- undetected_chromedriver (running anti-bot browser)
- BeautifulSoup (parsing HTML)
- Pandas (creating and saving data)

### Results:
- Successfully crawling dozens of VPBank's transaction points and ATMs.
- Collecting information fields such as: name, type (ATM/Branch), address, phone, latitude/longitude.
- Create a Vpbank.csv file containing clean data, which can be used for further analysis, etc.
