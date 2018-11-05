# Machine-Learning
Machine Learning Projects

Hacker News is a social news website focusing on computer science and entrepreneurship. It has a community where users can submit articles, and other users can upvote those articles. Like other website the articles with the most upvotes make it to the front page.

This data set consists of submissions users made to Hacker News from 2006 to 2015. Developer Arnaud Drizard used the Hacker News API to scrape the data, which which can be found in one of his GitHub repositories. https://github.com/arnauddri/hn

hn_stories is 3000 rows that was sampled from the data randomly, and it has only has four columns:

submission_time - When the article was submitted upvotes - The number of upvotes the article received url - The base URL of the article headline - The article's headline

I'll be predicting the number of upvotes the articles received, based on their headlines. Upvotes are an indicator of popularity, I will try to discover which types of articles tend to be the most popular it this community.
