# Project Notebooks

This repository contains Jupyter notebooks for various data analysis tasks. Each notebook focuses on a specific aspect of the analysis pipeline.

## Notebooks

### 01_Descriptive_Statistics.ipynb

Analyzes news article data, focusing on:

- **Headline Lengths**: Computes and displays descriptive statistics.
- **Publisher Analysis**: Lists the top 10 publishers by article count in a formatted table.
- **Date Parsing**: Converts timestamps to UTC and extracts day-of-week and date components.
- **Visualizations**: Includes a bar plot for publication frequency by day and a line chart for trends over time.

#### Usage

1. Place your dataset in `../Data/raw_analyst_ratings.csv`.
2. Run the notebook for insights and visualizations.

### 02_Text_Analysis(Sentiment_analysis_&_Topic_Modeling).ipynb

Conducts sentiment analysis and topic modeling on text data.

### 03_Technical_Indicators_with_TALib.ipynb

Applies technical indicators to financial data using the TALib library.

### 04_Visualizing_Stock_Data_and_Indicators.ipynb

Visualizes stock data and technical indicators.

### 05_Sentiment_Analysis_of_News.ipynb

Analyzes sentiment of news articles related to financial markets.

### 06_Correlation_Analysis_between_Sentiment_and_Stock_Returns.ipynb

Examines correlations between sentiment and stock returns.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/AschalewMathewosDamtew/NovaSolutions.git
    ```
2. Navigate to the notebooks directory:
    ```bash
    cd NovaSolutions/notebooks
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Open and run the notebooks using Jupyter:
    ```bash
    jupyter notebook
    ```

## Requirements

Ensure you have the following packages installed:

- pandas
- matplotlib
- python-dateutil
- tabulate
- TALib
- nltk
- sklearn
