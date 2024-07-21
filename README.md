# Twitter-Analysis-of-Apple-Music-and-Spotify (NLP)

 The research question is to analyse the tweets of AppleMusic and Spotify. How their
 tweets differ from each other, to see if they follow what’s trending and the techniques
 they might use in their tweets. The subset of this Twitter data is retrieved through
 Twitter API. I will be using sentiment analysis to determine how their tweets differ,
 cosine similarity if they follow trends and TF-IDF to see the techniques they might
 use in their tweets. Apple Music and Spotify are the two most used music streaming
 apps. The significance of this project is to see any differences or similarities in their
 marketing strategy in managing their twitter account.

Techniques and operations used for this project:
 - Python
 - Spark map-reduce
 - Sentiment Analysis
 - Cosine Similarity
 - TF-IDF (Term Frequency-Inverse Document Frequency)
 - Twitter API
 - Pandas
 - Numpy

Summary:
 - AppleMusic keeps their tweets fairly positive around 56%
 - Spotify keeps their tweets fairly neutral around 51%
 - Their tweets are not similar, only accounting to 0.25% cosine similarity, implying they don't have similar content and not following what's     trending
 - Their TF-IDF shows that they are tweeting their selling point the most, 'Dolby' and 'Spatial Audio' for Apple Music, and '#spotifyisland'       for Spotify

A future direction for this project is to pull the number of likes, retweets and
 comments per tweet. This is to determine which content or tweet generally gets more
 interactions. This then can help get the average number of likes, comments and
 retweets for each tweet. Very useful when comparing them to see which has more
 interactions in general.
