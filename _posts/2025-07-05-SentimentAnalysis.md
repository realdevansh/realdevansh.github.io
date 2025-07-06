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

<dl class="colors">
  <dt style="background-color: #f8f9fa;"></dt>
  <dd>
    <strong>var(--gray-000)</strong><br>
    #f8f9fa
  </dd>
  <dt style="background-color: #f1f3f5;"></dt>
  <dd>
    <strong>var(--gray-100)</strong><br>
    #f1f3f5
  </dd>
  <dt style="background-color: #e9ecef;"></dt>
  <dd>
    <strong>var(--gray-200)</strong><br>
    #e9ecef
  </dd>
  <dt style="background-color: #dee2e6;"></dt>
  <dd>
    <strong>var(--gray-300)</strong><br>
    #dee2e6
  </dd>
  <dt style="background-color: #ced4da;"></dt>
  <dd>
    <strong>var(--gray-400)</strong><br>
    #ced4da
  </dd>
  <dt style="background-color: #adb5bd;"></dt>
  <dd>
    <strong>var(--gray-500)</strong><br>
    #adb5bd
  </dd>
  <dt style="background-color: #868e96;"></dt>
  <dd>
    <strong>var(--gray-600)</strong><br>
    #868e96
  </dd>
  <dt style="background-color: #495057;"></dt>
  <dd>
    <strong>var(--gray-700)</strong><br>
    #495057
  </dd>
  <dt style="background-color: #343a40;"></dt>
  <dd>
    <strong>var(--gray-800)</strong><br>
    #343a40
  </dd>
  <dt style="background-color: #212529;"></dt>
  <dd>
    <strong>var(--gray-900)</strong><br>
    #212529
  </dd>
</dl>

