# WikipideaWebscrapping

## Project Overview

`WikipideaWebscrapping` is a project that involves scraping data from Wikipedia and processing it into structured datasets. The project includes a Jupyter Notebook for web scraping practices and several CSV files containing the scraped data.

## Contents

- `Practice_Sheet.ipynb`: A Jupyter Notebook demonstrating web scraping techniques using Python libraries such as BeautifulSoup and requests.
- `Population.csv`: A dataset containing population data scraped from Wikipedia.
- `table2.csv`: Another dataset obtained from Wikipedia.
- `table3.csv`: Additional data extracted from Wikipedia.

## Getting Started

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python packages (see below)

### Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/monali0212/WikipideaWebscrapping.git
   cd WikipideaWebscrapping
2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    If requirements.txt is not provided, install the necessary packages manually:
    ```sh
    pip install requests beautifulsoup4 pandas jupyter

### Running the Notebook

1.**Start Jupyter Notebook**:
   ```sh
   jupyter notebook
2. **Open the Practice_Sheet.ipynb**:
  Navigate to the notebook in the Jupyter interface and open it to run the cells and see the web scraping process in action.

### Project Structure
    WikipideaWebscrapping/
  ├── Practice_Sheet.ipynb
  ├── Population.csv
  ├── table2.csv
  ├── table3.csv
  ├── README.md
  └── requirements.txt

### Usage
**Web Scraping**: The Jupyter Notebook Practice_Sheet.ipynb demonstrates how to scrape data from Wikipedia using Python.
**Data Analysis**: The CSV files (Population.csv, table2.csv, table3.csv) contain the scraped data that can be used for further data analysis and visualization.

### Acknowledgements
   The BeautifulSoup and requests libraries for web scraping.
   Wikipedia for providing the data.

