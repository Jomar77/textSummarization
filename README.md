# Text Summarizer using NLP in Python
This repository contains a Python-based text summarizer utilizing Natural Language Processing (NLP) techniques. The text summarizer has two iterations, each using a different NLP architecture to generate a concise summary of the input text.

## Getting Started
These instructions will help you get the text summarizer up and running on your local machine.

## Prerequisites
You need to have the following libraries installed in order to run the text summarizer:

- Numpy
- Pandas
- Matplotlib
- NLTK
- Transformers
- Tensorflow

## Installing
To install the required libraries, run the following command in your terminal:

```
pip install numpy pandas matplotlib nltk transformers tensorflow
```

## Usage
The text summarizer can be run from the command line by executing the following command:

```
python textSummarizer.py
python textSummarizer2.py
```

The program will prompt you to enter the input text and the desired length of the summary. The generated summary will be displayed in the terminal.

## Iterations
The text summarizer has two iterations, each using a different NLP architecture to generate the summary.

## Iteration 1
The first iteration uses the TF-IDF technique to identify and extract the most important sentences from the input text. The sentences are ranked based on their TF-IDF score, and the top n sentences are selected to form the summary, where n is the desired length of the summary.

## Iteration 2
The second iteration uses a similar technique above to analyze the input text and generate a more nuanced summary that captures the context and meaning of the original text. The summary is generated by selecting the most relevant sentences from the input text based on their contextual similarity to the input text as a whole.

## Conclusion
This repository provides a valuable resource for anyone interested in NLP and text summarization. The code is well-documented and easy to understand, making it a great starting point for further exploration and customization. So if you're looking to dive into the world of NLP and text summarization, be sure to check out this repository.
