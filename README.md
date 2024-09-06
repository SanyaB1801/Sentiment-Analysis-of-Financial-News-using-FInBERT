# Sentiment Analysis using FinBERT

## Overview
This project leverages the FinBERT model, a BERT variant fine-tuned specifically for financial text, to perform sentiment analysis on data sourced from Yahoo Finance. It provides insights into the market sentiment by categorizing financial news into negative, neutral, and positive sentiments.

## Features
- **Automated Data Acquisition**: Automatically downloads data from Yahoo Finance.
- **FinBERT Sentiment Analysis**: Utilizes the pre-trained FinBERT model to assess and categorize sentiment from financial texts.
- **Categorical Output**: Converts sentiment scores into categorical labels (negative, neutral, positive).
- **Visualization**: Includes bubble plots to visually represent sentiment distributions across texts.

## Prerequisites
Ensure you have the following prerequisites installed:
- Python 3.8+
- pip (Python package installer)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/SanyaB1801/Sentiment-Analysis-of-Financial-News-using-FInBERT.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To get started with the "Sentiment Analysis using FinBERT" project, follow these steps:

1. **Open the Notebook**:
   - Download the Jupyter notebook from the repository.
   - Open the notebook in an environment that supports Jupyter, such as Jupyter Lab, Jupyter Notebook, or an IDE like Visual Studio Code with Jupyter support.

2. **Install Dependencies**:
   - Ensure all dependencies are installed by running the following command in your notebook:
     ```python
     !pip install -r requirements.txt
     ```

3. **Run the Notebook**:
   - Execute the cells sequentially to understand the flow:
     - **Data Acquisition**: The notebook will show how to automatically fetch financial texts from Yahoo Finance.
     - **Load Tokenizer and Model**: Instructions and code cells to load the necessary FinBERT model.
     - **Tokenization**: Steps to tokenize the fetched data.
     - **Sentiment Analysis**: Apply sentiment analysis and observe the outputs directly in the notebook.
     - **Visualization**: Visualize the sentiment analysis results with bubble plots within the notebook.

4. **Interact**:
   - Modify the code or parameters as needed to perform sentiment analysis on different texts or to refine the results.
   - Experiment with different sections to see how changes affect the outcomes.

5. **Save and Share**:
   - Save your modifications to the notebook.
   - Share your version of the analysis if desired by pushing it back to a repository or through other means.

## Contributing
Contributions are welcome! Please fork the project, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.


## Acknowledgments
- Thanks to the FinBERT model authors and Hugging Face for providing the tools necessary for this analysis.
- Yahoo Finance for providing the data.

---
