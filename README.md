# Challenge-11

# Mars News Scraping Project

This project scrapes the latest news articles from the Mars News website using Python, Splinter, and BeautifulSoup. The script extracts the titles and preview text of the news articles and stores them in a structured format for further use or analysis.

## Table of Contents

- [Overview](#overview)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Output](#output)
- [Troubleshooting](#troubleshooting)

## Overview

The Mars News Scraping script automates the process of visiting the Mars News website, extracting the latest news article titles and preview texts, and storing the results in a Python data structure. Optionally, the data can be saved to a JSON file for easy sharing or further analysis.

## Setup Instructions

Follow these steps to set up the project and run the scraping script:

1. **Clone the Repository**: Clone this project repository to your local machine using the command:
   ```bash
   git clone <repository-url>
   ```
   
2. **Install Dependencies**: Ensure that Python is installed on your machine. Then, install the required Python packages by running:
   ```bash
   pip install splinter selenium beautifulsoup4
   ```

3. **Download ChromeDriver**: 
   - Download ChromeDriver from the [official site](https://sites.google.com/chromium.org/driver/) matching your installed version of Chrome.
   - Place the ChromeDriver executable in a directory that is included in your system’s PATH, or specify the path directly in the script.

## Usage

1. Open the Jupyter Notebook `part_1_mars_news.ipynb` or run the Python script directly.
   
2. Update the `executable_path` in the script with the correct path to your ChromeDriver if needed.

3. Run the script. The script will:
   - Visit the Mars News website.
   - Extract the titles and preview texts of the latest articles.
   - Store the results in a list of dictionaries.

4. Optionally, the data can be saved to a JSON file named `mars_news.json` for easy sharing.

## Dependencies

The following dependencies are required to run the scraping script:

- Python 3.x
- Splinter
- Selenium
- BeautifulSoup4

Install these dependencies using the following command:

```bash
pip install splinter selenium beautifulsoup4
```

## Output

- The script outputs a list of dictionaries, each containing a title and preview text of a Mars news article.
- Sample Output:
  ```python
  [
      {
          "title": "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
          "preview": "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."
      },
      ...
  ]
  ```
- The data can also be saved to a JSON file named `mars_news.json`.

## Troubleshooting

- **ModuleNotFoundError**: Ensure all dependencies are installed using the provided command.
- **ChromeDriver Issues**: Ensure ChromeDriver matches the installed version of Chrome and is accessible via the system’s PATH.

For any further assistance, please refer to the official documentation of Splinter, Selenium, and BeautifulSoup.





# Mars Weather Data Analysis

## Overview

This project involves scraping and analyzing Mars weather data from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) to explore temperature and atmospheric pressure patterns on Mars.

## Steps

1. **Scraping**: Data is scraped from the website using BeautifulSoup and stored in a Pandas DataFrame.
2. **Data Preparation**: The data is cleaned and converted to appropriate types (`datetime`, `int`, `float`) for analysis.
3. **Analysis**:
   - Identified the number of months and Martian days in the dataset.
   - Analyzed the coldest and warmest months by average minimum temperature.
   - Examined months with the lowest and highest atmospheric pressure.
   - Estimated the number of Earth days in a Martian year based on seasonal temperature patterns.

## How to Run

1. Download the Jupyter Notebook (`part_2_mars_weather.ipynb`).
2. Install required libraries: `requests`, `beautifulsoup4`, `pandas`, `matplotlib`.
3. Run the notebook cells to perform the analysis.




