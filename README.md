# Trading Gamification
![GitHub top language](https://img.shields.io/github/languages/top/bordbe/trading_gamification?color=yellow)

This repo contains all the work I did for my master thesis. The topic is gamification of trading which I chose to approach as an existing phenomenon to be taken into account. So I did not lose myself in exploring the pros and cons of its regulation but rather in looking for its consequences on the market. 

In order to take this gamification into account when analysing the market, I decided to approach it through the sub-reddit r/wallstreetbets. After justifying this approach with a sentiment analysis, I then built a text classification model to predict the direction of SPY in the aftermath of WSB daily discussion threads. 

##  Data

The comments from WSB come from : 

* a dataset collected from [KAGGLE](https://www.kaggle.com/theriley106/wallstreetbetscomments)
* completed with pushshift.io and PRAW (the REDDIT API)

The database created includes all discussion threads with comments between 11 April 2014 and 22 December 2021.

##  Model

