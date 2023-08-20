# SocPredict-ML
---

## Overview
This project focuses on predicting wins and losses for the 2022-23 season of La Liga football using a machine learning model based on data from the 2021-22 season. By analyzing match logs and shooting statistics, the goal is to develop a predictive model that can provide insights into team performance and outcomes.

## Project Structure  
- `scraper.ipynb`: Jupyter Notebook for web scraping data from La Liga match statistics pages.
- `predict.ipynb`: Jupyter Notebook for cleaning, merging, and formatting of the scraped data.
- `predict.ipynb`: Also implements the building of and evaluation of the Random Forest Classifier model.
- `games_stats.csv`: Processed and aggregated dataset containing match logs, shooting statistics, and predictions.

## Data Collection
Used web scraping techniques to gather match logs and shooting statistics for the 2021-22 and 2022-23 seasons of La Liga football. The `requests` and `BeautifulSoup4` libraries were employed to extract relevant information from web pages.

## Data Preprocessing
The collected data was processed and cleaned in the `predict.ipynb` notebook.  
The steps included:
- Merging match logs and shooting statistics for each team.
- Filtering and formatting data to retain only La Liga match information.
- Combining data from multiple seasons and teams into a single dataset.
- Standardizing column names for consistency.

## Random Forest Classifier Model
The `predict.ipynb` notebook also showcases the implementation of the Random Forest Classifier model:
- Utilizing the `pandas` library for feature engineering.
- Exploring hyperparameter tuning for optimal model performance.
- Evaluating the model's accuracy and performance metrics.  
---

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/brmattos/SocPredict-ML.git
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Jupyter notebooks for data collection, preprocessing, and model building.

