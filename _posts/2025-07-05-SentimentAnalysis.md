---
layout: post
title: Sentiment Analysis
---

This is a rough documentation of or the Journey to the Sentiment Analysis project that helped me learn NLP and basic ML algorithms

- toc
{: toc }

## Data Gathering
Made a review scraper with requests and bs4 to get random threads data.

## Pre Processing
Cleaned the urls, named entities, idioms, spelling errors, mixed langauges, acronyms, slangs, etc. to improve efficiency. ALbeit I claim that this is all from scratch, you can't possibly expect me or anyone to be serious about data cleaning process, thus I used AI Overlords' help to clean the strings and store them in a neat and clean CSV file.

## Labelling
So, I cheated and used the distilled BERT(will be distilling it in future for demonstration) to classify the sentiments of the dataset. This process is usually done by a large group of humans to train the learning models but I am lazy and you can't expect me to read 1,000 lines of non sense thread dumps.


## Looking at the data
Using pandas profiling generated a report for what the data set looks like, so you know what it's going to be like


## Splitting the Database
So, the proper way to do this would be to preserve the variance of the data but I am lazy and this for NLP and ML algorithms not data preprocessing master class. So I shuffled the database and made a 3:1 split. 750 tweets(or whatever the thread lingo is) for "training" and 250 for "testing".

PS: Ideally you need at least 30,000 data entities to get your model to produce meaningful predictions but I don't have that much resources to spare and thus we will hallucinate that the model is good and everything is fine.


# Models
Get your Sci-Kit learn documentation's ready, we are about to import Naive Bayes Classifier and SVM Classifier.

## Naive Bayes Classifier
-->

## SVM Classifier

Now calm down and let us import 

There are also ten grayscale colors to choose from.

