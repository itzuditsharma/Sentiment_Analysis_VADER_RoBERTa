# Sentiment_Analysis_VADER_RoBERTa
This project performs sentiment analysis on Amazon product reviews using both traditional and modern NLP techniques.


The analysis includes:

**Exploratory Data Analysis (EDA):** Visualizing the distribution of review ratings and understanding the review dataset.

**VADER Sentiment Analysis:** A rule-based sentiment analysis model that calculates sentiment scores (positive, neutral, negative, and compound) based on the Valence Aware Dictionary and sEntiment Reasoner (VADER).

**RoBERTa-based Sentiment Analysis:** A modern transformer-based model (RoBERTa) is fine-tuned for sentiment classification, providing an alternative, more robust approach to understanding sentiments in reviews.

**Comparison of Models:** The project compares the results of the VADER and RoBERTa models on the same dataset, visualizing differences in their sentiment predictions and the relationships with Amazon review ratings.

**Pairwise Analysis and Visualization:** Displays the relationships between VADER and RoBERTa sentiment scores and the review ratings using Seaborn and Matplotlib.

**Sentiment Analysis Pipeline:** A sentiment analysis pipeline built using the Hugging Face transformers library, providing easy-to-use sentiment analysis for product reviews.


## Key Features:
Data visualization using Matplotlib and Seaborn.

Sentiment analysis using VADER and RoBERTa models. 

Hugging Face's pipeline for quick and easy sentiment analysis.

Exploratory data analysis with Pandas.

Results comparison between VADER and RoBERTa using pair plots.


## Tools and Libraries:
Python

Pandas

Numpy

NLTK (VADER sentiment analyzer)

Hugging Face Transformers (RoBERTa sentiment model)

Seaborn and Matplotlib for data visualization

tqdm for progress tracking
