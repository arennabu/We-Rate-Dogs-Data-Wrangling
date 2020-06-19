# We-Rate-Dogs-Data-Wrangling

### Objective and key findings
Real-world data rarely comes clean. In this project, I gathered We-Rate-Dog twitter data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned, stored, and analyzed it. 

I was interested in find out the distributions and any factors that have impact on dog rating scores. Some key findings include:  

- Most dog rating scores are between 1 to 1.25, and is to say most people rate the dog 10/10 to 12.5/10! 
- 94% of dog rating users are from Twitter for iPhone, indicating the popularity of this user source. This could be an important market information for the industry. The Vine - Make A scene iPhone app by Twitter, however, only counts for 3.9% of user sources compared to Twitter for iPhone.
- Surprisingly, TwitterDeck users gave the highest dog rating score, this may due to the high score outliers. Otherwise, Twitter for iPhone users rate the dogs slightly higher than other users. 
- People love the dogs that are in the stage of between doggo and puppo, followed by doggo and puppo!  They received the highest dog rating score, retweet counts and favourite counts!


### Install

`import pandas as pd`

`import numpy as np`

`import requests`

`import json`

`import os`

`import tweepy`

`from tweepy import OAuthHandler`

`import json`

`from timeit import default_timer as timer`

`import matplotlib.pyplot as plt`

`import seaborn as sb`


### Contents
- Intrudction
- Gathering
- Assessing 
- Cleaning
- Storing
- Analyzing and Visualizations
