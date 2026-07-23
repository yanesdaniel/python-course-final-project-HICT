# COVID-19 Data Crawler 🦠

Final project for the Huawei ICT Academy Python course.

A minimalist Python web scraper that extracts real-time COVID-19 statistics from [Worldometer](https://www.worldometers.info/coronavirus/), processes the data, and visualizes the impact across top countries.

## Features
- **Web Scraping:** Fetches live global COVID-19 data using `requests` and `BeautifulSoup`.
- **Data Wrangling:** Cleans and structures the raw HTML table into a robust `pandas` DataFrame.
- **Data Export:** Automatically exports the processed dataset to a local `covid19.csv` file.
- **Data Visualization:** Generates a bar chart of the top 10 countries by total cases using `matplotlib`.

## Prerequisites
Ensure you have Python 3 installed. You will need the following libraries:
- `requests`
- `beautifulsoup4`
- `numpy`
- `pandas`
- `matplotlib`

## Installation & Usage

1. **Clone the repository** or download the Jupyter Notebook file.
2. **Install dependencies** (it is recommended to use a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Notebook:** The `requirements.txt` file already includes Jupyter Lab. You can launch the environment directly from your terminal by running:
   ```bash
   jupyter lab
   ```
   Once the interface opens in your browser, select the notebook file and execute the cells sequentially to scrape the site, generate the `covid19.csv` file, and render the bar chart.
