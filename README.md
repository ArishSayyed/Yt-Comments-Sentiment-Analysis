# Yt-Comments-Sentiment-Analysis
This project is aimed at getting a report of how the audience is reacting to a Youtube video by analyzing the top comments.

- The code in this notebook first takes authorization for you to fetch Youtube data from Google
- Then You have to input the Youtube Video url or Video Title in the input box that will be provided
- It will fetch the top 100 comments on that video and puts it in a dataframe, cleans the comments (of punctuations and other unnecessary stuff)
- There are only words left now processes the words
- Gives a sentiment score to the comments based on the words that were in that comment. A positive score between 0 and 1 to a good comment (depending upon how strongly positive the words are) while a negative score between 0 and -1 for a bad comment
[for e.g. comment: good video, score: 0.6 ; comment: best video, score: 0.9
similarly a comment having negative words like 'bad','disgusting','worst' will get a score between 0 and -1]
- Based on average and the weighted average of these scores the program will make a General report and a Detailed report to give you an idea of how the audience reacted to the video
- Lastly, It gives a pie chart showing the percentage of the various types of comments received
