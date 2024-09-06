# Sentiment Analysis using FinBERT

## Overview
This project applies the FinBERT model, a BERT-based model pre-trained specifically for financial text, to perform sentiment analysis. It is designed to help analysts, investors, and financial enthusiasts gauge the sentiment from financial news and reports to aid in decision-making.

## Features
- **Sentiment Classification**: Classifies sentiments into categories such as positive, negative, and neutral.
- **Data Visualization**: Provides bubble plots of sentiment analysis results for easy interpretation.
- **Customizable Analysis**: Users can input their financial text and receive sentiment analysis results.

## Prerequisites
Before you can run this project, you need to have the following installed:
- Python 3.8 or newer
- pip (Python package installer)

## Installation
To get this project up and running, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://https://github.com/SanyaB1801/Sentiment-Analysis-of-Financial-News-using-FInBERT.git
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Output
- **Sentiment Scores**: After analyzing the financial text, the project outputs sentiment scores that categorize the text as positive, negative, or neutral.
- **Visualizations**: Generates bubble plots that visually represent the sentiment distribution over various texts analyzed.
- **Reports**: Optionally, detailed sentiment reports can be generated as output, summarizing the overall sentiment and highlighting key phrases that influenced the sentiment score.

## Data Source
- **Yahoo Finance**: This project utilizes financial news and stock market data from Yahoo Finance to perform sentiment analysis. Ensure that you adhere to Yahoo Finance's terms of service when using their data.

### Updated Usage Section (including Yahoo Finance)
To include the specifics of using Yahoo Finance data in the usage section of the README, you might add:

## Usage
1. **Prepare Data**: Download your financial text data from Yahoo Finance. Ensure the data format is compatible with the script requirements.
2. **Run Analysis**: Execute the script to analyze the sentiment of financial news obtained from Yahoo Finance.


## Usage
To perform sentiment analysis using the FinBERT model, follow these steps:

1. Navigate to the project directory:
   ```bash
   cd Sentiment_Analysis_using_FinBERT
   ```
2. Run the script with the command:
   ```bash
   python sentiment_analysis.py
   ```
3. Follow the on-screen prompts to input your financial text.

## Contributing
We welcome contributions to this project! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Thanks to the creators of the FinBERT model for providing the tools to analyze financial texts.
