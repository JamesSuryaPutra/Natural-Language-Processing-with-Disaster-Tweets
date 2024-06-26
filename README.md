# Natural Language Processing with Disaster Tweets
![header](https://github.com/JamesSuryaPutra/Natural-Language-Processing-with-Disaster-Tweets/assets/155945814/81b471a2-8d77-4584-88a2-b73e0e430630)

# Welcome to one of our "Getting Started" competitions
This particular challenge is perfect for data scientists looking to get started with Natural Language Processing. The competition dataset is not too big, and even if you don’t have much personal computing power, you can do all of the work in our free, no-setup, Jupyter Notebooks environment called Kaggle Notebooks.

If you want to talk with other users about this competition, come join our Discord! We've got channels for competitions, job postings and career discussions, resources, and socializing with your fellow data scientists. Follow the link here: https://discord.gg/kaggle

# Competition description
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

<img width="296" alt="tweet_screenshot" src="https://github.com/JamesSuryaPutra/Natural-Language-Processing-with-Disaster-Tweets/assets/155945814/990eddeb-755c-4ee5-928c-ed01cae6ad94">


The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified. If this is your first time working on an NLP problem, we've created a quick tutorial to get you up and running.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

# Acknowledgements
This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here.

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

# Evaluation
Submissions are evaluated using F1 between the predicted and expected answers.

F1 is calculated as follows:

![f1_score](https://github.com/JamesSuryaPutra/Natural-Language-Processing-with-Disaster-Tweets/assets/155945814/545dc5c7-0f35-4408-b38b-a1e9ef72d811)


where:

![precision-recall](https://github.com/JamesSuryaPutra/Natural-Language-Processing-with-Disaster-Tweets/assets/155945814/da251003-a2d0-4634-92a7-dd28f26367d9)


and:

- True Positive [TP] = your prediction is 1, and the ground truth is also 1 - you predicted a positive and that's true!
- False Positive [FP] = your prediction is 1, and the ground truth is 0 - you predicted a positive, and that's false.
- False Negative [FN] = your prediction is 0, and the ground truth is 1 - you predicted a negative, and that's false.
