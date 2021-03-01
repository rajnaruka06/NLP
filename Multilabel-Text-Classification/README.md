#### Problem Statement:
- The challenge is to develop a machine learning model(s) to classify given text data into multiple classes. The text can belong to multiple classes simultaneously.

#### Preprocessing Findings: 
- Convert all text to lower english alphabets. (Could do upper as well. Consistancy is important.)
- Word tokenization.
- Removing stopwords. (Words that occur a lot in the corpus but add no special sense to data.)
- Filtering only alphabet-words. (No special characters or numerical values.)
- Using work lemmatization. (work, worked, works -> work)
- Dataset has a huge class imbalance problem.
- Oversampling technique can be used to conquer this.

#### Approach:
- Random Oversampling to conquer class imbalance problem.
- Manually oversampling the classes which had most entries before oversampling.
- Tf-Idf vector represention.
- Can build 6 different classifiers and then use them or treat the problem as a multi-class-classification problem.
- Will build one model for multi-class classification problem.
