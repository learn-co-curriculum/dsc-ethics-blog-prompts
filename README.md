# Data Science Ethics Blog Prompts
_A collection of prompts for blog posts about data science ethics created for Flatiron students._



## Data Privacy and Security
Suggested for Phase 1

__1. Aside from overtly illegal practices according to current legislation, data privacy and ethics calls into question a myriad of various thought experiments. For example:__
	* Should IP addresses or cookies be considered Personal Identifiable Information (PII)?
	* How should surveillance camera footage be handled? 
	* What about vehicles such as Google street view cars that capture video and pictures of public places? 
__Discuss your thoughts about:__
  * Should organizations be allowed to maintain massive databases of said information? 
  * What regulations are needed for these and other potentially sensitive datasets?


__2. Various legislation like General Data Protection Regulation (GDPR) has been introduced to manage user privacy and security in the data space. However, there is also an impetus on companies and users to take some accountability for the privacy and security of user data. Who do you think has the most power and/or responsibility to protect user data -- the [government](https://web.archive.org/web/20230121023603/https://www.congress.gov/bill/117th-congress/house-bill/8152/text), [companies](https://web.archive.org/web/20230125052204/https://www.wired.com/story/apple-photo-scanning-csam-communication-safety-messages/), or [users](https://github.com/arkenfox/user.js/wiki/4.1-Extensions)?__


__3. In GDPR, the standard for data collection is defined as "on a lawful basis". This includes:__
	* consent from the subject
	* to fulfill a contractual obligation entered into by the subject
	* to comply with the data collectors legal obligations
	* to protect the data subjects vital interests
	* for the public interest
	* to pursue the legitimate interests of the data controller
  __Do you think that the justifications for data collection listed above are sufficient to protect users? Why or why not?__
  


## Sensitive Features
Suggested for Phase 2

__1. Logistic regression and other algorithms are used to inform a wide range of decisions including:__
* [whether to provide someone with a loan](https://web.archive.org/web/20221230075448/https://themarkup.org/denied/2021/08/25/the-secret-bias-hidden-in-mortgage-approval-algorithms)
* [the degree of criminal sentencing](https://web.archive.org/web/20230106001145/https://www.nybooks.com/articles/2021/06/10/prison-terms-sentenced-by-algorithm/)
* [whether to hire an individual for a job](https://archive.is/pcw8a) 

__Choose one of the decisions listed above and discuss how historical bias might impact the underlying data and how this can impact the fairness of the model used to make the decision.__


__2. Another concern is that some features might not initially appear to be sensitive, but are actually highly correlated with a sensitive feature. For example, in the United States, geography is highly correlated with racial demographics. Considering this, a credit card company that uses zip code as a factor to decide how creditworthy an applicant is may end up unintentionally exhibiting racial discrimination. 
If you were a data scientist working for a credit card company and your employer wanted to include this feature in their model, how would you convince them that including the feature would be unethical? Provide some advice for fellow data scientists that might find themselves in this situation. Use [this guide](https://archive.ph/5TL6y) to help frame your advice.__



## Machine Learning Bias Blog Prompts
Suggested for Phase 3 and Phase 4

__1. The Boston Housing dataset contains a number of features that can be considered sensitive in isolation but can be especially problematic when combined. Selecting a combination of features might produce an analysis that is plagued by either measurement bias or algorithmic bias. Describe how the combination of features might lead to a biased analysis.__


__2. In the past, systems like the one used at St. George's Hospital Medical School in the early 1980s that docked applicants 3 points for being female and 15 points for being non-European applied bias to the algorithms they implemented. Research and summarize another case where blatant bias about a sample population was built into an algorithm and discuss how the disparate treatment caused a disparate impact on the affected sample population. Use the following questions and guidelines to help you:__
* Be sure to: 

	* List the decision maker(s) in the case you selected
	* Describe what went wrong 
	* In 2-3 sentences, explain the impact of the unethical decision(s)
	* Share any next steps or recommendations you think would be beneficial
	
* __In the example you choose, were unethical made from the beginning, or did behavior(s) change and become unethical after a certain point in time? Consider using a timeline or a list of dates to illustrate what happened.__


__3. Consider the following facts about the 2014 Facebook Emotional Contagion Study:__.   
_In 2012, Facebook's A/B testing tools as well as natural language processing (NLP) techniques were used to manipulate the news feeds of over 600,000 Facebook users. Some users had posts with "negative emotional content filtered out, while others had posts with "positive emotional content" filtered out, and then researchers measured the impact of these changes on the "emotional content" of those users' future Facebook posts._.  
__In the passage above, we learn that posts on a Newsfeed can be labeled with a positive or negative sentiment. Research what methods Facebook used to label the posts as positive or negative and discuss the impact that this might have on the study.__

