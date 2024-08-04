## Overview

This project aims to analyse financial complaints data. It focuses on extracting insights from text data to classify decisions as "Upheld" or "Not upheld." The project involves several key components, including data scraping, preprocessing, exploratory data analysis (EDA), n-gram analysis, topic modelling, and machine learning classification.

## Structure

pdf2txt.ipynb: Contains notebooks for scraping data from the Financial Ombudsman Service, extracting text from PDF files, and organising the data into training and testing sets.

eda_basics.ipynb: Includes basic exploratory data analysis, such as loading data, preprocessing with spaCy, and visualising key metrics like word count and sentence length.

eda_ngram_analysis.ipynb: Focuses on n-gram analysis, extracting and visualising frequent word sequences in text data. It also covers named entity recognition and class-wise distribution analysis.

eda_topic_model.ipynb: Implements topic modelling using Latent Dirichlet Allocation (LDA) to discover and visualise underlying topics in the text data.

classification.ipynb: Details the machine learning classification process, including training and evaluating models to predict the outcome of complaints.