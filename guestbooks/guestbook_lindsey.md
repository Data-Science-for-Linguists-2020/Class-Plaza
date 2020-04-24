## Analysis of Japanese Loanwords: Lindsey's Guestbook
Welcome to my Guestbook! As of now, I'm working on cleaning conversation data, hopefully to isolate each speaker's utterances from the .txt files. Any advice or critique is appreciated!
### Project Info
- [Repo Link](https://github.com/Data-Science-for-Linguists-2020/Analysis-of-Japanese-Loanwords)
- [Progress Notebooks](https://github.com/Data-Science-for-Linguists-2020/Analysis-of-Japanese-Loanwords/tree/master/progress-notebooks)
- [Data Samples](https://github.com/Data-Science-for-Linguists-2020/Analysis-of-Japanese-Loanwords/tree/master/samples)

### Comments

#### Juan

- **What is done well:** I think this project is super interesting! I don't know any Japanese but I understand the idea. You provide details about data acquisition and you thought about what bigger questions you could ask now that you have the data. Nice treatment of the NaN values. I think your notebook is also easy to read.
- **What could be improved:** How are you going to operationalize the sociolinguistic variables? That could have implications for the way you organize and manipulate the data as you move forward. We worked with Google n-gram data in Computational Linguistics so that's a good place to start if you do decide to work with n-grams later on. As a last note, why did you choose the frequency you did? You might need to normalize it for statistical analyses.
- **What I learned:** I learned what Katakana is and more about Japanese in general. Coding-wise, I learned more about handling null values.

*Re: Juan (4/1/2020) - Thanks for the feedback! I'm glad my notebook was easy to read - that's what I strive for. Sociolinguistic analysis will regard the ages of the participants and their conversation partners, but that's all I know right now. I chose the frequency I did mostly by freehanding it, which might not have been the best tactic, but that isn't to say I didn't think about why I chose the number I did. I skimmed through the lower frequency words on the spreadsheet and tried to find occurrences of less common words in the conversation files to get an idea of how common the words were in casual conversation. The word for "kangaroo" showed up someplace despite it being pretty low on the frequency scale.*


#### Kiara
- **What I liked**
    - I don't really know what's happening in your project because I don't know Japanese, but your whole project is organized really well and the explanations were really good, so it was easier to understand.
- **Possible improvements**
    - Since I really don't know much about Japanese or how it works, I'm afraid I can't offer much in way of improvements at this stage. Looking at Juan said, I agree with what he said, but I'd be lying if I said I came up with it myself.
- **What I learned**
    - I learned about Japanese! I had no idea what Katakana was, so that was really interesting to me. You also handled your data and null values using things I hadn't used before, so it was cool to see that being implemented. I also learned a lot from your data-cleaning process. Although our two processes will invariably differ exponentially, it was interesting to see how you did it.

*Re: Kiara (4/1/2020) - Glad you learned about Japanese! It's a very interesting language, and a difficult language to read thanks to how the Japanese borrowed a lot of Chinese characters into their language. Appreciate your honesty about not knowing much; there's a lot to know. Maybe I'll provide some more context in my README to accomodate for that? Katakana is super cool! It's really neat to investigate how non-Roman languages handle foreign words like this, similar to the way we write foreign words in Italics.*

#### Joey
- **What is done well:** Your code being so well documented makes following along with your data cleaning process very simple. I especially liked that your markdown cells are in a more narrative style, if you will, which gives the reader the opportunity to follow your exact chain of thinking.
- **Possible improvements** It seems like your project is going well, but I think some more background information would have been helpful. I'm not too familiar with a lot of the linguistic jargon you use, so even a simple glossary in one of your files would be helpful.
- **What I learned** So I did some more research and learned about Katakana, but I'm still a little fuzzy and would definitely like to learn more about it. From my current understanding, I think that Katakana is a set of characters that are derived from other languages, or is that too specific?
    
*Re: Joey (4/16/2020) - I see your comments about a glossary of some kind and understand completely; when all is said and done, I'll probably put some links in for further reading along with a simple definition of what's going on. You're close on the Katakana definition! The characters are very much Japanese characters, but they're made for (mostly Western) loan words and onomatopoeia. They stand out from other Japanese characters (something I'm going over in my presentation), so they're easy to pick out from a set.*

#### Jordan
- **What is done well:** It looks like you overcame the challenge of using katakana in Python, well done! Like other commenters have said, your code is well organized and easy to follow
- **Possible improvements:** Everything looks good in general but I would have liked to see more exploratory analysis just so that I can wrap my head around it better.
- **What I learned:** Your use of .startswith looks very useful, I'll keep that function in mind in case I need it in the future.
    
*Re: Jordan (4/16/2020) - .startswith was a lifesaver, honestly. It wasn't a fix-all because some lines started with an M or F but was really just one speaker referring to another, but it got the job done. Glad everything is easy to follow!*

#### Anthony
- **What is done well:** Your notebooks are sooooo well-formatted, Lindsey! Very readable and very easy to follow, I can clearly get a picture of your thought process as you're working on your project. Great job.
- **Possible improvements:** I totally get what you're talking about with "la" (ラ) in your analysis notebook. If you're familiar with Regex, it might be useful the word boundary functions here!
- **What I learned:** Lots about Japanese! I've never really looked closely at the distinctions between kanji, katakana, and hiragana, so it was fun to take a close look at one of them.
    
*Re: Anthony (4/16/2020) - Thank you so much! I try to make things easy to follow because I feel like getting down a thought process will help readers understand why I took certain steps with my process. I, sadly, am not too familiar with regex, but if I find some time to work with it, that's a good solution to the doublecounting issue I'm having.*
