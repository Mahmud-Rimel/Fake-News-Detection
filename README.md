# Fake News Detection

The motivation of this project is to differentiate between Fake news and Real news by applying Natural Language processing techniques and machine learning algorithms.

## Workflow of the study
- **Removing Punctuation** 
- **Tokenization**
- **Stopwords**
- **Stemming**
- **Feature Extraction**
- **Building machine learning classifiers**
- **Evaluation of the results**


### **Data Source:** [Data](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)

### **Tokenization**

Tokenization is a technique to separating a piece of text into small units. A text may contain a huge number of words, sentences. Tokenization creates a list of words in the text. For example:  ' I am writing a markdown file.' --> ['I', 'am', 'writing','a', 'markdown','file.']

### **Stopwords**

Stopwords are words that have little value in a text/are very common in a text. For example, in the English language stopwords are 'I, am, is, are, he, she, my, to, for, was' etc.

### **Stemming**
Stemming is a technique to reduce the abundance of words from the text. Stemming removes the suffixes of words and returns a base form of the word. 
For example, plays, playing, played -- > play

### **TF-IDF (Term Frequency - Inverse Document Frequency)**

Term frequency and inverse document frequency is a vectorization technique to show the importance of a word in a text, based on its frequency and weight of the word.

### Evaluation Metrics

- **Precision:** (News predicted as fake that are actually fake)/Total predicted fake news

- **Recall:** News predicted as fake that are actually fake/Total number of fake news that are actually fake

- **Accuracy:** Predicted correctly/Total number of news

