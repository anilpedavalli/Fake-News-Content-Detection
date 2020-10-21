# Fake-News-Content-Detection
Fake news, defined by the New York Times as “a made-up story with an intention to deceive”, often for a secondary gain, is arguably one of the most serious challenges facing the news industry today. In a December Pew Research poll, 64% of US adults said that “made-up news” has caused a “great deal of confusion” about the facts of current events  In this hackathon, your goal as a data scientist is to create an NLP model, to combat fake content problems. We believe that these AI technologies hold promise for significantly automating parts of the procedure human fact-checkers use today to determine if a story is real or a hoax.

# Dataset Description:

Train.csv - 10240 rows x 3 columns (Inlcudes Labels Columns as Target)
Test.csv - 1267 rows x 2 columns
Sample Submission.csv - Please check the Evaluation section for more details on how to generate a valid submission
 

# Attribute Description:

Text - Raw content from social media/ new platforms
Text_Tag - Different types of content tags
Labels - Represents various classes of Labels
Half-True - 2
False - 1
Mostly-True - 3
True - 5
Barely-True - 0
Not-Known - 4

# Skills:

NLP, Sentiment Analysis
Feature extraction from raw text using TF-IDF, CountVectorizer
Using Word Embedding to represent words as vectors
Using Pretrained models like Transformers, BERT
Optimizing multi-class log loss to generalize well on unseen data
