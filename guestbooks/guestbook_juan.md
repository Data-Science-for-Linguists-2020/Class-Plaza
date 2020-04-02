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
___
* **Anthony's Feedback**
  * Your work has always been exceptional in its thoughtfulness and the care you take with your methodology and your decision-making always shines through. Removing lexicalized forms of your diminutive targets that have acquired new word senses is a good move, and I'm glad to see it included as a step.
  * You're working with a *lot* of varieties here, and it would probably be helpful to readers to include a full key of which abbreviation maps to which variety at the top of [your analysis notebook](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity/blob/master/code/cleaning_analysis.ipynb) (I do see it in a code section, but a more prominent mapping in a markdown cell might be handy). I'm also wondering if you may want to rethink the label of figure 3. "Usage of -illo and -ito by country" because it's not clear to me if this reflects actual usage by speakers or if it's a reflection of the fact that Castellano is the most frequently observed variety in your dataset. Something like "usage of -illo and -ito in [corpus name] by country" may be more accurate.
  * I'm definitely going to be studying your data wrangling moves! You've got a real knack for handling dataframes and their content and it's been a great learning experience reading through this.