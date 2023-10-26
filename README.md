# I2A2_2021_Sentiment_Analysis_Preprocessing
Overview
Welcome to the I2A2 NLP class challenge.

The purpose of this competition is to explore a dataset that contains information about the rating of an e-commerce website's product shopping experience. Your goal is to use the NLP techniques you learned to create a model capable of predicting the rating given by the user (1 to 5 stars) based on their comments.
Description
The dataset is a corpus which contains varied information, that it can be useful for several NLP/CL tasks.
The first that comes to mind is sentiment analysis. Sentiment analysis is the task of assigning a sentiment (or a position) to the content of a given text.

The complete corpus has 132,373 reviews, left by 112,993 different users regarding 48,001 unique products. The reviews were collected from January to May, 2018. All reviews submitted to the e-commerce website are present in the corpus. It means that one can find offensive language, repeated reviews and reviews composed by only one word in the present data. These kinds of reviews are often not accepted to be displayed on the website. So, this means that this resource is richer than one could get crawling the e-commerce website.
Evaluation
Submissions are evaluated on classification accuracy (the percent of labels that are predicted correctly) for every review. The sentiment labels are:

1 - negative
2 - somewhat negative
3 - neutral
4 - somewhat positive
5 - positive.

Submission File
For each ID in the test set, you must predict the corespondent rating based on the data of the record.
Dataset Description
The dataset contains more than 130k e-commerce customer reviews, collected from a e-commerce website between January and May, 2018. It offers rich information about the reviewer profile, such as gender, age, and geographical location.

Files
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
Columns
ID - the id of the review
submission_date - date/time - review submission date (format YYYY-MM-DD hh:mm:ss)
reviewer_id - string - unique reviewer id
reviewer_birth - integer - integer reviewer’s birth year
reviewer_gender - string - reviewer’s gender (”F” for female; ”M” for male)
reviewer_state - string - reviewer’s Brazilian State, according to the delivery address
product_id - integer - unique product id
product_name - string - product name
product_brand - string - product brand
site_category_lv1 - string - product category (first level)
site_category_lv2 - string - product subcategory (second level)
review_title - text - review title, introduces or summarizes the review content
review_text - text - main text content of the review
recommend_to_a_friend - string - boolean value (Yes/No) indicating if the reviewer would recommend the product to his/her friends
rating - integer - overall customer rating, from 1 to 5
