# Verde-Inc
First thing first, extracting useful information out of messy columns, here we have multiple datasets which are somehow related to each other, the most important part of data wrangling is dropping “unknow” column because its goanna make multicollinearity,because it is  extremely related to rest of genres!
In first question, I have been asked to guess the rating base on the genre and popularity:
I made a dataset and called it “rating popularity”, using ‘groupby‘ method and getting mean rating and count of view per movie(popularity).
I went a little bit further and wanted to show popularity and rating visually, what I see here; people tend to watch drama movies and the second popularity goes to comedy genre and the third to action genre! (It can be considered by production companies, the more view, the more revenue).
The thing is with considering the efficiency of my model, I guess genre of movies and popularity are not the only factor to decide and guess the rating, as it is apparent each genre has its mediocre, disaster and awesome movies.
Second question, predicting users rating based on genre:
I started it with making the best and proper data frame out of all the given datasets.
Before choosing and implementing the machine learning model I would prefer to show diagrams to see vividly what’s going on here! The biggest chunk of movies with genre of drama got rating 4, and people don’t have tendency to watch western movies (important to be considered). here random forest comes to play!
Predict what genre a user will watch based on their Zip Code:
The most interesting part of the whole assessment.
After preparing proper and suitable data frame out of what we have in hands, now how can I deal with the zip codes?
After dropping nonsense zip codes (zip codes contains alphabets) with the aid of “geopy” I converted them into longitude 