# Domain - Education


Business challenge/requirement:
The University has data of Math, Physics and Data Structure  score of sophomore students. This data is stored in different files. The University has hired a data science company to do analysis of scores and find if there is any correlation ofscore with age, ethnicity etc.

Key issues:
Ensure students identify is not revealed to the agency and only relevant data is shared

Business benefits:
University can get more students enrollment by improving its international ranking through personalized course/curriculum for students

Approach to Solve:
1.Read the three csv files which contains the score of same students in term1 for each Subject
2.Remove the name and ethnicity column (to ensure confidentiality)
3.Fill missing score data with zero
4.Merge the three files
5.Change Sex(M/F) Columnto 1/2 for further analysis
6.Store the data in new file –ScoreFinal.csv

