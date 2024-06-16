# Natural Language Processing

Emotion classification tasks: 
- investigate the core principles of the Naïve Bayes algorithm, utilize it for an emotion detection task, and assess its effectiveness in identifying six emotion categories based on the dataset you and your peers created last week.
- investigate the core principles of the binary logistic regression algorithm. Filter your data to contain only information from the 2 categories {Joy,Sadness}.Treat Joy as your positive class, and Sadness as your negative class for coding and computation. Again, double count sentences that are in both categories.
- investigate the core principles of the Word2Vec skip-gram algorithm. Use the same data in the last homework with data of the 2 categories {Joy,Sadness}.Put all joy&sadness sentences into your corpus (there is no train/val/test split, use all rows as the training set). Remember the key of the implementation is that for each target word w, the neighboring words within the context window are positive words and we sample negative words. Use context words in the L= +-2.
- investigate the core principles of using RNN for machine translation with PyTorch.

