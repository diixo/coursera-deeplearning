# Structuring Machine Learning Projects

There was no course work in this 2. course, just quizzes

## Content

### Introduction to ML Strategy

Orthogonalization was a topic Andrew Ng emphasized in this regard. By that he meant doing one step at a time and focussing on parts that are not intertwined with each other seperately.

For example feature engineering can be considered being orthogonal to algorithm building.

### Setting up your goal
In this part he talked about the dev / train / test split. One important fact in this regard that stuck with me is that the test data should always be seperate. They should not used, when averageing in order to fill missing values. There shoud be no influence whatsoever from test to dev!

### Comparing to human level performance
Human performance is always a good yard stick when evaluating what you have achieved. Algorithms might be better then humans on certain tasks. But Human performance might also show where the limits for algorithms might be encountered. I am always thinking of the famous Titanic data example on Kaggle in this regard. In the end, live or death isn't totally predictable for the passengers, since there might be an influence of gender and status, such as women and children and first class passenger might have been priviledged, but there is also a part of pure luck of survival that can never be predicted.

### Error Analysis
