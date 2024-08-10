# Vervebridge-Flipkart_Web-Scraping-Project
Vervebridge Web Scraping Project:  Python tool for extracting product info from Flipkart, including titles, prices, ratings, and reviews. Handles pagination and retries. Outputs data to CSV.


# Vervebridge Web Scraping Project

## Description
This project involves web scraping data from Flipkart to extract product details such as title, price, rating, and number of reviews. The scraper is designed to handle multiple pages of search results and save the data into a CSV file.

## Features
- Scrapes product titles, prices, ratings, and reviews.
- Handles multiple pages of search results.
- Logs errors and retries failed requests.
- Saves the extracted data into a CSV file for easy analysis.

## Requirements
- Python 3.x
- Required Python libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `numpy`

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Vervebridge/Vervebridge-Web-Scraping-Project.git
   cd Vervebridge-Web-Scraping-Project


2.  Install Dependencies:
Create a virtual environment and install the required libraries:
bash
    python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt



3. Usage
Run the Scraper:
bash

python scraper.py
This will start the scraping process, extract data from Flipkart, and save it to flipkart_data.csv


Configuration
You can adjust the number of pages to scrape by modifying the num_pages variable in scraper.py. The BASE_URL can also be updated to scrape different product categories.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
We welcome contributions to improve this project. To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push the branch (git push origin feature-branch).
Create a pull request.



Acknowledgements
BeautifulSoup - For web scraping capabilities.
Requests - For handling HTTP requests.
Pandas - For data manipulation and saving to CSV.
NumPy - For numerical operations.


Contact
For any questions or feedback, please contact vinuthanaik550@gmail.com




### Summary of Key Sections

- **Description**: Provides an overview of the project's purpose and functionality.
- **Features**: Lists the main features and capabilities of the scraper.
- **Requirements**: Specifies the software and libraries needed to run the project.
- **Setup**: Instructions for cloning the repository and setting up the development environment.
- **Usage**: How to execute the script to perform web scraping.
- **Configuration**: Information on how to modify the script settings.
- **License**: Details about the project's license.
- **Contributing**: Guidelines for contributing to the project.
- **Contact**: How to get in touch for questions or feedback.
- **Acknowledgements**: Credits to the tools and libraries used in the project.



