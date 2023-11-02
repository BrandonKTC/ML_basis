# Naive Bayes and NLP

Naive Bayes is a set of algorithms that use Bayes' Theorem for supervised learning classification.
- Bayes' Theorem is a probability formula that leverages previously known probabilities to define probability of related events occuring.

## Bayes' Theorem:

- A and B are events
- P(A|B) is probability of event A given that B is True.
What's the probability of event A happening given that the second event is True/ or has already occur
- P(B|A) is probability of event B given that A is True.
- P(A) is probability of A occuring.
- P(B) is probability of B occuring.

Formula: P(A|B) = P(B|A) . P(A) / P(B)

## Count Vectorization

count vectorization treats every word as a feature, with the frequency counts acting as a "strength" of the feature/word. For larger documents, matrices are stored as a sparse matrix

- create a vocabulary dictionary (Document Term Matrix)  of all possible words

## Stop Words

stop words are words common enough throughout a language
it's usually safe to remove them and not consider them as important. Most NLP librairies have a built-in list of common stop words.

- Term frequency tf(t,d): is the raw count of a term in a document:
the number of times that term t occurs in document d.

An Inversed Document Frequency factor is incorporated chich diminishes the weight of terms that occur very frequently in the document set and increases the weight of terms that occur rarely.

- The IDF is how common or rare a word is in the entire document set
the closer it is to 0 the more common a word is.

