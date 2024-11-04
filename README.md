# Twitter Sentiment Analysis with Demographic and Contextual Features
This group project is implemented as part of the NLP course at the university of Oulu.

## Project Overview

The goal of this project is to perform sentiment analysis on a dataset of tweets. The sentiment analysis dataset can be found [here](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset/code).
We incorporate demographic and global context features such as user age, country, and population statistics. By utilizing state-of-the-art transformer-based models, this project aims to provide a more holistic understanding of sentiment through the integration of metadata, including tweet time, user demographics, and country data.


## Dataset

The sentiment analysis dataset contains the following fields:
- **textID**: Unique identifier for each tweet
- **text**: Full text of the tweet
- **selected_text**: Portion of the tweet relevant to the sentiment
- **sentiment**: Sentiment classification (positive, negative, neutral)
- **Time of Tweet**: Timestamp indicating when the tweet was posted
- **Age of User**: Age of the user who tweeted
- **Country**: Country of the user
- **Population 2020**: Population of the country in 2020
- **Land Area (Km²)**: Land area of the country in square kilometers
- **Density (P/Km²)**: Population density of the country


## Installation

To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/sk-tareen/Twitter-Sentiment-Analysis.git
cd sentiment-analysis-project
pip install -r requirements.txt
