# Text-Classification
SVM and Naive Bayes for text classification project on kaggle Wikipedia Movie Plots Dataset.

Dataset url: https://www.kaggle.com/jrobischon/wikipedia-movie-plots

Project Description:

Task 1. Explore the dataset. Plot the distribution of the attributes if applicable.
Find most/least common words, average sentence length for textual attributes, the proportion of each class in the dataset, the trends found in the dataset.

Task 2. Select the following five movie genres: Drama, comedy, adventure, romance, western.

Task 3. Clean the text: Remove stop words.
                Remove numbers and other non-letter characters.
                Perform either lemmatization or stemming.

Task 4. Convert the corpus into a bag-of-words tf-idf weighted vector representation.

Task 5. Split the data randomly into training and testing sets (70-30 %).
Train SVM and report confusion matrix.
Train Multinomial NB and report confusion matrix.
Which algorithm has a higher weighted F1 measure and why?
Does changing the kernel of the SVM change the weighted F1 measure or decrease confusion between classes?

Task 6. Perform part-of-speech tagging on the raw data (i.e. prior to cleaning it), clean as in Task 3, and extract the nouns only to obtain a bag-of-words tf-idf weighted vector representation using only the nouns. Repeat question Task 5. How does this weighted F1 measure compare with that of Task 5? How does the size of the vocabulary compare with that of Task 5?

Task 7. Fix the class imbalance by the resampling strategy of your choice. Repeat Task 5 and compare the performance with what you received in Task 5. Discuss your findings.
