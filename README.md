# Fake-News-Content-Detection
Fake news, defined by the New York Times as “a made-up story with an intention to deceive”, often for a secondary gain, is arguably one of the most serious challenges facing the news industry today. In a December Pew Research poll, 64% of US adults said that “made-up news” has caused a “great deal of confusion” about the facts of current events  In this hackathon, your goal as a data scientist is to create an NLP model, to combat fake content problems. We believe that these AI technologies hold promise for significantly automating parts of the procedure human fact-checkers use today to determine if a story is real or a hoax.

# Dataset Description:
https://www.machinehack.com/hackathons/fake_news_content_detection_weekend_hackathon_20/overview
1. Train.csv - 10240 rows x 3 columns (Inlcudes Labels Columns as Target)
2. Test.csv - 1267 rows x 2 columns
 

# Attribute Description:

1. Text - Raw content from social media/ new platforms
2. Text_Tag - Different types of content tags
3. Labels - Represents various classes of Labels
4. Half-True - 2
5. False - 1
6. Mostly-True - 3
7. True - 5
8. Barely-True - 0
9. Not-Known - 4

# Skills:

1. NLP, Sentiment Analysis
2. Feature extraction from raw text using TF-IDF, CountVectorizer
3. Using Word Embedding to represent words as vectors
4. Using Pretrained models like Transformers, BERT
5. Optimizing multi-class log loss to generalize well on unseen data
