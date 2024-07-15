# Sentiment Analysis Tool

This repository contains a sentiment analysis tool developed using Python and the Natural Language Toolkit (NLTK). The tool classifies the sentiment of text data into positive, negative, or neutral categories.

## Features

- Collect and preprocess text data from the NLTK movie reviews corpus.
- Develop a sentiment analysis model using the Naive Bayes classifier.
- Analyze the sentiment of new text samples.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/abhinav-12357/Sentiment-Analysis-Tool.git
    cd Sentiment-Analysis-Tool
    ```

2. Install the required Python libraries:

    ```sh
    pip install nltk scikit-learn pandas numpy
    ```
    
## Usage

1. Run the Python script to preprocess the data, train the model, and evaluate its performance:

    ```python
    python sentiment_analysis.py
    ```

## Example

Here's an example of how to use the sentiment analysis tool:

```python
sample_text = "The movie was fantastic and I loved it!"
print(f'Sentiment: {analyze_sentiment(sample_text)}')
```
## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## Contact

For any inquiries or questions, please contact [abhinavshakya063@gmail.com].

This README provides an overview of the project, installation instructions, usage examples, and the MIT license.
