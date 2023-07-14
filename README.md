# PandasChallenge - external help 

I recieved help from my tutor to get started on the code and how to follow the logic. 
https://github.com/bernbr/pandas_challenge/blob/main/PyCitySchools/PyCitySchools_starter.ipynb
received helped with this code from AskBCS to get started on this code
# Calculate the total school budget and per capita spending per school
per_school_budget = school_data_complete.groupby("school_name").mean()["budget"]

per_school_budget

per_school_capita = per_school_budget/per_school_counts
per_school_capita
