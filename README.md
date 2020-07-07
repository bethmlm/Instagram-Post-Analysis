# Instagram-Post-Analysis
TLDR; .ipynb that present a bot that scrapes post information from a specified instagram account, with an example 

# Goal and Background
Instagram business accounts have the functionality to look at a users post statistics -- what time of day do they get the most likes? What hashtags give them the most likes? Which hashtags are you using the most? But if you're managing an instagram account, you might be curious about the statistics for other SIMILAR businesses. For example, if you're a boutique shoe store, you might want to know what hashtags other shoe stores are using and which of those hashtags are associated with the most likes. What time of day are other shoe stores posting and what time of day or year gets these posts the most likes? If there is a particularly successful instagram account that you would like to emulate, being able to view that account's statistics could help you boost engagement on your own instagram account and ultimately help your business.

The goal of this project is to create a web scraping bot with Selenium that will log in to an instagram account, then navigate to an account that the user specifies and scrapes the post information from said account. The bot will scrape information on date and time of posting, number of likes/views, the original post comment, and the original post hashtags.

In this code I perform an example using the Instagram account of the Los Angeles based dog adoption agency Tobies Small Dog Rescue (because who doesn't like puppies?). We will scrape the infromation from all the posts on the 'tobiessmalldogrescue' instagram account and analyze the most used hashtags, which hashtags are associated with the most likes, and which dates and times are associted with the most likes.

# Python v 3.7.3

# Libraries
selenium
pandas
numpy
time
re
itertools
pickle
matplotlib
sci-kit learn
seaborn
datetime
