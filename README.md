### Project Description

**Title: Web Scraping for Stock Information Extraction**

**Objective:**
The primary goal of this project was to develop a web scraping tool to extract and compile specific stock information from a financial website, particularly focusing on the hardware technology equipment sector. The extracted data was then cleaned and stored in a structured format for further analysis.

**Overview:**
In this project, I designed and implemented a web scraper using Python. The scraper was used to navigate a specified financial website, extract relevant stock information, and save it into a CSV file. The main focus was on gathering the product titles and NSE (National Stock Exchange) names of various companies listed under the hardware technology equipment sector.

**Key Components:**
1. **Libraries Used:**
   - **BeautifulSoup**: For parsing the HTML content of the web pages.
   - **Requests**: For making HTTP requests to fetch the web pages.
   - **Pandas**: For data manipulation and storage in a CSV file.
   - **Numpy**: For handling missing data.

2. **Process:**
   - **HTTP Requests**: Sent HTTP requests to the target URL to retrieve the HTML content of the web page.
   - **HTML Parsing**: Used BeautifulSoup to parse the HTML content and extract relevant links to individual stock pages.
   - **Data Extraction**: For each stock page, extracted the product title and NSE name using custom functions designed to handle potential missing data or changes in the HTML structure.
   - **Data Storage**: Compiled the extracted data into a Pandas DataFrame, handled missing values, and saved the clean data into a CSV file for further analysis.

**Skills Developed:**
1. **Web Scraping**: Gained expertise in using BeautifulSoup and Requests to extract and parse data from web pages.
2. **Data Cleaning**: Developed skills in handling missing data and ensuring the accuracy and completeness of the extracted information.
3. **Data Manipulation**: Used Pandas for organizing, cleaning, and storing data in a structured format.
4. **Problem Solving**: Enhanced problem-solving abilities by addressing challenges such as dynamic content handling and dealing with potential changes in web page structures.
5. **Python Programming**: Improved proficiency in Python, particularly in writing efficient and reusable code.

**Outcome:**
The project successfully scraped and compiled relevant stock information into a CSV file, providing a valuable dataset for financial analysis. This project not only demonstrated my ability to automate data collection but also showcased my skills in data cleaning, manipulation, and storage, making me adept at handling real-world data science challenges.
