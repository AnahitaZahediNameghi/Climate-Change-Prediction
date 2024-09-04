Sentiment Analysis Task)

Overview:
This project involves analyzing tweets about climate change to predict the sentiment expressed in each tweet. The dataset includes three columns: Tweet ID, message, and 
sentiment, with sentiment as the target variable. The sentiment column contains four unique values: -1, 0, 1, and 2, representing different sentiment classes.

Dataset:
•	Tweet ID: Unique identifier for each tweet.
•	message: Text of the tweet, containing opinions about climate change.
•	sentiment: Target variable with four possible values: -1: Negative; 0: Neutral; 1: Positive; 2: Very Positive

Approach:

1.	Data Preprocessing)
The message column was vectorized using one specific method:
TF-IDF Vectorization: Converted the text data into numerical features.

2. Model Building)
Logistic Regression
MultinomialNB

3.	Additional Analyses)
oNamed Entity Recognition (NER): Extracted entities such as persons, locations, and organizations from the text.
oCorrelation Analysis: Investigate the relationship between sentiment, text length, and the number of links in the tweets.

Steps Taken:
1.	Vectorization: Applied TF-IDF converting text data into numerical features.
2.	Model Development: Built and evaluated several machine learning models using TF-IDF.
3.	Evaluation: Assessed model performance based on metrics such as precision, recall, and F1 score.
4.	Exploratory Analysis: Examined the correlation between sentiment, text length, and the number of links.

Results:
•	Detailed results and performance metrics of the models are documented in the project report.
•	Key insights from the NER and correlation analysis are also included.

Dependencies:
•	Python 3.12.0
•	Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, spacy, re

Usage:
1.	Data Preparation: Load the dataset and preprocess it as described in the approach section.
2.	Model Training: Train the models using the provided scripts.
3.	Evaluation: Evaluate the performance of each model using the provided metrics.
Contact:
For questions or further information, please contact [Anahita Zahedi Nameghi] at [AnahitaZahediNameghi@gmail.com].
