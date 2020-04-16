# Guestbook for [Arabic Learner Corpus Considerations](https://github.com/Data-Science-for-Linguists-2020/Arabic-Learner-Corpus-Considerations)
**Anthony Verardi | Spring 2020 | University of Pittsburgh**

Welcome to my project! I'm investigating the [Arabic Learner Corpus](https://www.arabiclearnercorpus.com/)
to see what kinds of questions it might be useful for answering. My main idea right now is to play around
with the data and let insights emerge from there instead of trying to explore one question in particular.
Currently, I'm working on loading my data into a usable format. Feel free to sign the guestbook below and
leave some feedback!

* Project Links
  * [Project Plan](https://github.com/Data-Science-for-Linguists-2020/Arabic-Learner-Corpus-Considerations/blob/master/project_plan.md)
  * [Data Samples](https://github.com/Data-Science-for-Linguists-2020/Arabic-Learner-Corpus-Considerations/tree/master/test_data)
  * [Data Analysis (WIP)](https://github.com/Data-Science-for-Linguists-2020/Arabic-Learner-Corpus-Considerations/tree/master/data_analysis)

## Feedback

### Natasha's Feedback (3/2/2020)
- **What I liked**: Honesty your thoroughness and explanation of the material is what I strive for in this class. You really explain your project and data in great detail so even someone who might have no context for the project can understand it well.
- **What could be improved**: There are some points where a lot of text is flashed on your notebook which might be jarring and take away from the relevant data that you are looking at. Maybe clipping how much you show can get your point across without distracting from the real data you want to show.
- **What I learned**: I started to see what the process might be for working with non-Roman characters in python and i'm excited to see more of how that works! I also learned some interesting things about the Arabic language and how the data includes native speakers of a different dialect of Arabic.

*Anthony says (4/1/2020): thanks for the feedback, Natasha, and your extremely kind words! I totally hear you re: the length of some of my cells, will work on it.*

### Sean's Feedback (3/3/2020)
- **What I liked**: You can definitely tell you put the time in. Very well organized, great methodology, and important linguistic variation consideration. I really enjoy the style your NB's are in, keep it up!
- **What could be improved**: I would say there is one or two cells with a *lot* of text, so maybe don't flash in those cases. Other than that things look great! I also wanted to mention that I think Stanford's POS tagger/NLPcore would be perfect for your project, as it's widely cited in academia and handles Arabic (what kind of Arabic, I do not know). Here's the link: https://nlp.stanford.edu/software/tagger.html
- **What I learned**: I learned a lot about how difficult it is to do work with XML files, and also how difficult research in a macro-language can be. Best of luck, hope Beautiful Soup works for you!

*Anthony says (4/1/2020): Thanks for the feedback and the well-wishing, Sean! Beautiful Soup is cooperating now, so hopefully I'll have something cool to show off soon.*

### Lindsey's Feedback (4/1/2020)
- **What I liked**: A fellow non-Roman project! Even just the idea of the project is interesting. I love that you're *testing* this resource rather than just using it for some other project. Also, everything is so clear and organized so despite my lack of knowledge towards literally anything about Arabic, I know what's going on.
- **What could be improved**: Like the two above me said, there's a lot of text going on in that first Notebook. It's feedback you've gotten before, so I'm sure you're going to take that into consideration as you move forward. It's really hard to find anything else that could be improved upon because your organization and explanation is phenomenal.
- **What I learned**: To echo Sean a bit: I learned about handling XML and the challenges of it. I considered working with an XML corpus but didn't want to go through the trouble, so I commend you for that. I also learned some little bits about Arabic in general, like how you mentioned that object pronouns can attach to verbs as suffixes.

*Anthony says (4/15/2020): Thanks, Lindsey! I really need to figure out how to trim down cell output :) it'll be a step I circle back to once all the main work is done, probably.*

### Kiara's Feedback (4/2/2020)
- **What I liked**: I'm always really impressed with your work because it's usually very well organized and you explain EVERYTHING you're doing which means it's easy to follow along with.
- **What could be improved**: You explain EVERYTHING which means sometimes there's a lot of text that doesn't really do much BUT I'd rather have it than not. It's kind of fun to read your very much so Na-Rae inspired comments, but just keep in mind you have a LOT of text there.
- **What I learned**: It was really cool to see you use beautiful soup with XML because I'm using it with HTML. Your data is organized very much so differently than mine, so I liked seeing how you cleaned and organized your data.

*Anthony says (4/15/2020): Ha, yes, my commentary is indeed very much in the spirit of Na-Rae! I think it's the former language teacher in me coming out and really trying to make things as clear as possible for the reader. Thanks for the feedback!*

### Jordan's Feedback (4/14/2020)
- **What I liked**: Like Kiara said, your organization is top notch. Everything is very readable and easy to follow.
- **What could be improved**: Honestly, I'd say the amount of text you use is fine, not excessive.
- **What I learned**: Beautiful soup! It seems like it can real pain to use and it's nice to see it in action.

*Anthony says (4/15/2020): Thanks for the supportive feedback, Jordan!*

### Juan's Feedback (4/15/2020)
- **What I liked**: I think it's nice that you started with a broad focus that you progressively narrowed down. Building a classifier is a good application of what we have done in class. As others have noted, your code is very clearly documented so as a reader it is quite easy to follow. Also kudos for handling a language that doesn't use a Latin-script alphabet.  
- **What could be improved**: Regarding your (WIP) classifier training and analysis notebook, I agree that combining features could be useful to make the classifier more accurate. The classifier might not be doing as badly as you think, though, if you calculate the baseline based on the number of labels you have (many). An alternative might be to make the labels binary.  
- **What I learned**: The use of `BeautifulSoup` (and the handling of the `.xml` files in general) was highly informative and applicable to other projects.

### Joey's Feedback (4/16/2020)
- **What I liked**: I get the sense that your data almost guided you to new areas of research as your project progressed if that makes sense. Basically, I like that you didn't try to make your data something it was not, and adapted to logistical concerns that you had such as L1 disparity.
- **What could be improved**: You touched on it in your 3rd report, but I think further generalizing the L1's as native and non-native would be helpful for what you're trying to do. I think this would be the best way to address your original hypothesis.
- **What I learned**: I thought that your l1_fam() method was really informative, especially because I don't really know a lot about different languages, generally speaking. I always thought that language families were interesting when I learned about them in Intro to Linguists.
