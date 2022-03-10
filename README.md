# Covid-Tweets-PCI-PSI

This codebase contains the python scripts for calculating concern levels during COVID-19 using RoBERTa based transformers, proposed in the paper titled "Concern levels during COVID-19: An AI-based approach for social media analysis".

Presented at ICIICT - 2022 International Conference on Innovations in Information and Communication Technologies

## Contents and Description

Tweet-Preprocessing -> This folder contains the preprocessing of tweets (Sentiment140) and self-hydrated COVID tweets dataset.

Models.PCI -> This folder contains the RoBERTa based classification model used for classifying tweets into covid related and non-covid related.

Time-Series Analysis -> This folder contains all the scripts used for implementing the trained RoBERTa model on self-extracted tweets from Mumbai, Bangalore and Delhi over a period of 13 months (Jan'21-Jan'22) and calculation of PCI indices.

## Data and Preprocessing

Find the Seniment140 dataset [here](https://www.kaggle.com/kazanova/sentiment140), and the related tweets and time series dataset [here](https://drive.google.com/drive/folders/1ERJ5-JbkS1Y4rghB_mF4qxvuxZGRFbGx?usp=sharing).
