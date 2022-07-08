# -Sentiment-Analysis-on-Hotel-Reviews
Classification of hotel reviews on positive and negative class by using sentiment analysis


The dataset was retrieved through Kaggle and included around 20.000 reviews gathered from TripAdvisor. The information included was the review of the customer, as well as the relative rating, which was a range of 1-5. For performing the analysis, the Knime analytical tool was selected.

## Classes Generation

We classified the reviews that have a value equal or greater than 4 as positive, while all the others should be considered negative. From this process more than 15.000 reviews were characterized as positive, while the others as negative.

## Pre-Processing

Except for the tokenization and stopwords removal, we also proceeded in removing punctuation and stemming the words

## Transformation

Bag of Words, TF and TF-IDF were implemented

## Classification Algorithms

For the classification task five algorithms were selected and trained.

## Extra Techniques

Since we had imbalanced data for class, we also tried oversampling the minority class and undersampling the majority class, so as to see if any improvement occurred in the accuracy of out models.


The data set was analysed through the KNIME software
