# Hespress Scraper & Sentiment Analysis with BeautifulSoup, Googletrans, TextBlob, Scikit-learn

## Project Overview

This project aims to scrape comments from articles on the Hespress website and analyze their sentiment. The project leverages various technologies to achieve this, including BeautifulSoup for web scraping, Googletrans for translation, TextBlob for sentiment analysis, and Scikit-learn's Linear Regression for sentiment prediction.

## Features

- **Web Scraping**: Extract categories, articles, and comments from Hespress.
- **Translation**: Translate Arabic text to French using Googletrans.
- **Sentiment Analysis**: Analyze the sentiment of comments using TextBlob and predict sentiment with a Linear Regression model from Scikit-learn.
- **Data Storage**: Save the scraped and analyzed data into a CSV file.

## Technologies Used

- **BeautifulSoup**: For parsing HTML and scraping web content.
- **Googletrans**: For translating text from Arabic to French.
- **TextBlob**: For basic sentiment analysis.
- **Scikit-learn**: For training a Linear Regression model to predict sentiment.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Hespress-Scraper-Sentiment-Analysis.git
    cd Hespress-Scraper-Sentiment-Analysis
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script to scrape articles and comments, translate them, analyze sentiment, and save to CSV:
    ```sh
    python main.py
    ```

2. The output CSV file `articles_comments.csv` will contain the scraped data, including translated comments and their sentiment.

## Project Structure

- `main.py`: Main script to run the entire scraping and analysis process.
- `data_scraper.py`: Contains the `DataScraper` class for scraping categories, articles, and comments.
- `translator_service.py`: Contains the `TranslatorService` class for translating text.
- `sentiment_analyzer.py`: Contains the `SentimentAnalyzer` class for analyzing sentiment and training the regression model.
- `data_saver.py`: Contains the `DataSaver` class for saving data to a CSV file.
- `requirements.txt`: Lists all the dependencies required for the project.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the developers of BeautifulSoup, Googletrans, TextBlob, and Scikit-learn for their fantastic libraries.
- Inspired by the need to understand public sentiment through comment analysis on news articles.
