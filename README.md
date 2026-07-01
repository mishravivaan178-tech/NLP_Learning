# NLP_Learning
# 📄 Text Summarizer using TF-IDF

## 📌 Overview

This project is an **Extractive Text Summarizer** built using **Python**, **NLTK**, and **Scikit-learn**. It summarizes long pieces of text by identifying the most important sentences using the **TF-IDF (Term Frequency–Inverse Document Frequency)** algorithm.

Unlike modern Large Language Models (LLMs), this project does **not generate new sentences**. Instead, it selects the most relevant sentences from the original text based on their importance.

This project was built to strengthen my understanding of **Classical Natural Language Processing (NLP)** before moving on to **Word Embeddings, Transformers, Large Language Models (LLMs), and Agentic AI**.

---

## 🚀 Features

* Convert text to lowercase
* Remove punctuation
* Tokenize text into words
* Remove stopwords
* Lemmatize words
* Split article into sentences
* Generate TF-IDF vectors
* Calculate sentence importance scores
* Rank sentences
* Generate an extractive summary

---

## 🛠️ Technologies Used

* Python 3
* NLTK
* NumPy
* Scikit-learn (TF-IDF Vectorizer)

---

## 📂 Project Structure

```text
Text-Summarizer-TFIDF/
│
├── text_summarizer.ipynb
├── requirements.txt
├── sample_article.txt
└── README.md
```

---

## ⚙️ How It Works

```text
Input Article
      │
      ▼
Sentence Tokenization
      │
      ▼
Text Preprocessing
      │
      ├── Lowercasing
      ├── Remove Punctuation
      ├── Tokenization
      ├── Stopword Removal
      └── Lemmatization
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Sentence Scoring
      │
      ▼
Sentence Ranking
      │
      ▼
Top N Sentence Selection
      │
      ▼
Final Summary
```

---

## 📖 Example

### Input

```text
Artificial Intelligence is transforming healthcare.
Doctors use AI to detect diseases early.
Patients receive faster treatment because of AI.
Machine learning helps researchers discover new medicines.
The future of healthcare looks very promising.
```

### Output (Top 2 Sentences)

```text
Doctors use AI to detect diseases early.
Machine learning helps researchers discover new medicines.
```

> The selected sentences may vary depending on their TF-IDF scores.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/Text-Summarizer-TFIDF.git
```

Move into the project directory:

```bash
cd Text-Summarizer-TFIDF
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook text_summarizer.ipynb
```

Or open the notebook in **Google Colab**.

---

## 📚 NLP Concepts Used

* Text Preprocessing
* Sentence Tokenization
* Word Tokenization
* Stopword Removal
* Lemmatization
* Feature Extraction
* TF-IDF
* Sentence Ranking
* Extractive Text Summarization

---

## 🔮 Future Improvements

* Read articles from PDF files
* Read articles from Word documents
* User-defined summary length
* Web application using Streamlit or Flask
* TextRank-based summarization
* Transformer-based summarization (BART, T5, PEGASUS)
* LLM-powered abstractive summarization

---

## 🎯 Learning Outcome

This project helped me understand:

* Classical NLP pipelines
* Feature engineering using TF-IDF
* Extractive text summarization
* Sentence ranking algorithms
* Building an end-to-end NLP application

This project serves as the foundation for my journey toward **Large Language Models (LLMs)** and **Agentic AI**.

---

## 👨‍💻 Author

**Vivaan Mishra**

If you found this project helpful, feel free to ⭐ the repository and share your feedback!
