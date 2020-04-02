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
	
* I actually took note of the all-caps speech in my second report. I accomplished this by converting all of the text to lowercase using String.lower().
- Joey *

* Sean's Feedback
	* You have a clear idea of what you want to do, and the data you've selected will be great in helping you get there. It was a great choice to skip Tweepy/the Twitter API and use a precompiled corpus--this will save a ton of data cleaning and overhead.
	* While you have a very clear idea of *what* your project is, I think a few of the *how's* are a little unclear. For example, I'm not 100% as to why you need Sentiment Analysis--and it might not be worth the work if you aren't sure what you want to do with it. That being said, I have the same problems and it's natural to be unsure about techniques this early.
	* I learned about Textblob! I also learned a lot more about the "lambda" functionality from your NB.

* Lindsey's Feedback
	* This project was so entertaining to read about. The "sad" keyword cracked me up. You're also really good at explaining what you're doing step-by-step. I didn't get lost while reading your notebook at all. 
	* This is sort of minor, but the graphs could use some y-axis labels. It was hard to tell just from the graphs alone which graphed retweets and which graphed favorites. Also re: Anthony's feedback, explanation about Textblob would be nice, too. 
	* I learned about how to handle Emojis! I had issues with Unicode etc. myself, but none of it involved Emojis, so if I have to handle that in other projects, I know where to begin.
