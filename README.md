# Web Scraping and PDF Generation

A Python-based project that scrapes data from three different websites using BeautifulSoup and Selenium, processes and cleans the data, and then generates PDFs based on the scraped information.

## Description

This project automates the process of scraping data from multiple websites, cleaning it, and generating well-structured PDF reports. It utilizes BeautifulSoup and Selenium for web scraping, Pandas for data cleaning, and ReportLab and FPDF to generate PDFs.

### Features:
- **Web Scraping**: Scrapes data from 3 different websites.
- **Data Cleaning**: Extracted data is cleaned and structured for analysis.
- **PDF Generation**: Converts the cleaned data into PDF documents for easy sharing and reporting.
- **Interactive Scraping**: Option to scrape data from user-specified URLs.

### Differentiating Factors:
- **Multi-Website Scraping**: The ability to scrape from multiple sites in one project.
- **Automated PDF Reports**: The project can automatically generate PDF reports based on the scraped data.
- **Data Cleaning**: Data is cleaned and processed before being saved, ensuring only relevant information is included in the PDFs.

## Badges

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Installation

To set up the `Web-Scraping-and-PDF-Generation` project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/shhushann/Web-Scraping-and-PDF-Generation.git
    cd Web-Scraping-and-PDF-Generation
    ```

2. Create a virtual environment (recommended):
    ```bash
    python3 -m venv venv
    ```

    Activate the virtual environment:
    - **Windows:**
        ```bash
        venv\Scripts\activate
        ```
    - **macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the script:
    ```bash
    python scraper.py
    ```

This will start the web scraping and PDF generation process, saving the results to PDF files.

## Usage

### Input
- **URLs**: Provide the URLs of the websites you wish to scrape.
- **Scraping Options**: Choose the data fields you want to scrape (if applicable).

### Output
The script will generate:
- **PDF Files**: PDFs containing the cleaned data scraped from the websites.
- **Logs**: Console logs showing the scraping process and status.

### Example Input:
- **URLs**: `https://example.com`, `https://another-site.com`
- **Fields**: Title, Description, Price (if available)

### Example Output:
- **Generated PDF**: A PDF report with the cleaned data from the scraped websites.
  
## Support

If you encounter any issues, feel free to reach out via the following:
- [Create an issue on GitHub](https://github.com/shhushann/Web-Scraping-and-PDF-Generation/issues)

## Roadmap

- **Future Releases**:
    - Expand scraping capabilities to more websites.
    - Improve PDF formatting with more advanced templates.
    - Automate the process of scraping on a schedule.

## Contributing

Contributions are welcome! If you would like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your forked repository (`git push origin feature-branch`).
5. Open a pull request.

Please ensure that your contributions do not break any existing functionality and that all tests pass.

## Authors and Acknowledgments

- **Shushan Gevorgyan** - Creator and Lead Developer
- **BeautifulSoup** - Web scraping library
- **Selenium** - For handling dynamic content on websites
- **Pandas** - Data cleaning and processing
- **ReportLab/FPDF** - PDF generation libraries

## Project Status

This project is actively maintained and open for contributions. Feel free to submit issues or pull requests for improvements.
