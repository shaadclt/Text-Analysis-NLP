# Text Analysis with Python

This Jupyter Notebook-based project demonstrates various Natural Language Processing (NLP) and data analysis techniques using Python. The project includes text analysis, sentiment analysis, named entity recognition (NER), word cloud generation, and topic modeling.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Word Cloud](#word-cloud)
- [Sentiment Analysis](#sentiment-analysis)
- [Named Entity Recognition (NER)](#named-entity-recognition-ner)
- [Top Named Entities](#top-named-entities)
- [Topic Modeling](#topic-modeling)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

This Jupyter Notebook project showcases various NLP and data analysis techniques using Python libraries such as spaCy, TextBlob, matplotlib, scikit-learn, and more. The project demonstrates how to perform word cloud generation, sentiment analysis, named entity recognition, and topic modeling on a dataset of articles.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Jupyter Notebook
- Python libraries: pandas, plotly, wordcloud, textblob, spacy, matplotlib
- The spaCy model 'en_core_web_sm'

## Getting Started

1. Clone this repository:

```shell
git clone https://github.com/shaadclt/Text-Analysis-NLP.git
```

2. Install the required Python packages:

```shell
pip install pandas plotly wordcloud textblob spacy matplotlib
python -m spacy download en_core_web_sm
```

3. Open the Jupyter Notebook (`text_analysis.ipynb`) to explore and run the code.

## Word Cloud

The project generates a word cloud from the titles of the articles, visually representing word frequency.

## Sentiment Analysis

Sentiment analysis is performed on the article content, and a histogram shows the sentiment distribution.

## Named Entity Recognition (NER)

The project utilizes spaCy to extract named entities from the articles and visualizes the top named entities.

## Top Named Entities

A bar chart displays the top 10 named entities found in the articles.

## Topic Modeling

The project uses scikit-learn to perform topic modeling on the articles. The topics are visualized using a bar chart.

## Project Structure

The project directory structure is as follows:

```
- text_analysis.ipynb     # Jupyter Notebook
- articles.csv                        # Dataset
- README.md                           # This README file
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
