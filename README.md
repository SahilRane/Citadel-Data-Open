# Citadel-Data-Open
3rd Place project submission for the Citadel Data Open held from 18th October, 2021 to 24th October, 2021.

Citadel Data Open is a datathon competition taking place throughout the year at a series of top universities. At each event, participants work in teams to 
work through a large and complex dataset and then present their findings to a panel of judges. I was selected to be one of 75 students participating in the 
competition from among several thousand students. I was a part of Team 13 and we won the 3rd place prize defeating teams of undergraduates, graduates, and 
post-doc students.

The problem we set out to explore was an analysis of A/B testing practices by the company Upworthy. A/B testing was a methodology adopted by Upworthy where
they would create multiple packages (a different set of headlines and images) for the same article. They would then release these packages to different users 
and identify the particular set of headlines and images that maximised user engagement measured through 'clicks', that is whether the user clicked on the 
package or not. Using this technique Upworthy was able to achieve a lot of success.

The question we set out to answer was whether the practice of A/B testing was a major cause for the increase in clickbait and whether the choices made by the 
A/B testing algorithm had a statistically significant preference for clickbait articles. We answered this question by first finding a Kaggle dataset that had 
headlines of articles and whether they were clickbait or not. We used Natural Language Processing in order to train a Machine Learning Model that could 
identify whether an article was clickbait or not with over 99% accuracy. We used the XLM RoBERTa model (for high accuracy) and a simple logistic regression 
model (for interpretability of results and identifying key terms and phrases associated with clickbait) which was trained on the tokenized text. After we 
trained this model, we ran it on the Upworthy dataset to identify the "clickbaitiness" of each article headline and used statistical tests such as hypothesis 
testing (t-testing) to check whether the packaging for the articles chosen by Upworthy tended to have a high "clickbaitiness" and where this preference for 
clickbait was statistically significant. Our conclusion was that this was true and A/B testing could be one of the major causes for the increase in the 
publication of clickbait articles in recent times. 
