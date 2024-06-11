# Natural Language Processing with Disaster Tweets

# Welcome to one of our "Getting Started" competitions
This particular challenge is perfect for data scientists looking to get started with Natural Language Processing. The competition dataset is not too big, and even if you don’t have much personal computing power, you can do all of the work in our free, no-setup, Jupyter Notebooks environment called Kaggle Notebooks.

If you want to talk with other users about this competition, come join our Discord! We've got channels for competitions, job postings and career discussions, resources, and socializing with your fellow data scientists. Follow the link here: https://discord.gg/kaggle

# Competition description
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

https://storage.googleapis.com/kaggle-media/competitions/tweet_screenshot.png

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified. If this is your first time working on an NLP problem, we've created a quick tutorial to get you up and running.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

# Acknowledgements
This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here.

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

# Evaluation
Submissions are evaluated using F1 between the predicted and expected answers.

F1 is calculated as follows:

F1 = 2 ∗ precision ∗ recall / precision + recall

where:

precision = TPTP + FP

recall = TPTP + FN

and:
- True Positive [TP] = your prediction is 1, and the ground truth is also 1 - you predicted a positive and that's true!
- False Positive [FP] = your prediction is 1, and the ground truth is 0 - you predicted a positive, and that's false.
- False Negative [FN] = your prediction is 0, and the ground truth is 1 - you predicted a negative, and that's false.
