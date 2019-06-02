The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10
Attribute Information:
1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review
helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review# Apply-Naive-Bayes-on-Amazon-reviews

Objective:- 
1. Apply Multinomial Naive Bayes on two feature sets, one with BOW and other with TFIDF vectorizers.
2. Consider a minimum of 100k points for this assignment as the model runs very quickly.
3. Use AUC as a metric for hyperparameter tuning. And take the range of alpha values from (10^-4 to 10^4).
4. Find the top 10 features of positive class and top 10 features of negative class for both feature sets
note: please do submit both .pdf and .ipynb versions of your notebook
