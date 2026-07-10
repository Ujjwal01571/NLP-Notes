# 🧠 Natural Language Processing (NLP) - Notes

## 📌 Definition
Natural Language Processing (NLP) is a branch of Artificial Intelligence (AI) that enables computers to understand, analyze, process, and generate human language.

---

# 🎯 Objectives of NLP
- Understand human language
- Process text and speech
- Translate languages
- Generate human-like text
- Analyze sentiment
- Answer questions
- Summarize documents

---

# 🏗️ NLP Pipeline

Raw Text
↓
Text Cleaning
↓
Tokenization
↓
Stopword Removal
↓
Stemming / Lemmatization
↓
Feature Extraction
↓
Model Training
↓
Prediction

---

# 📝 Text Preprocessing

## 1. Tokenization
Splits text into words or sentences.

**Example:**
```
"I love AI"
↓
["I", "love", "AI"]
```

---

## 2. Stopword Removal
Removes common words that do not add much meaning.

**Examples:**
- is
- the
- a
- an
- of
- in
- to

---

## 3. Stemming
Reduces words to their root form.

**Example:**
```
Playing → Play
Running → Run
```

---

## 4. Lemmatization
Converts words into meaningful dictionary forms.

**Example:**
```
Better → Good
Running → Run
```

---

# 📊 Feature Extraction

Converts text into numerical vectors.

Methods:
- Bag of Words (BoW)
- TF-IDF
- Word2Vec
- GloVe
- FastText
- BERT Embeddings

---

# 📚 Bag of Words (BoW)

Counts the frequency of words in a document.

### Advantages
- Simple
- Fast
- Easy to implement

### Disadvantages
- Ignores word order
- Produces sparse vectors

---

# 📚 TF-IDF

**TF (Term Frequency):** Number of times a word appears in a document.

**IDF (Inverse Document Frequency):** Measures the importance of a word across multiple documents.

---

# 🤖 Word Embeddings

Represents words as dense numerical vectors.

Popular Techniques:
- Word2Vec
- GloVe
- FastText
- BERT Embeddings

---

# 🧠 Deep Learning Models in NLP

- RNN
- LSTM
- GRU
- Transformer

---

# 🚀 Transformer

Introduced in the paper:
**"Attention Is All You Need" (2017)**

### Advantages
- Faster training
- Parallel processing
- Better context understanding

---

# 🤖 Popular NLP Models

| Model | Developed By |
|--------|--------------|
| BERT | Google |
| GPT | OpenAI |
| RoBERTa | Meta |
| T5 | Google |
| LLaMA | Meta |
| Gemini | Google |

---

# 💼 Applications of NLP

- Chatbots
- Machine Translation
- Sentiment Analysis
- Spam Detection
- Search Engines
- Grammar Checking
- Voice Assistants
- Text Summarization
- Question Answering

---

# 📌 Common NLP Tasks

- Text Classification
- Named Entity Recognition (NER)
- Language Translation
- Text Generation
- Sentiment Analysis
- Speech Recognition
- Information Extraction

---

# 📈 Advantages

- Automates text processing
- Saves time
- Supports multiple languages
- Improves user experience
- Handles large text datasets

---

# ⚠️ Limitations

- Difficult to understand sarcasm
- Ambiguous language
- Requires large datasets
- High computational cost

---

# 📚 Popular Python Libraries

- NLTK
- spaCy
- Gensim
- Hugging Face Transformers
- TextBlob

---

# 📖 Real-Life Examples

| Application | NLP Task |
|-------------|----------|
| ChatGPT | Text Generation |
| Gmail | Spam Detection |
| Google Translate | Machine Translation |
| Grammarly | Grammar Correction |
| Alexa | Speech Recognition |

---

# 📝 Interview Questions

### What is NLP?
NLP is a branch of AI that enables computers to understand and process human language.

### Difference between Stemming and Lemmatization?

| Stemming | Lemmatization |
|-----------|---------------|
| Faster | More accurate |
| Rule-based | Dictionary-based |

### Difference between BoW and TF-IDF?

| Bag of Words | TF-IDF |
|--------------|--------|
| Counts words | Assigns importance to words |

---

# 📌 Summary

- NLP is a branch of AI.
- It enables machines to understand human language.
- Text preprocessing is the first step in NLP.
- Transformers are the foundation of modern NLP models.
- NLP powers ChatGPT, Google Translate, Grammarly, Alexa, and many other AI applications.