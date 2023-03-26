# NLP_hackathon_032423
Natural Language Processing hackathon
The notebook includes tasks for a Hackathon on the NLP class at UCI. There are two data sets we needed to work on during the hackathon.
The "emotion" data includes content and associated sentiment such as empty, sadness, hapiness, worry, and others. 
The another data set include tweets about 6 major airlines and relevant sentiment like positive, neutral, negative.
We perofmed various task and compete with other teams on speed and accuracy. The tasks are established with low level at the beginning and more challenging when
the Hackathon moved further. The hackathon required us to apply a variety of NLP techniques and machine learning to analyze sentiment from tweets and provide 
insight to airlines. Following techniques are employed in this hackathon:
* CountVectorizer and TfidfVectorizers
* Sentiment analysis classifier with machine learning such as Decision Tree and Naive Bayes
* Topics modeling to identify topics from text
* Data visualization

Here are summary of tasks that we needed to conduct.
* Part 1: Create the word cloud of negative and positive words for every airline.
* Part 2: Show the distribution of positive/neutral/negative sentiment across all airlines
* Part 3: Analyze the words distribution on the given "emotions" dataset
* Part 4: Build the Decision Tree and Naive Bayes classifiers with parameters tuning from emotions data in part 3 to classifer the emotion of each content.
* Part 5: Use Naive Bayes built in part 4 to predict the sentiment in the airline data set. What is accuracy?
* Part 6: Build topics model to identify what topics people are talking about in their tweets? How does this distribution of topics differ across airlines?
* Part 7: Plot a heat map that shows the sentiment associated with the airlines for different topics and analyze the relationship between them.
* Part 8: Build a function to show how airlines differ based on the emotions consumers express about them in the tweets. Pick Southwest and United and provide insights
to the airlines management team.
* Part 9: Pick two topics (dimensions) and create a perception map of how all the airlines are located on the two-dimensional map. The axes go from -1 to 1,
where 1 denotes that all the tweets pertinent to an airline about that topic are positive, whereas -1 denotes that all tweets are negative.
