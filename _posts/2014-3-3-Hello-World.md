---
layout: post
title: Twitter Sentiment Framework
---

![_config.yml]({{ site.baseurl }}/images/sentiment-analysis.jpg)

Sentiment analysis is an application of Natural Language Processing (a branch of Artificial Intelligence) that revolves around detecting the sentiment of text. A common dimension for measuring sentiment uses labels positive, negative and neutral; there are many other possibilities as well (i.e. how strong the sentiment is, how active vs subdued it is, etc). Figure 1 contains two sample tweets about the current series Falcon and the Winter Soldier, one positive and one negative. Social
media is a particularly popular arena for deploying sentiment analysis: companies aspire to obtain detailed insights into the way their products are being perceived. As a result, there are many organisations offering apps or services for building them; a screenshot from a demo of such an app is given in Figure 2.

The earliest and simplest techniques for performing sentiment analysis (although this type of
approach is still in fact widely used) only conducted keyword matching in the text on the basis of words
from a sentiment lexicon (i.e. a source of words that have known sentiment). Often, these lexicons do not have extensive coverage: there are many words with sentiment that are not included in them, particularly in the case of social media text, where misspellings, abbreviations and slang
are common. Consequently, there are other approaches to the task: there’s a large class of machine learning
techniques applied, as well as other techniques like label propagation, where sentiment labels are propagated through a graph structure.

In this project, I have worked with a set of real tweets collected by researchers who developed
one of the first approaches to sentiment analysis of tweets, and constructed my own tweet sentiment
analyser . Early stages of the project only employ a keyword-based approach, building up to a simple
version of label propagation later.

![_config.yml]({{ site.baseurl }}/images/figure1&2.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
