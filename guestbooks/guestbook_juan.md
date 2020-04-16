## Juan's guestbook

Welcome to my guestbook. As of now I am mainly working on cleaning up the data and creating data frame objects from it. You can find a link to the repository and relevant directories/files below. All feedback is welcome. Thanks!
- **Information about the project:**
- Project title: Diminutive Suffix Productivity
- [Repository](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity):
  - [code](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/tree/master/code)
  - [data_samples](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/tree/master/data_samples)
  - [project_plan](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/blob/master/project_plan.md)
  - [progress_report](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/blob/master/progress_report.md)
___
* **Joey's Feedback**
  * There's much to compliment here. Your introduction is informative, your code is overall well organized, and not only did you do a good job at cleaning up the data, I thought that defining methods for each step of the process that you can use for your other files was brilliant. Very well done.
  * One place in which I could foresee improvement is with the actual processing of the data. It seems that, other than removing the irrelevant rows, you're not doing much to add to the dataframe. Maybe you don't need to, so if you don't then disregard this, but it seem's like you could make the dataframe even more presentable, possibly by refining the POS column.
  * I made a similar comment in Jordan's guestbook, but your code helped me further understand the pickling process. Especially because the scale of your code will be so great once you've processed the other styles, I can see why making your data more persistent over multiple kernels and notebooks will be helpful.
    * Juan's response: Thanks for your feedback! I'll definitely try to make a new, more informative column POS column.
___
* **Jordan's Feedback**
  * You've done a great job of wrangling pretty messy data into a format you can use for this project. I agree with Joey, the methods you wrote are going to make processing the rest of the files much easier.
  * I don't really see anthing that could be improved here, I noticed that some verbs like 'necesita' were getting into the dataframe but you already have a plan for this. With the POS tags it'll be easy, only nouns can take diminutives.
  * The syntax of your method remove_redacted is interesting, I might need to use something similar for my project. I've been using the .drop() method and the way you're doing it seems much more elegant.
    * Juan's response: Thanks for your feedback! Spanish is a bit tricky because adjectives and even a (limited) set of adverbs can take diminutives too, but you're right in suggesting the use of the POS column as a way to handle the issue.
___
* **Sean's Feedback**
  * First of all, love the .md style. You go beyond just making it look good, rather it *is functional and adds to the organization*. I enjoyed how you set up the background in the project_plan. It was obvious not only what you were doing, but the inspiration for and potential applications of your project.
  * Small heads up, your project_plan file has dead hyperlinks at the top. Little typo in your first project report "(shut out)". Couple of little things like that, but I'm sure you'll clean it up after the term! Honestly I can't think of any other critiques than echoing what Joey said. Great job!
  * This was an awesome project to read through because it's a step by step blueprint through checking somebody else's findings and applying literature outside of the classroom. Slightly more big picture, but I'm really impressed with how comprehensive yet coherent the project is.
    * Juan's response: Thanks, Sean! I'm glad you liked the project. Also thanks for noticing the typos and broken links, I've gone over those now.
___
* **Anthony's Feedback**
  * Your work has always been exceptional in its thoughtfulness and the care you take with your methodology and your decision-making always shines through. Removing lexicalized forms of your diminutive targets that have acquired new word senses is a good move, and I'm glad to see it included as a step.
  * You're working with a *lot* of varieties here, and it would probably be helpful to readers to include a full key of which abbreviation maps to which variety at the top of [your analysis notebook](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/blob/master/code/cleaning_analysis.ipynb) (I do see it in a code section, but a more prominent mapping in a markdown cell might be handy). I'm also wondering if you may want to rethink the label of figure 3. "Usage of -illo and -ito by country" because it's not clear to me if this reflects actual usage by speakers or if it's a reflection of the fact that Castellano is the most frequently observed variety in your dataset. Something like "usage of -illo and -ito in [corpus name] by country" may be more accurate.
  * I'm definitely going to be studying your data wrangling moves! You've got a real knack for handling dataframes and their content and it's been a great learning experience reading through this.
    * Juan's response: Thanks for your feedback, Anthony! I'll consider adding some kind of legend to the plots so that it's easier for the readers to distinguish varieties. Regarding your last comment, that was only a preliminary token count which indeed reflects that Peninsular Spanish is the largest variety in the data set. The plots in the [new notebook](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/blob/master/code/statistics_analysis.ipynb) are more illustrative of differences between varieties.
___
* **Kiara's Feedback**
  * I am always so impressed with anything you or Anthony do. I love how neat and clean everything looks. You explain everything well. I can't really add anything else that hasn't already been said.
  * Just echoing Sean's critique about the dead links (this time in your statistical analysis notebook- not super important, but maybe check all of them after the semester ends) and Anthony's idea about the full key of abbreviations (which you already acknowledged, so I'm just being redundant).
  * Honestly, I learn so much any time I read through your assignments. I can't point out anything specific, but I like taking notes any time you and Anthony turn in assignments. I learn *so* much.
    * Juan's response: Thanks for your very kind feedback, Kiara!
___
* **Lindsey's Feedback**
  * Everything is so clean! You take the time to explain everything you're doing. It's hard to know what's going on from just code, so staying documented like you have been makes everything pleasant for now and will likely make for a pleasant reader experience in the future in case anyone comes across this project.
  * I can't find much to criticize here. When I'm looking at your plots, though, it's hard to tell which varieties are which based on abreviation, but cell 3 in `cleaning_analysis` was helpful in figuring out which was which. It's a redundant criticizm, but a glossary/key would be helpful.
  * I learned a ton from your statistics notebook. I didn't exactly know what you meant by "productivity" but those explanations helped me understand it a bit more.
    * Juan's response: Thanks, Lindsey! I'm glad you enjoyed going through it. I added some more information about morphological productivity to the project plan and `README.MD` now so that it's clearer.
