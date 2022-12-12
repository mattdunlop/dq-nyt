# Analyzing New York Times Article Metadata
Recommended to view on nbviewer: https://nbviewer.org/github/mattdunlop/dq-nyt/blob/main/dq-nyt.ipynb

In this notebook we analyze and visualize the metadata of New York Times articles published between January 2020 and October 2022.

- We study the evolution of article subjects over time, ranking according to total mentions of subjects, and maximum mentions in a rolling weekly period. A number of trends are identified, with many correlating with Coronavirus and the Black Lives Matter movement.
- We perform sentiment analysis on article abstracts -- is everything getting gloomier over time? It turns out that, in terms of sentiment of the articles, this isn't the case.
- Finally we focus on presidents Biden and Trump, visualizing the people they are most associated with, and seeing if any bias/trends arise in terms of sentiment. We see that, although the NYT generally publishes more positive articles regarding Biden and more negative articles regarding Trump, the difference between them is decreasing over time. In particular, the proportions of negative articles published regarding Biden and Trump are almost equal as of October 22, and significantly higher than the average proportion of negative articles over all subjects. 

Dataset: https://www.kaggle.com/datasets/cascaschatz/new-york-times-articles-metadata-2020-2022
