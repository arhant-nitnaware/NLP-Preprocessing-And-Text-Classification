# NLP-Preprocessing-And-Text-Classification
NLP Preprocessing and Text Classification
What is Natural Language Processing (NLP)?
Natural Language Processing (NLP) is a field of Artificial Intelligence that focuses on enabling machines to understand, interpret, and generate human language. In this assignment, we focus on text classification, where the goal is to assign predefined labels (e.g., spam/ham, positive/negative) to text data.

NLP Preprocessing Techniques
Before feeding text data into a machine learning model, it must be preprocessed and converted into a numerical format. Common preprocessing steps include:

1. Tokenization
Splitting a sentence or paragraph into individual units (tokens), usually words.

Example: "This is a sentence." → ["This", "is", "a", "sentence"]

2. Stopword Removal
Stopwords are commonly used words (e.g., “and”, “is”, “the”) that add little value to text analysis.

Removing them reduces noise and model complexity.

3. Stemming
Reduces words to their root form by chopping off suffixes.

Example: "playing" → "play" using a rule-based algorithm like Porter Stemmer.

4. Lemmatization
Similar to stemming but more sophisticated; it reduces words to their dictionary base form using context.

Example: "better" → "good"

Text Vectorization
Text data must be converted into numerical format for ML models to process. Two common vectorization techniques are:

1. CountVectorizer
Converts a corpus into a bag-of-words model.

Creates a vocabulary and returns a document-term matrix with token counts.

2. TF-IDF (Term Frequency-Inverse Document Frequency)
Measures how important a word is to a document in a collection.

Reduces the weight of common words that appear in many documents.

Text Classification with Machine Learning
Once text is preprocessed and vectorized, it can be passed into a machine learning classifier.

Common Algorithms Used:
Naive Bayes: Popular for text due to its efficiency and good performance on sparse data.

Logistic Regression: Suitable for binary or multi-class text classification.

Support Vector Machines (SVM): Effective for high-dimensional data like text.

Evaluation Metrics
To evaluate the performance of a text classification model, the following metrics are commonly used:

Accuracy: Overall correctness of the model.

Precision: Correct positive predictions / All positive predictions.

Recall: Correct positive predictions / All actual positives.

F1-Score: Harmonic mean of precision and recall.

Applications
Spam detection

Sentiment analysis

News categorization

Customer feedback classification

Toxic comment detection
