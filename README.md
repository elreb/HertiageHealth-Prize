# Hertiage Health Prize - A Kaggle Data Science Competition

Heritage Health Prize was a Kaggle competition with a $500,000 prize, with the goal of identifying patients who will be admitted to a hospital within the next year using historical claims data. The data was composed of three years worth of insurance claims data across 6 tables. 

This analysis was a project of a big data course while I was a graduatate student at UC Berkeley, [Big Data In Public Health](https://classes.berkeley.edu/content/2019-Spring-PBHLTH-244-001-LEC-001). 

In the analysis, I used R to explore the data and start to combine and generate summary tables. However, I ran into some complications summarizing the large datasets due to the procedural nature of R and `dplyr`. So instead of breaking up the code, I loaded up an instance of Postgres to process and summarize the data. This would decrease compuational strain with SQL and set theory. I ended up using Gradient Boosted Machine algorithm for prediction and scored moderately well on the Kaggle Scoreboard. 


https://www.kaggle.com/c/hhp
