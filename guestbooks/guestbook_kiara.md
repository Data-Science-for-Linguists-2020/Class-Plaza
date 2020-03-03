## Star Wars Dialogue Analysis - Kiara
Welcome!! I was having a lot of issues with reading all the data in as a group, so for the deadline I switched to reading in files individually. I was following a tutorial, so once I'm done doing all of my work for Soudi and Karen, I plan on focusing on this project. I literally don't have anything in depth in the GitHub repo, so I apologize for that . The most detailed stuff is what I've done with the code so far, but even the final version of that never really got uploaded by the deadline. I have it, I just hadn't pushed it.
### Project Info
- [Repo] (https://github.com/Data-Science-for-Linguists-2020/SW-Dialogue-Analysis)
- [Code] (https://github.com/Data-Science-for-Linguists-2020/SW-Dialogue-Analysis/tree/master/code)

### Comments

#### Juan

- **What is done well:** This is an interesting project! Looking forward to the developments. So far I think the procurement of the data is well done.
- **What could be improved:** What variables are you planning to explore? That is to say, how are you going to operationalize "differences in speech" or "changes in speech"? The code for all notebooks reads "Episode IV" even though it's different episodes. To get all the data frames in the same notebook you might consider pickling them.
- **What I learned:** I learned about some useful tools (webdriver, BeautifulSoup) to extract raw text from websites.

#### Jordan
- **What is done well:** It seems like you're doing a good job of handling the XML, scraping data from the internet rather than using a corpus must be much more annoying and it looks good!
- **What could be improved:** I have similar concerns to Juan, I'd like to know what specifically you're looking for. Splitting the episodes up by notebook makes it a little harder to read but if it takes a very long time to run the program it makes sense to split it like that. You might also consider using pickling if run speed is the issue, I decided to pickle all my data once my notebook started taking 5 minutes to run.
- **What I learned:** I learned about beautifulsoup, I'll definitely consider using it next time I need to scrape XML data.
