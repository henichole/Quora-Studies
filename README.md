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

# Image 1: Originality Score Ranking By Topic(Interactive Graph Link: https://public.tableau.com/app/profile/ao.he/viz/QuoraTopicsOriginalityRanking/TopicRanking )
(Score interpretation: a score of 0.3882 shows a 38.82% confidence rate of human-generated content, and a score of 0.9446 shows a 94.46% confidence rate of human-generated content, according to Originality.AI v2.0)

The topic “Refunds” has the lowest originality score of 0.3882, and the topic “Sports” has the highest originality score of 0.9446.

Top ten AI-generated topics: 

“Refunds” - 0.3882
“Essay Writing Help” - 0.4039 
“Sports Business” - 0.4659 
“Blogging” - 0.4556
“Photographs” - 0.5021 
“Brokers” - 0.5396
“Food” - 0.5698
“Bitcoin” - 0.5977 
“Social Media” -0.6463
“Funding” - 0.6481


# Image 2: Yearly Average By Topic 2014-2020 (Interactive Graph Link: https://public.tableau.com/app/profile/ao.he/viz/QuoraOriginalityStudyByTopics/YearlyAverage2014-2020)

This image shows the yearly average originality score from 2014 to 2022. With originality scores of each topic recorded. 

1.
In 2022, the top topics of AI-generated content were “Refunds” 0.3882, “Food” 0.4742, and “User Experience” 0.7346, respectively.
In 2021, the top topics of AI-generated content were “Photographs” 0.5021,  “Social Media” 0.6463, and “Machine Learning” 0.7742, respectively.
In 2020, the top topics of AI-generated content were “Machine Learning” 0.6587,  “Democracy” 0.6992, and “Investing” 0.7557, respectively.
In 2019, the top topics of AI-generated content were “Sports Business” 0.4556,  “Blogging” 0.4659, and “Bitcoin” 0.5977, respectively.
In 2018, the top topics of AI-generated content were “Stock Markets” 0.7622,  “Scientific Revolution” 0.7983, and “Bitcoin” 0.8131, respectively.

2.
“Machine Learning” has appeared twice in 2020 and 2021, respectively, with originality scores of 0.6587 in 2020 and 0.7742 in 2021. 

3.
“Sports” has an overall originality average score of 0.9446, whereas “Sports Business” has an overall score of 0.4660, this is interesting to look at because if you take a look at the answers, the “sports” are mostly opinion-based, whereas for “Sports Business”, if you look at the questions:

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

These questions are more general, which would make it more tempting for authors to use AI tools to pull out supporting evidence. 

# Image 3: Monthly Average (Interactive Graph Link: https://public.tableau.com/app/profile/ao.he/viz/OriginalityScoreByMonthforQuora/OriginalityScoreByMonth）

There is no significant trend with monthly averages due to the unequal amount of data pulled from individual topics and time.



