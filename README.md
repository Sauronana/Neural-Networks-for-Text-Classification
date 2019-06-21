### Update on 1st May, 2019:
Please note that Senator Michael Bennet has unexpectedly deleted his Twitter account recently in this week. This might cause a problem when reader tries to re-run my 4th code chunk where I scrape all the data. Please remove this senator from the dataframe named as "df" if needed. If similar scenarios occur, please follow the same instruction. 

# Reader Instructions:
* Candidate Number: 18106; Student Number: 201812256; Name: Jinna Sun
* Please find the final report in this github repository named as "ST449 Report Final - Jinna Sun (201812256)". 
* You may find the same report here via a Google Colab link. Anyone with this link is allowed to view. https://colab.research.google.com/drive/1MAn17nyQuvXlaak_OJcNZGrKjLlDEExi
* The additional file is a table containing 80 senators' Twitter usernames and their political party, which is used as a small part of the data in the report. This particular table was scraped from https://www.socialseer.com/resources/us-senator-twitter-accounts/ via Excel. 
* Anything below this line is previous memo with the course lecturer. 

---


# ST449 Course Projects

- This project accounts for 80% of the final mark.
- The project report is due on the 30th of April 2019.  

**MV 5 April 2019**: project topic approved; good to compare with other ML algorithms; make sure to implement and evaluate deep learning methods, e.g. feedfoward neural networks, but also recurrent neural networks would be suitable for your problem

I intend to use deep learning techniques to identify and classify US/UK politicians' tweets pattern, i.e. word choices, sentence structure, tweeting frequency and popularity level. Project goal is to be able to classify the politician who tweeted the given text to the greatest accuracy possible. Data will be scraped from Twitter using my own developer account credentials. I aim to use as many relevant knowledge acquired in this course without of course losing focus on the project objective. 

Should this topic be rejected, please email me at j.sun31@lse.ac.uk asap so that I can make rearrangements. 

Thank you. 

**MV Comments, 1 April, 2019**: could you explain a bit more what exactly is the problem to be solved. Is it to classify tweets with respect to their authors (learn the mapping between a tweet text and its author identity)? What deep learning models do you intent to use? Why scraping Twitter data while you may find some available to download in public domain? Are you going to be able to scrap a sufficiently large dataset for the purposes of your project?


**Reply, 3rd April, 2019**: Thank you for the follow-up. 

**Objective:** My original intention is to dive deep into a typical "text classification" problem. Inputs are text transformed into numerical representations, i.e. either a dictionary of word frequencies (a bag of words) or some indicator of text like average word length. Outputs are tags or categories to which the text belongs. In the twitter example, output will be the US politician who tweeted the tweet. 

**Data:** While I could use widely available online datasets such as movie reviews, email spams, I believe this tweets data is more interesting to me personally. My developer credentials allow for 3000 tweets per twitter user. I plan to scrape from all governors and senators, which should hopefully be enough for a method to be applied. That said, if the dataset turns out to be problematic, I will use online libraries instead. It does not change the nature of the objective. 

**Methods:** 
**1.** Machine learning based methods will be explored first. Non-deep learning methods like Naive bayes or support vector machine will be used for reference. Then I wish to dive deep into neural networks architectures. This will include but not limited to different activation functions (sigmoid, hyperbolic tangent...), different regularisation on loss functions, sparse representation, ensemble methods, drop out rates and optimisation algorithms. If I have time, I will also look into automatic hyperparameter optimisation algorithm in addition. 

**2.** Rule-based systems will then be studied. This will include some naive reinforcement learning policies. For example, with a initialised domain of train set, every word in the text will have a known tag, and the policy will classify based on tag frequency and update the acquired knowledge. This part will not be the center of the report.

**3.** Last I will make some efforts in combining these two methods as some sort of "hybrid systems" to see if the performance will be improved. 

**References will be designed in Harvard style and the report will be written in Python Notebook format. Please keep me updated on your advice and let me know if this topic is approved or not. Many thanks!**
