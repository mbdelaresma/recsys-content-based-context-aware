# UPNEXT: Content-based and Context-Aware Movie Recommender System

Advanced Data Mining Course Submission

See full report [HERE](https://github.com/mbdelaresma/recsys-content-based-context-aware/blob/main/Technical%20Report.ipynb)

![image](https://user-images.githubusercontent.com/71246479/188303488-78c9b174-ca88-4ffc-ac63-eebc18791a1c.png)

# Executive Summary

The growth of digital movie streaming over the years paved way to the creation of a huge amount of data containing ratings of users to movies, content metadata such as genre and title of movies, context of the user like gender age, and occupations 1 . Recommender systems are helpful in trying to predict the preference or the possible ratings of users for items that they haven't tried yet. In this technical report the team aims to answer How might we provide effective movie recommendations using several user specific features and movie features?

Using the MovieLens 1M dataset that contains movies from 1995 to 2015 and has million of anonymous ratings from six thousand users who rated at least twenty movies we explored the different characteristics of genre, age, occupation, and gender in terms of count and its average ratings. We found interesting insights such as older group tend to rate higher compared to the younger ones, demographics of the Movielens users, and drama as one of the most popular genre in the MovieLens. These content metadata and context of the users are used as features to our recommender system models.

The team developed content-based recommender system using genre and title as the features. We preprocessed the text using NLTK and converted it to machine readable representation using TF-idf. The TF-idf features are used to train our model based recommender system. The results that we got are similar to the user preference in terms of genre.

The team also developed several Context-Aware recommender system using genre, age group, and occupation. the recommendations made are more influenced by the filters set instead of the viewing or rating history. Using pre-filtering method, the model did poorly for some of the context used due to its effect on initial filtering of data. For both of the post filtering and contextual modeling, the results that we got performed well even on having multiple context at a time. The team also developed a combination of content based and context aware models by getting its weighted sum in order to get a more specific recommendation based on the content and context of the user.

For future studies, we suggested to use a larger dataset, try other models, and perform evaluation metrics to further validate the results.

# Contributors

dela Resma, Marvee

La Rosa, Patrick
