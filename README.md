# Web Scraping Challenge

This project provides an analysis of data related to Mars, using Python and Jupyter Notebooks. It is divided into two parts: analyzing Mars news articles and exploring Mars weather data.

## Project Structure

### Files

1. **`part_1_mars_news.ipynb`**
   - Description: A Jupyter Notebook for analyzing the Mars news data. Key features include:
     - Extracting and displaying titles and previews.
     - Performing basic text analysis on the news content.

2. **`part_2_mars_weather.ipynb`**
   - Description: A Jupyter Notebook focused on analyzing the Martian weather dataset. Key features include:
     - Visualization of temperature and pressure trends.
     - Statistical summaries and insights into Mars' atmospheric conditions.
    

Outputs Folder:

1. **`mars_news.json`**
   - Description: A JSON file containing Mars-related news articles. Each entry includes:
     - `title`: The title of the article.
     - `preview`: A short summary or preview of the article.
   - Source: NASA's Mars exploration news.

2. **`mars_weather.csv`**
   - Description: A CSV file with data on Martian weather conditions. Key columns include:
     - `terrestrial_date`: Earth date of the observation.
     - `sol`: Martian sol (day).
     - `min_temp` and `max_temp`: Minimum and maximum temperatures on Mars.
     - `pressure`: Atmospheric pressure on Mars.
   - Source: Mars weather datasets from NASA.

### Requirements

- **Python Libraries:**
  - `pandas`: For data manipulation and analysis.
  - `matplotlib` and `seaborn`: For data visualization.
  - `json`: For working with JSON data (used in `part_1_mars_news.ipynb`).

### Instructions

1. **Setup Environment**:
   - Install required Python libraries using pip:
     ```bash
     pip install pandas matplotlib seaborn
     ```
   - Ensure Jupyter Notebook is installed:
     ```bash
     pip install notebook
     ```

2. **Run Analysis**:
   - Open each notebook (`part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`) in Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Execute cells sequentially to view analysis and visualizations.

3. **Input Files**:
   - Place the `mars_news.json` and `mars_weather.csv` files in the same directory as the notebooks to ensure proper file loading.

### Outputs

- **Mars News Analysis**:
  - Summary of key topics discussed in the articles.
  - Word frequency analysis to understand popular terms.

- **Mars Weather Analysis**:
  - Trends in temperature and pressure over time.
  - Insights into seasonal changes on Mars.

### Project Goals

- Gain insights into the challenges and findings of Mars exploration through data analysis.
- Practice working with JSON and CSV files in Python.
- Develop visualization skills to communicate data-driven insights effectively.

### Authors

- **Name**: Zachary Hooks
- **Contact**: zhooks558@gmail.com

