# Joey's Guestbook
#### Joey Livorno | gil15@pitt.edu | 3.3.2020

This file contains peer feedback to my term project, Sentiment Analysis of Trump Tweets. The repository for my project can be found [here](https://github.com/Data-Science-for-Linguists-2020/Sentiment-Analysis-of-Trump-Tweets).

* Anthony's Feedback
	* You've done a great job structuring your code notebook so far, and I can see how it will probably develop as you continue to work on it.
	Very organized, very readable. Also props for storing your emoji information in a separate script and reading it in, that's a great way
	to keep your analysis file from getting cluttered.
	* I think you might want to spend more time explaining what Textblob is, how it works, and any potential shortcomings that you/your reader
	should be aware of. Also, when looking for specific elements in the string, you might actually want to include all-caps speech! Trump's
	certainly no stranger to it, and I think you'd miss out on "WITCH HUNT" with your current setup if you tried to find it.
	* It's been cooling learning about Textblob, even though I definitely have more questions than answers! I'm looking forward to seeing this
	project develop.

*I actually took note of the all-caps speech in my second report. I accomplished this by converting all of the text to lowercase using String.lower(). - Joey*

* Sean's Feedback
	* You have a clear idea of what you want to do, and the data you've selected will be great in helping you get there. It was a great choice to skip Tweepy/the Twitter API and use a precompiled corpus--this will save a ton of data cleaning and overhead.
	* While you have a very clear idea of *what* your project is, I think a few of the *how's* are a little unclear. For example, I'm not 100% as to why you need Sentiment Analysis--and it might not be worth the work if you aren't sure what you want to do with it. That being said, I have the same problems and it's natural to be unsure about techniques this early.
	* I learned about Textblob! I also learned a lot more about the "lambda" functionality from your NB.

*Thanks, Sean. I definitely think I've made progress on this front, and my objective will become even clearer as I progress through the project. - Joey*

* Lindsey's Feedback
	* This project was so entertaining to read about. The "sad" keyword cracked me up. You're also really good at explaining what you're doing step-by-step. I didn't get lost while reading your notebook at all.
	* This is sort of minor, but the graphs could use some y-axis labels. It was hard to tell just from the graphs alone which graphed retweets and which graphed favorites. Also re: Anthony's feedback, explanation about Textblob would be nice, too.
	* I learned about how to handle Emojis! I had issues with Unicode etc. myself, but none of it involved Emojis, so if I have to handle that in other projects, I know where to begin.

*A big reason I don't have a lot of information about TextBlob is because I'm still unsure whether or not I will be replacing it with the traditional nltk sentiment analysis tools. Once I make a decision, I should have some more concrete descriptions of whichever tool I choose. Thanks for the feedback! - Joey*

* Natasha's Feedback (4/2)
	* This project was great to review because it's similar to the kind of data i'm using! I thought it was a great idea to use certain keywords for the sentiment analysis of the tweets, and I might incorporate that into my own classifier. Its great that you have clear plots decribing your data too!
	* This is over-all pretty good presentation wise, but the graph portion could be explained a bit more so the viewer knows what they are looking at!
	* I learned about how to use TextBlob for sentiment analysis, and since my next phase of analysis involves improving my classifier, it would be interesting to look into TextBlob!


* Jordan's Feedback (4/14)
	* Really interesting project, I like how you can see real world political changes reflected in the data.
	* I read Anthony's feedback and it seems like you misinterpereted what he was saying. I think he meant that a tweet being in all caps could be a variable of its own. I'd assume that all caps means a message has a higher polarity in one direction or another, and you could be missing out on that information.
	* Textblob seems like a very usefull library, I'll have to check it out

* Juan's Feedback (4/15)
	* Your procedure was informed by your research questions and the overall goal of the project. It was easy to follow the steps of your code and you did a great job manipulating the data frame object. The classifier was a nice addition as well, I was surprised by the accuracy too! I guess there are some very informative features.
	* All of your data files are too big to be seen directly in the GitHub interface. You could consider adding a small sample that readers don't need to download (or view raw). If you continue working on this later, I agree considering caps themselves as a feature could be informative.
	* I was unfamiliar with `TextBlob`. It looks like a really useful library for those doing sentiment analysis.

* Kiara's Feedback (4/15)
	* I like how relevant your project is to our daily lives (we all come into contact with Trump tweets even if we don't want to) so it's cool to see how politics is reflected through his Tweets. 
	* I agree with what everyone else was saying about tweets in all caps. Also Trump only tweets in English and if I read your notebook correctly, your collection of random tweets include those in other languages. I don't know if those are accounted for or not, but that could have some kind of effect on the sentiment analysis.
	* I liked learning about TextBlob. If I ever do sentiment analysis for anything I'll def check it out.
