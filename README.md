# Big5PersonalityModel

The [Big 5 Personality Model](https://en.wikipedia.org/wiki/Big_Five_personality_traits) is a grouping of personality traits based on factor analysis of survey data. For a more thorough introduction to the model, and to the particular set of survey data I used, see '1_Exploratory_Data_Analysis.ipynb'. This notebook also covers the steps I took to clean the data, and contains simple visualizations of the relationships between the survey questions.

In '2_Factor_Analysis.ipynb' I use factor analysis on the survey data to re-derive the 5 traits. I then try to split each trait into sub-traits, again using factor analysis. Finally I compare the Kaiser rule to parallel analysis, based on how many significant factors each finds, and the quality of those factors.

Lastly, in '3_Predict_Survey_Results.ipynb' I train some simple machine learning models to predict how people answer certain questions in the survey based on their answers to other questions.
