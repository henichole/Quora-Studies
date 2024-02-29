# Project: AI-generated Contents on Quora.com

Questions:
1. Is there a rising or falling trend for AI-generated answers on the site during 2018-2023?
2. Which category has the most use of AI-generated answers?

Steps:
1. Explore the site Quora.com
2. Identify topics
3. Check the robots.txt
4. Proceed to build an API template, and determine the API tool. (BeautifulSoup, Selenium, Originality AI, etc.)
5. Data Collection
6. Determine the data structure, and clean the datasets (remove replications, sort out columns, etc)
7. Tableau Visualization and Data Interpretation

Data Interpretation:

A total of approximately 5900 inquiries and responses were extracted from various topic sections on Quora.com, ranging from areas such as health and science, political science and government, literature and writing, journalism and business, finance, technology and stocks, food, design, photography, and cameras. The dates of the inquiries and responses spanned from 2014 to 2024; for the years 2014 to 2022, only the year was documented due to Quora’s privacy regulations and user safeguards (a considerable number of opinions evolve, the historical inputs are accessible only when users permit them to be). 

The results are presented in the following Tableau Public sheets and dashboards. Please note that if you click on the interactive link, it would be easier to understand the trend.

# 1. Originality Score Ranking By Topic
(Interactive Link: https://public.tableau.com/app/profile/ao.he/viz/QuoraOriginalityStudyByTopics/TopicRanking?publish=yes)
                  
1. Score interpretation: a score of 0.3882 shows a 38.82% confidence rate of human-generated content and 61.18% AI-generated, and a score of 0.9446 shows a 94.46% confidence rate of human-generated content and 5.54% AI-generated, according to Originality.AI v2.0.

2. The topic “Refunds” has the lowest originality score of 61.18% AI-generated content, and the topic “Sports” has the highest originality score of 5.54% AI-generated contents.

3. Top ten AI-generated topics: 

   “Refunds” - 61.18% AI generated
   “Essay Writing Help” - 59.61% AI generated 
   “Sports Business” - 54.44% AI generated
   “Blogging” - 53.41% AI generated
   “Photographs” - 49.79% AI generated 
   “Brokers” - 46.04% AI generated
   “Food” - 43.02% AI generated
   “Bitcoin” - 40.23% AI generated 
   “Social Media” -35.37% AI generated
   “Funding” - 35.19% AI generated

4. “Sports” has an overall originality average score of 94.46% content, whereas “Sports Business” has an overall score of 46.60% human content. This is interesting to look at because if you take a look at the answers, the “sports” are mostly opinion-based, whereas “Sports Business” is mainly focused on FAQ-type queries that don’t require opinion-based answers. Here are some examples: 

   What sport has the lowest life expectancy?
   What sport has the lowest life expectancy?
   How much do professional sports balls cost?
   Why do so many highly paid professional athletes end up bankrupt only a few years after retiring from their sport?
   Should females be paid the same as males in sports?
   Why was wrestling the first sport that got the "pro wrestling" treatment (staged matches, gimmicky fighters) instead of other sports?
   Do athletes ever sign lifetime agreements with brands?
   Why do top-level athletes go broke after their careers?
   Why didn't Dan Marino (a football player) win a Super Bowl?
   Why do the best players in professional sports sometimes go unnoticed?
   
   These questions are more general, which would be tempting and easier for authors to use AI tools to generate answers. 

# 2. Yearly Average By Topics 2018-2022
(Interactive Link: https://public.tableau.com/app/profile/ao.he/viz/QuoraOriginalityStudyByTopics/YearlyAverage2018-2022?publish=yes)

This image shows the yearly average originality score from 2014 to 2022. With originality scores of each topic recorded. 

1. In 2022, the top topics are “Refunds” 38.82% human content, “Food” 47.42% human content and “User Experience” 73.46% human content, respectively.

2. In 2021, the top topics are “Photographs” 50.21% human content,  “Social Media” 64.63% human content and “Machine Learning” 77.42% human content, respectively.

3. In 2020, the top topics are “Machine Learning” 65.87% human content,  “Democracy” 69.92% human content, and “Investing” 75.57% human content, respectively.

4. In 2019, the top topics are “Sports Business” 45.56% human content,  “Blogging” 46.59% human content and “Bitcoin” 59.77% human content, respectively.

5. In 2018, the top topics are “Stock Markets” 76.22% human content,  “Scientific Revolution” 79.83% human content and “Bitcoin” 81.31% human content, respectively.

6. There was a significant drop in human-generated content from 2018 to 2019, with a score of 6.74 (total human content score of the lowest 8 topics) in 2018, and a score of 5.64 in 2019. 

7. “Machine Learning” appeared twice in 2020 and 2021, respectively, with 65.87% human content in 2020 and 77.42% human content  in 2021, which stated a slight increase in human-generated content between these two years.
   
8. “The Internet” appeared twice in 2021 and 2022, respectively, with 79.55% human content in 2021 and 90.16% human content  in 2022, which was also an increase in human-generated content between these two years.

# 3. Topic Study: Refunds (0.3882) Originality Score With Questions
(Interactive Link: https://public.tableau.com/app/profile/ao.he/viz/RefundsOriginalityScoreWithQuestions/Refunds0_3882?publish=yes)

1. Here, we can see that there are some interesting bipolar characteristics: It’s either all or nothing.

2. Some of the questions with 100% AI-generated answers (0% human content) are shown below: 

   “How can I get my money from a binary options scam?”
   “How can you learn faster?” 
   “How long does it take to get a refund from Southwest Airlines?”

   These questions are instruction-based, which would make it tempting and easier for humans to use AI tools to generate answers. 

# 4. Topic Study: Essay Writing Help
(Interactive Link: https://public.tableau.com/app/profile/ao.he/viz/OriginalityStudy-Quora-TopicEssayWritingHelp/OriginalityStudy-TopicEssayWritingHelponQuora_com?publish=yes)

1. There is no significant trend of increasing % of human contents from Jan 2023 to Jan 2024 (top left graph).

2. The top three authors with the highest originality scores are C.S. Friedman, Matthew Bates, and Sean Kernan, there is a trend, the more an author has answered, the higher the human content score. Authors with one input are more likely to have 0% human-generated content, compared to the top authors. These authors are also found active in other topics such as “Essays” on Quora.com with high human content scores.

3. Similar to the topic of Refunds, the contents are divided into two distinct categories: close to 100% human content and 0% human content.

# Results

1. Is there a rising or falling trend for AI-generated answers on the site during 2018-2023?

There is no significant rising or falling trend for AI-generated content on the site from 2018-2023. On the other hand, the AI-generated content score on Quora.com is found to be topic-based, due to a lack of consistency in the amount of data content scraped from each month.

2. Which category has the most use of AI-generated answers?

The top three categories that have the most use of AI-generated answers are: 
“Refunds” - 61.18% AI generated
“Essay Writing Help” - 59.61% AI generated
“Sports Business” - 54.44% AI generated
“Blogging” - 53.41% AI generated 
“Photographs” - 49.79% AI generated 
“Brokers” - 46.04% AI generated 
“Food” - 43.02% AI generated 
“Bitcoin” - 40.23% AI generated 
“Social Media” -35.37% AI generated 
“Funding” - 35.19% AI generated

3. Do users prefer to have AI-generated answers? If yes, to what extent?

As of now, this question cannot be answered, due to a lack of consistency in the amount of data content scraped from each topic. 




