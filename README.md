# BidAssist
Project Description
BidAssist Scraper is a Python-based web scraping project that automates the extraction of tender data from the BidAssist platform. The primary purpose of this project is to collect up-to-date information on government tenders across various Indian states and save the data in a structured format for further analysis or integration into other platforms.

The data extracted includes:
Tender titles
Locations
Departments
Estimated values
Due dates
URLs to individual tender listings
The project uses the following technologies:
Requests: for HTTP operations.
BeautifulSoup: for HTML parsing.
Pandas: for data manipulation and export to CSV.
JSON: to handle structured data.
Time: to manage delays in scraping to avoid overloading the server.

Features:
Scrapes tender listings by state.
Automatically paginates through available tenders.
Extracts and stores structured data (like title, value, department, due date).
Saves the result into a .csv file for offline analysis.
Handles missing or malformed data gracefully.

How to Run:
1. Clone the repository:
   git clone https://github.com/yourusername/bidassist-scraper.git
   cd bidassist-scraper
2. Set up your Python environment:
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
3. Run the Jupyter Notebook:
   jupyter notebook Bidassist.ipynb

Dependencies:
Install dependencies using the provided requirements.txt or manually install:
pip install requests beautifulsoup4 pandas

Output
The script generates a CSV file with the following columns:
Title
Location
Department
Estimated Value
Due Date
Tender URL
The CSV file can be opened in Excel or imported into data analysis platforms.

Contact
For suggestions or contributions, feel free to raise an issue or submit a pull request.
