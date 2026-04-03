NLP_Techniques_on_Text_Data
AIM
To study, implement, and analyze fundamental text preprocessing and Natural Language Processing (NLP) techniques using Python’s NLTK library to transform raw, unstructured text into a format suitable for computational analysis.

OBJECTIVES
To perform Text Cleaning by removing noise such as punctuation and special characters.
To execute Tokenization and Stop Word Removal to isolate meaningful semantic units.
To contrast Stemming and Lemmatization for word normalization.
To apply Part-of-Speech (POS) Tagging and Frequency Distribution for structural and statistical analysis.
TOOLS & SOFTWARE
Programming Language: Python 3.x
Environment: Google Colab / Jupyter Notebook.
Libraries:
NLTK: For core NLP tasks (Tokenization, Stemming, Lemmatization, POS Tagging).
Pandas/NumPy: For data manipulation and array handling.
THEORY
1. Tokenization
Tokenization: the foundational step in NLP that involves breaking a raw string of text into smaller units called tokens.
Word Tokenization: Splitting a sentence into individual words (e.g., "Natural Language" becomes ['Natural', 'Language']).
Sentence Tokenization: Dividing a large paragraph into its constituent sentences based on punctuation cues.
2. Stop Word Removal
Stop words are common words (such as "is", "the", "and", "in") that appear frequently but carry minimal unique semantic information.
Removing these reduces the noise in the data, allowing the model to focus on the "content" words that define the meaning of the text.

3. Word Normalization:
Stemming vs. Lemmatization
Both techniques aim to reduce inflectional forms of a word to a common base, but they differ in their approach:

Stemming: A rule-based process that chops off the ends of words to find the "stem." It is fast but can result in non-dictionary words (e.g., "studies" becomes "studi").
Lemmatization: A more sophisticated process that uses a vocabulary and morphological analysis to return the lemma (dictionary form). It ensures the resulting word is linguistically valid (e.g., "studies" becomes "study").
4. Part-of-Speech (POS) Tagging
POS tagging is the process of marking up a word in a text as corresponding to a particular part of speech based on its definition and context. This helps the system understand the grammatical structure of a sentence. Common tags include:

NNP: Proper noun, singular.
VBZ: Verb, 3rd person singular present.
JJ: Adjective.
5. Word Frequency Distribution
This involves counting the occurrences of each token in a text corpus.
It is used to identify the most significant words or "keywords" in a document, which is essential for tasks like document summarization or sentiment analysis.


ALGORITHMS
A. Tokenization (Word & Sentence)
Start.
Input a raw string of text.
Load the punkt tokenizer from NLTK.
Apply sent_tokenize() to split the paragraph into a list of individual sentences.
Apply word_tokenize() to split sentences into a list of individual words/punctuation.
Stop.
B. Stop Word Removal
Start.
Define a set of English stop words using nltk.corpus.stopwords.words('english').
Tokenize the input text into a list of words.
Iterate through each word in the list.
Check if the word (in lowercase) exists in the stop words set.
If not in the set, append it to a new filtered_list.
Stop.
C. Stemming (Porter Stemmer)
Start.
Initialize the PorterStemmer() object.
Provide a list of words to be reduced.
For each word, apply the stemming rule (heuristic chopping of suffixes).
Return the resulting "stems" (e.g., "flying" , "fli").
Stop.
D. Lemmatization (WordNet)
Start.
Initialize the WordNetLemmatizer() object.
Ensure the wordnet corpus is downloaded.
For each word, look up its base form in the lexical database.
Return the valid dictionary "lemma" (e.g.: "was" , "be").
Stop.
E. Part-of-Speech (POS) Tagging
Start.
Tokenize the input text into words.
Apply the pos_tag() function to the word list.
Assign a tag (NN, VB, JJ, etc.) to each token based on context and grammar.
Output the word-tag pairs.
Stop.
F. Word Frequency Distribution
Start.
Tokenize the input text.
Create a FreqDist object from the list of tokens.
Count the occurrences of each unique word.
Identify and display the most common words.
Stop.

REAL-LIFE APPLICATIONS
Chatbots and Virtual Assistants: Applications like Siri, Alexa, and Google Assistant use Tokenization and POS Tagging to parse user commands and provide human-like responses.
Spam Email Detection: Email services use Stop Word Removal and Word Frequency (Bag of Words) to identify patterns common in spam messages and filter them out of your inbox.
Search Engines: Google and Bing use Stemming and Lemmatization so that if you search for "running shoes," you also get results for "run shoes" or "ran," improving search relevance.
Recommendation Systems: Streaming platforms like Netflix use Text Vectorization to analyze movie descriptions and recommend similar content based on text similarity.
CONCLUSION
The preprocessing techniques and NLP techniques used for analyzing text data were studied successfully.
