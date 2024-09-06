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

## Outputs and Visualizations

### Bar Chart
Bar charts are used to display the distribution of sentiment scores across different categories (Negative, Neutral, Positive). They provide a clear, straightforward view of the frequency of each sentiment category.

![Bar Chart of Sentiment Distribution](https://github.com/user-attachments/assets/71ac5bc0-07f5-4dee-b18f-045fdfeb496c)


### Pie Chart
Pie charts provide a visual representation of the proportion of different sentiment categories within the dataset, offering an intuitive view of the overall sentiment distribution.

![Pie Chart of Sentiments](https://github.com/user-attachments/assets/2ff888d1-cedd-4463-9dd7-dc8c9e89f054)


### Heatmap
Heatmaps are utilized to show the correlation between different variables in the data set, possibly highlighting relationships between sentiment scores and other financial metrics.

![Sentiment Heatmap](https://github.com/user-attachments/assets/1da7ee3a-7f25-410e-a027-d2d8d8dd7df3)

### Waffle Chart
Waffle charts provide a unique visual representation of market sentiments as parts of a whole, making it easy to visualize proportions in a more engaging way than pie charts.

![Waffle Chart of Market Sentiments](https://github.com/user-attachments/assets/6b648b45-367d-4c8b-b69a-688edde127a6)


### Bubble Plot 
The bubble plot visually represents the frequency and intensity of sentiments across different texts. Larger bubbles indicate a higher occurrence of a particular sentiment. Here’s what you can expect:

![Bubble Plot of Sentiment](https://github.com/user-attachments/assets/775fb091-812b-488d-968e-8c737e8b207a)

These visualizations help in quickly understanding the general sentiment trends in the financial news data from Yahoo Finance.


## Contributing
Contributions are welcome! Please fork the project, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.


## Acknowledgments
- Thanks to the FinBERT model authors and Hugging Face for providing the tools necessary for this analysis.
- Yahoo Finance for providing the data.

---
