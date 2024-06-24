# Keywords and Sentences to Predict Stress
## Source:
- The dataset is available on Kaggle.com here: https://www.kaggle.com/datasets/ruchi798/stress-analysis-in-social-media
## EDA and Data Cleaning
- This dataset did not have much EDA from me on it due to its size and how difficult it would end up being to answer the question I was interested in finding.
- The dataset had several columns that I did not need, so I made a list of integers that would correspond with the axis locations and drop all of those columns.
- From there I began thinking of a python function I could make that would count the words and the number of times they appear in the text column. Originally I was thinking of a for loop that would be applied to the function which out create a dictionary key and value. The key would be any new word that would appear and the value would be +1 whenever that word appeared after it had been added. Then I wanted to come up with some way that could pull out the sentences and create a new series or dataframe of those sentences that have those common words and perform an analysis on that.
- After thinking on it I decided it would take too long to create and test and get it to work, so I moved on to another dataset.
## The Future
- A goal for me personally will be to come back to this dataset and create the way that I wanted to perform an analysis on it.