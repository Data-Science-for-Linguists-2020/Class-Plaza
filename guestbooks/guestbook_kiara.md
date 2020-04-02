## Star Wars Dialogue Analysis - Kiara
Welcome!! | There's a lot of underdeveloped stuff 
### Project Info
- [Repo] (https://github.com/Data-Science-for-Linguists-2020/SW-Dialogue-Analysis)
- [Code] (https://github.com/Data-Science-for-Linguists-2020/SW-Dialogue-Analysis/tree/master/code)

### Comments

#### Juan

- **What is done well:** This is an interesting project! Looking forward to the developments. So far I think the procurement of the data is well done.
- **What could be improved:** What variables are you planning to explore? That is to say, how are you going to operationalize "differences in speech" or "changes in speech"? The code for all notebooks reads "Episode IV" even though it's different episodes. To get all the data frames in the same notebook you might consider pickling them.
- **What I learned:** I learned about some useful tools (webdriver, BeautifulSoup) to extract raw text from websites.
- *Kiara*: webdriver was a really cool tool I found accidentally just by googling how to go about this. Using it with beautiful soup was kind of challenging at first because I was using code that did something completely different as a guide, but I managed to figure it out!

#### Jordan
- **What is done well:** It seems like you're doing a good job of handling the XML, scraping data from the internet rather than using a corpus must be much more annoying and it looks good!
- **What could be improved:** I have similar concerns to Juan, I'd like to know what specifically you're looking for. Splitting the episodes up by notebook makes it a little harder to read but if it takes a very long time to run the program it makes sense to split it like that. You might also consider using pickling if run speed is the issue, I decided to pickle all my data once my notebook started taking 5 minutes to run.
- **What I learned:** I learned about beautifulsoup, I'll definitely consider using it next time I need to scrape XML data.
- *Kiara*: Because this data is so hard to work with specifically because I have to do a lot of manipulation myself, I'm doing a more toned down analysis of the different speakers. Top bigrams/trigrams, etc. I want to see if I can try to get the computer to learn to produce sentences like each character, which hopefully works. I don't know if the characters speak differently enough, so analyzing speech that way will be really important. I originally wanted to do something a little different, but due to limited data available, this is the game plan. If I was doing this for fun and didn't have deadlines, I'd probably collect all different kinds of data (like audio and visual- body language would be such an important tell in Star Wars) and try to use that as well, because I think that would actually hold more information.

#### Anthony
- **What is done well:** I absolutely commend you for using BeautifulSoup and web scraping at the same time (although I guess BS4 is kinda' made for that? Anyway). They're both things that we haven't really gone into practiced depth with in class, so kudos to you for being bold!
- **What could be improved:** Don't quote me on this because I'm not by any means an expert on BeautifulSoup, but I think you actually might not want to convert your "soup" into a plain string in cell 11. BeautifulSoup objects are useful because they preserve structural elements of what they're "brewed" from, and you might be able to use that to your advantage. I don't know if this is actually applicable, though, since I don't know what your raw data looks like!
- **What I learned:** That working with scraped data and using BeautifulSoup is not an easy task! Again, kudos to you for taking on the challenge.
- *Kiara*: Thank you! It's very weird but I have been having fun doing something new. So my raw data is literally just one long ass string. There's a bunch of stuff in it, but the format of the data is a string. One. String. It's made data collection/cleaning VERY weird because I have to find a way to split the string to be usable, but once I do it'll be easier (hopefully).

#### Joey
- **What is done well:** First of all, great topic. I don't have as much of a linguistics background as I imagine the rest of the class does, so I enjoy the projects that are on widely relatable topics most. More specifically though, I think that scraping the data from the web is very impressive. It will be much harder, but it'll definitely pay off in the long run in terms of the knowledge you gain.
- **What could be improved:** I find your lack of markdown cells disturbing... just a joke, but going off of previous comments that relate to some objectives being unclear, I feel that explaining what you're doing with more markdown cells would help remedy this a bit.
- **What I learned:** I learned what Beautiful Soup is! My knowledge of html and xml is rather limited, so I definitely applaud you for taking this approach. 
- *Kiara*: I was never very good with markdowns before because I wasn't used to them, so that's something I wanted to go back and change. I think I was waiting until I had something a little more concrete to add the cells, but I'm probably going to go back in now and then just update the cells whenever.