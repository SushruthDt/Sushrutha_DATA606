# UMBC DATA606 Data Science Capstone Project

## Capstone Project Proposal

Author : Sushrutha DT and Srikeerthi Upperla 

# FAKE NEWS CLASSIFICATION AND PREDICTION

![image](https://user-images.githubusercontent.com/98927072/153283455-74b6119b-51b2-4c09-a95c-f961c636b736.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------------

_**1.	What is your issue of interest (provide sufficient background information)?**_

Fake news on social media and other forms of media is widespread, and it is a source of serious concern because it has the potential to cause significant social and national harm, as well as have debilitating effects on individuals and communities. It has long been recognized that the authenticity of information is a problem that affects businesses and society in general, and that this is true for both printed and digital media. Fake news entails deliberate disinformation where false and misleading information is sowed to mislead, manipulate or harm for which there is invariably a large economic price tag attached. The year 2021 proved to be up to the task, beginning with the Capitol insurrection and continuing with a deluge of falsehoods and distortions about COVID-19 vaccines. 2021 proved to be up to be advent of new era as new social media apps like Tik-tok and other platforms came to rise. It is reasonable to assume that the global economy bears a cost of at least $78 billion per year from a growing number of small costs associated with fake news and larger incidents. Fake news' dangers and costs will only increase as technology improves, despite the best efforts of law enforcement.


_**2.	Why is this issue important to you and/or to others?**_

Personally, I've been a victim of fake news, particularly in the area of job rackets, where I received fake interview letters from recruiters claiming that if I paid up front, they would get me through the next rounds quickly, and the covid vaccination fiasco, where I was told that they were administering covid vaccine in a nearby government hospital, only to find out it was fake news and contract covid. Exam postponement is another example, as is fake news about the death of one of my favorite celebs.



**3.	Why is this important?**_

![image](https://user-images.githubusercontent.com/98927072/153283392-e9994172-1419-4541-9dc6-e5da6ef6f510.png)

The World Economic Forum ranks the spread of misinformation and fake news, as among the world’s top global risks. 
 
   o	**You deserve the truth** and are educated enough to make your own decisions based on the facts. 

   o	**False news erodes credibility** People will be less inclined to accept you if you base your arguments on incorrect data.

   o	**Fake news can harm you and others** Mercola.com and NaturalNews.com, for example, help promote misconceptions that HIV and AIDS are unrelated, or vaccines cause autism. These sites are dangerous and heavily trafficked.

   o	**Real news can help** If you wish to invest in a company, you should study factual articles about it. A voter should research a candidate thoroughly before casting a ballot to ensure that the candidate best represents his or her views. Real news may help you generate money and make the world a better place.


_**4.	What questions do you have in mind and would like to answer?**_

It is an important skill to be able to distinguish between accurate news and fake news, and one that you will use for the rest of your life. Our research investigates various textual properties that can be used to distinguish between fabricated and authentic content. In order to take advantage of these characteristics, we train a combination of different machine learning algorithms using various ensemble methods, and then evaluate their performance on real-world datasets. It is our goal to distinguish between fake and true news by developing powerful classification models for the news data we have gathered so far. 

•	**Spot if next submission of author is fake or**

•	**Extensive EDA of news**

•	**Suspicious titles that can be tagged to fake** 

_**Size of the dataset** :_ 123.81 MB

_**Shape of the dataset** :_ (20800, 5)

**train.csv**: A full training dataset with the following attributes:

**id** : unique id for a news article


**title**: the title of a news article


**author**: author of the news article


**text**: the text of the article; could be incomplete


**label**: a label that marks the article as potentially unreliable


   1: unreliable


   0: reliable


**test.csv**: A testing training dataset with all the same attributes at train.csv without the label.

**submit.csv**: A sample submission 


_**5.	What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?**_

Here the unit of analysis is : Author / News organizations. 


_**6.	What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?**_

![image](https://user-images.githubusercontent.com/98927072/153284147-31b435f7-b2a2-4b44-8505-f91a156f7967.png)

I would mostly like to concentrate on – title, author and text from the dataset. 

_Title and Text:_ 

Does all the fraudulent news have repetitive jargon? Is there a pattern? 
What keywords are highly used in fake news?

_Author:_  

Are most of the fake news generated by the same author? Is there a pattern?
Predict if the following edition of the author would be fake.

_**7.	What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?**__

The sensationalism of not-so-accurate but eye-catching and intriguing headlines to retain audiences' attention to sell news has persisted throughout all sorts of information broadcast history, which, as conferred above, has many muted issues; thus, we would like to classify and predict fake news for which I plan to use the following models:

•	Logistic Regression


•	Multinomial Naïve Bayes


•	Passive aggressive classifier 


•	Support Vector Machine


•	Decision Trees


•	KNN

_**8.	How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?**_

As the project aims to classify and predict Fake news, I would be considering this as more as a classification problem and thus would work on generating the Classification report that is used to measure the quality of predictions from a classification algorithm—the precision, AU- ROC, recall, F1 Score, and our trained classification model support. We plan to use visualization techniques to compare the performance and better understand each model's metrics.

_**9.	What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practical applications, etc)?**__

This project aims to develop a solution that users can utilize to detect and filter out news containing false and misleading information. The plan is to carefully select features to identify fake posts/news.

