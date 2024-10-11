Web Scraping Project: Books to Scrape
=====================================

🚀 Project Overview
-------------------

This project aims to scrape book data from the **Books to Scrape** website, a practice site for web scraping techniques. The scraper collects essential information such as book titles, prices, stock availability, and links, storing this data in Excel and CSV formats for easy access and analysis.

📚 Features
-----------

*   **Multi-Page Scraping**: Automatically navigates through multiple pages to gather data.
*   **Data Structuring**: Extracts and organizes data into a structured format.
*   **File Outputs**: Saves the extracted data in both Excel and CSV formats.
*   **Proxy Support**: Configurable proxy settings for enhanced scraping capabilities.

🔧 Technologies Used
--------------------

*   **Python**: The programming language utilized for scripting the web scraper.
*   **Libraries**:
    *   **Requests**: For making HTTP requests to fetch webpage content.
    *   **Beautiful Soup**: For parsing HTML content and extracting relevant data.
    *   **Pandas**: For organizing data into a DataFrame and saving it in various formats.

🌐 Target URL
-------------

*   **Base URL**: https://books.toscrape.com

🛠️ Getting Started
-------------------

### Prerequisites

Make sure you have Python installed on your machine. Install the required libraries with the following command:


`pip install requests beautifulsoup4 pandas openpyxl` 

### Installation

1.  **Clone the Repository**:
    
   
    
    git clone https://github.com/Abhijaata/Web-Scrapping.git
    
2.  **Navigate to the Project Directory**:
    
   
    
    `cd Web-Scrapping` 
    

### Configuration

*   Open the Python script or Jupyter Notebook containing the web scraping code.
*   Update the proxy settings with your username and password.

### Running the Scraper

*   Execute the script to start the scraping process. The scraper will navigate through the pages, extract book data, and save it to files.

📂 Output
---------

After running the script, the book data will be saved in:

*   `books.xlsx`: Excel file containing the scraped data.
*   `books.csv`: CSV file for easy access and analysis.

🤝 Contributing
---------------

Contributions are welcome! If you have ideas for enhancements or additional features, please feel free to submit an issue or pull request.

📝 License
----------

This project is licensed under the MIT License.

🙏 Acknowledgments
------------------

*   Beautiful Soup Documentation
*   Requests Documentation
*   Pandas Documentation
