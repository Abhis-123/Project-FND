# Project-FND

## Introduction
We consume news through several mediums throughout the day in our daily routine, but sometimes it becomes difficult to decide which one is fake and which one is authentic.

Do you trust all the news you consume from online media?

Every news that we consume is not real. If you listen to fake news it means you are collecting the wrong information from the world which can affect society because a person’s views or thoughts can change after consuming fake news which the user perceives to be true.

## Project Aim 
The aim of this project is to classify news articles fake or real 

## Solution 
To get the accurately classified collection of news as real or fake i have build a deep learning  LSTM based model.

Bidirectional Neural Network and LSTM based deep learning model to detect fake news from a given news corpus. This project could be practically used by any media company to automatically predict whether the circulating news is fake or not. The process could be done automatically without having humans manually review thousands of news related articles.

### Dataset Description
* train.csv: A full training dataset with the following     
    #### attributes:
    * id: unique id for a news article
    * title: the title of a news article
    * author: author of the news article
    * text: the text of the article; could be incomplete
    * label: a label that marks the article as potentially unreliable
    * 1: unreliable
    * 0: reliable
* test.csv: A testing training dataset with all the same attributes at train.csv without the label.