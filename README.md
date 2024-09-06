# Nova Financial Insights

## Challenge Overview

This project focuses on analyzing a large corpus of financial news data to discover correlations between news sentiment and stock market movements. The challenge is designed to refine skills in Data Engineering (DE), Financial Analytics (FA), and Machine Learning Engineering (MLE). It aims to enhance your ability to analyze complex data sets, demonstrate adaptability, and employ innovative thinking.

## Business Objective

Nova Financial Solutions aims to boost financial forecasting accuracy and operational efficiency through advanced data analysis. As a Data Analyst, your primary tasks are:

1. **Sentiment Analysis**: Quantify the tone and sentiment of financial news headlines using NLP techniques, and associate sentiment scores with stock symbols.
2. **Correlation Analysis**: Establish statistical correlations between news sentiment and stock price movements. Analyze how news sentiment impacts stock performance, considering publication dates and potentially times.

Your analysis should lead to actionable investment strategies based on insights from sentiment analysis to predict future stock market trends.

## Project Structure

- `.github/`: GitHub Actions workflows.
- `Data/`: CSV files with historical financial data and analyst ratings.
- `myenv/`: Virtual environment.
- `notebooks/`: Jupyter notebooks for detailed analysis.
- `scripts/`: Python scripts for various functions.
- `src/`: Source code.
- `tests/`: Unit tests.
- `.gitattributes`, `.gitignore`, `requirements.txt`: Project configuration and documentation.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/AschalewMathewosDamtew/NovaSolutions.git
    ```
2. Navigate to the project directory:
    ```bash
    cd NovaSolutions
    ```
3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Open and run notebooks:
    ```bash
    jupyter notebook
    ```

## Requirements

- pandas
- matplotlib
- python-dateutil
- tabulate
- TALib
- nltk
- sklearn
