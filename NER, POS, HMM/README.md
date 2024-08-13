Code 1: In this question we want to use POS-tagged training set to compute for each word the tag that maximizes $p(t|w)$.
We will implement a simple tokenizer to deal with sentence boundaries.

Code 2: In this question we will Build a bigram HMM tagger.
First we split the part-of-speech-tagged corpus into a training set and test set.
From the labeled training set, we train the transition and observation probabilities of the HMM tagger directly on the hand-tagged data.
Then implement the Viterbi algorithm so we can decode a test sentence.

Code 3:  We will develop a NER system specific to the category of names of the top 1000 movie titles from IMDB.
We will evaluate the system on a collection of text likely to contain instances of these named entities.