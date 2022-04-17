# Exercise 4

In this exercise, you shall work with various collaborative filtering approaches. Specifically, you shall compare

- User based filtering

- Item based filtering

- One other model based filtering approach

You can reuse existing libraries and code examples (if you do so, please properly quote the origin, otherwise it has to be considered plagiarism), and you shall compare their performance in two ways

- Effectiveness of the recommendation on a supplied training set.

- Efficiency of the recommendation (i.e. runtime).



The dataset to be used is the MovieLens dataset. You shall first work with the smallest version available, with 100k ratings, at https://grouplens.org/datasets/movielens/100k/

To ensure that we can compare the results across all your peers in the course, you shall proceed as follows

- Split the dataset into 80:20 training:test set, after joining together an existing split, and shuffling the data; set the random seed to (the numberic parts of) your matriculation number. 

- For evaluation of effectiveness, we will utilise MSE (mean squared error) between the predicted score and the actual score known in the test set.



Your solution shall include the code, and a report on your findings , e.g. on

- Which methods worked well in regards to effectiveness and efficiency? 

- Are the result in general usable? 

- ...

Further, repeat the split 5 times with a different initialisation, and describe how stable your results are, respectively, how much the results change. You just need to set the random seed once, to initialise the random number generator, then subsequent splits will anyhow already be based on a different (pseudo-random) state, and thus won't yield the same split.



After the first step on the 100k database, obtain the next bigger version (1M, https://grouplens.org/datasets/movielens/1m/), and just test your algorithms for effectiveness - do the methods scale to the increased size? (If you have computational limitations for some methods, you may skip/reduce the 5 repetitions)