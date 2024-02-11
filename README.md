# Reddit Sentiment Analysis

This project performs sentiment analysis on Reddit comments using natural language processing techniques. It utilizes the Reddit API to collect comments from specified subreddits and applies machine learning models to analyze the sentiment of the collected comments.

## Features
- Collect comments from Reddit using the Reddit API.
- Preprocess text data for sentiment analysis.
- Train machine learning models for sentiment classification.
- Analyze sentiment trends over time.
- Visualize sentiment analysis results using graphs and charts.

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/hash1khn/reddit-sentiment-analysis.git
    ```
2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```

## Usage
1. Set up Reddit API credentials by creating a Reddit application [here](https://www.reddit.com/prefs/apps).
2. Update the `config.py` file with your Reddit API credentials.
3. Run the `reddit_sentiment_analysis.py` script to start collecting and analyzing Reddit comments:
    ```
    python reddit_sentiment_analysis.py
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [praw](https://github.com/praw-dev/praw) - Python Reddit API Wrapper
- [scikit-learn](https://scikit-learn.org/) - Machine Learning Library in Python
- [matplotlib](https://matplotlib.org/) - Data Visualization Library in Python
