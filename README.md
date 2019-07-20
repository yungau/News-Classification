# News-Classification

In this repository, we perform multiclass text classification of the category of news given the headline and the short description of the news using tensorflow with keras API.

We only predict top 10 most frequently occurring news categories for the reasons of shorter training time and better performance.

For machine learning model, we simply use bidirectional LSTM model followed by a fully connected layers for this task and achieve a quite good result.