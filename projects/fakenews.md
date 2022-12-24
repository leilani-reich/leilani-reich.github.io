---
layout: project
type: project
published: true
image: img/projects/fakenews-square.png
title: Analyzing Fake News with a Big Data Mindset
permalink: projects/FakeNews
# All dates must be YYYY-MM-DD format!
date: 2022-12-09
labels:
  - Big Data Analysis
  - ICS 438
  - PySpark
  - Python
  - Jupyter Notebook
  - Docker
summary: I conducted an analysis on fake news data in a distributed processing manner.
---
## Introduction
In this project, I analyzed data regarding fake news posts to learn more about the data, gain insights into fake news, get more familiar with distributed
processing (analyzing data in parallel with multiple machines that split the work), and to see how well I could classify fake news. I utilized GitHub,
the Jupyter Notebook IDE, the Docker platform, and Python. In addition, for handling data, I mostly utilized the distributed processing library called 
[PySpark](https://spark.apache.org/docs/latest/api/python/), and I also dipped my toes into another Python library enabling parallel processing called [Dask](https://www.dask.org/).

## Dataset
The dataset I used is titled ["Fake and real news dataset,"](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?select=True.csv) and it originates from user
Clément Bisaillon on [Kaggle](https://www.kaggle.com/). Within this dataset, there are two data files: Fake.csv (62.79 MB) and True.csv (53.58 MB). 
Each data file contains the following 4 attributes for each record: title, the title of the article; text, the text within the article; subject, the subject
of the article; and date, the date at which the article was posted.

## Problems I tackled
There were several things I investigated in my analysis. I looked into fake news and analyzed several characteristics that set it apart from true news, 
such as length, subjects, dates, and prominent words. I also used an algorithm called approximate nearest neighbors to try and accurately classify news
as fake or true based on similarity to other news posts.

## What I learned
I've learned several things from my project. First off, fake news is more wordy than true news, which was what I expected. With fake news, people can spew
a lot of nonsense and run on and on, but true news is generally more concise. In addition, the true news posts were more prevalent in the 2017
September-December period whereas fake news was more prominent in the 2016 summer period, specifically May, which was interesting to see. I think fake news 
is more prominent in 2016 due to the 2016 presidential election. Another discovery I made was that the main topics of both fake and true news tend to be politics
or just general news. Speaking of which, I found that the most frequent words in both the fake news and true news datasets relate to politics, with keywords like
"trump", "america", and "hillary", which is sensible, especially considering this data comes from the 2016-2017 period. In regards to the models, I discovered it
is viable to use an approximate nearest neighbors approach to classify a news post as true or fake based on its similarity to other news posts, and that autofaiss
does it quickly and efficiently compared to another algorithm from the PySpark library called BucketedRandomProjectionLSH, at least the way I approached it.
In the end, from this project I learned more about distributed computing with PySpark and applying the concepts in the class ICS 438: Big Data Analytics. In the future,
I hope to get better at distributed computing and parallelization and understanding how to work with it because I struggled a lot with this area, and I know there is some
code in this project that could be improved in terms of efficiency.

Link to Project: [FakeNews-GitHub](https://github.com/leilani-reich/ICS438-FinalProject-FakeNews)
