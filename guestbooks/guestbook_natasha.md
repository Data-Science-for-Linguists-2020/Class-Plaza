## Natasha's Guestbook
Welcome to my guestbook!! My project is Twitter Positivity Analysis

(3/2/2020) Unfortunately my repo is a little empty as I am catching up on some late work!

---

### Lindsey's Feedback (3/2/2020)
- **What I liked**
    - This project topic is incredibly interesting to me. Testing to see if social media (Twitter specifically) is growing more negative for one reason or another is not only doable but intriguing to the degree that I want to check this out a bit myself. I feel like Twitter has indeed gotten more negative over time because of the political climate, etc. But maybe your project will prove me wrong!
- **What could be improved**
    - README.md could be a little more detailed. It just seems lacking compared to some of the other projects' READMEs. Unfortunately, there also isn't very much in your repo right now for me to even comment on at the time of writing this (Monday evening, around 9:30pm), so there isn't much else to say.
- **What I learned**
    - See above; since there's not much in your repo, there's not much I can say here. You did mention in your project plan that there might be a thing in NLTK for Twitter processing. After double checking with a Google search, I did learn that there is something in NLTK that processes Twitter data.

## Kiara
- **What I Liked**
    - From what we've talked about in class, I really liked your project and as a Twitter user, this is especially interesting to me because I have personally witnessed several changes other Twitter users have gone through. I think Twitter has gotten more negative in certain senses- like politics, but I think it's also gotten a lot better. Usually when a negative tweet goes viral, a more positive "let's not be assholes" response tweet gains even more popularity, so I feel like although there IS negativity, younger people are actually more focused on positivity. I can't wait to see your results!!!!
- **What could be improved**
    - There's not much info to go off of, so I don't have much to say. I guess just getting started?
- **What I learned**
    - I haven't really learned anything because there's not much there, but I'm excited to learn about any tools you might utilize (like NLTK). I'm also really eager to see how this project goes!!

## Juan (3/31/2020)
- **What I Liked**
  - I find all of this quite interesting because I like Twitter a lot myself. You make good use of libraries such as `os` and you document the process well. I also think you made great use of regular expressions for data cleaning here (and there was a lot of cleaning involved, so kudos for that!). The results will be quite interesting to read.
- **What could be improved**
  - `langdetect` appears to be more effective with 2011 data (which you do note), maybe you could take a closer look at that subset of the data (or the `langdetect` options) to see what's going on. For analysis, have you considered removing stop words? This is also something you can test when you try to improve your classifier's accuracy.
- **What I learned**
  - It is the first time I have read about the `langdetect` library. It's not something I need for any project as of now, but it might come in handy if I need to work with multilingual data down the road. The use of `os` also illustrated some of that library's capabilities.

*Thanks for your feedback! I'm currently looking at how "text lingo" and shorter tweets can be classfied more accurately. I really like the idea of removing stop words and I think that might solve a lot of issues I'm having.*

## Jordan
- **What I Liked:** I really liked the sections comparing language use between the 2011 and 2019 twitter datasets, it's interesting how much things like this can show about social change over time. Your notebook is also very well presented and easy to follow.
- **What could be improved:** This probably couldn't be improved without draining massive amounts of time from the rest of your project, but it looks like quite a few non-english tweets slipped through the cracks. Just a thought, but comparing tweets to an English wordlist might help you sift out the stragglers.
- **What I learned:** The langdetect library seems useful, but at the same time not the most effective on small texts at least. I'm going to check it out, seems like it could be applied to many corpus linguistics problems. 

*Thanks! Yeah, I had found a couple libraries other than langdetect. I thought given the massive size of my initial corpus (15 million... oof) that it would be okay if a few slipped through. But since I trimmed it down midway it is definitely worth reassessing if langdetect is right for me!*

## Anthony (4/15/2020)
- **What I liked:** I think it's really cool that you're working to refine and expand an already-extant dataset along the lines of the original! Especially given that it contains so much data in languages other than English that might pose some really unique challenges, which you've done a really thorough job of documenting and accounting for; kudos!
- **What could be improved:** Now that we've worked with a lot of other types of classifiers for homeworks, you might want to consider trying a different model instead of the NLTK implementation of Naive Bayes!
- **What I learned:** Just how messy Twitter data can be, oof. It's a jungle out there and I have massive respect that you're trying to wrangle it instead of just tossing out the non-English data. Again, major props.

## Joey's Feedback (4/16/2020)
- **What I liked:** I also worked with Twitter data, however I chose not to scrape it manually. Choosing to get the raw twitter data using tweepy was definitely more difficult than the route I took, so I commend you for that.
- **What could be improved:** I'm sure this will be improved as your analysis continues, but more markdown cells in your analysis notebook would definitely help you. You're code is a little verbose at time, which is perfectly fine if it works, but explanation in plain english will help your project stand out.
- **What I learned:** Similar to what Anthony said, I learned how much extra stuff there is when you scrape raw Twitter data (there were 161 columns in your original scrape!) so again, well done for dealing with this.
