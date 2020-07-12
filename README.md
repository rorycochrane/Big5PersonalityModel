# Big5PersonalityModel

The [Big 5 Personality Model](https://en.wikipedia.org/wiki/Big_Five_personality_traits) is a grouping of personality traits based on survey data. For a more thorough introduction to the model, and to the particular set of survey data, see '1_Exploratory_Data_Analysis.ipynb'.

In '2_Factor_Analysis.ipynb' I use factor analysis on the survey data to re-derive the 5 traits. I think try to split each trait into sub-traits, again using factor analysis. Finally I compare the Kaiser rule to parallel analysis, based on how many significant factors each finds, and the quality of those factors.

Lastly, in '3_Predict_Survey_Results' I train some simple machine learning models to predict how people answer the survey based on their other answers.
