# Data analysis on COVID-19-related tweets

## Introduction

In this Python project, we conduct a comprehensive analysis of COVID-19-related tweets from all around the world during a four-day period (04-21-2021 - 04/24/2021). The data was obtained from [Kaggle](https://www.kaggle.com/datasets/komalkhetlani/tweets-about-covid19-all-over-the-world). The project consists of the followings:
- Observation of post activity on a hourly basis 
- Text frequency analysis of English tweets and hashtags 
- Sentiment analysis of English tweets
- Statistical analysis of the connection between the sentiment category (positive/neutral/negative) and the popularity (likes count, replies count, retweets count) of a tweet

For a more detailed description, please see the project report given in the report.pdf file. 

The project code is given in the Jupyter notebook code.ipynb.

## Installation

To run the project code, you must first have [Python](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/) installed. Change the working directory into the project's (unzipped) folder and run the following in command line:

```
python -m venv venv
venv\Scripts\activate \\Windows
source venv/bin/activate \\Linux, Mac
pip install -r requirements.txt
```
After that, you can open the code.ipynb file in an text editor of your choice. Remember to select the current venv as the kernel. 