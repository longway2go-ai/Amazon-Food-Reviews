# 🍴 Amazon Food Reviews – Text Preprocessing & Feature Engineering

This repository focuses on preparing the **Amazon Fine Food Reviews** dataset for downstream machine learning tasks through **text preprocessing** and **feature engineering** techniques.

---

## 📊 Dataset

- **Description**: 
  - Contains 568,454 food-related reviews from Amazon users.
  - Includes fields like `Text`, `Summary`, `Score`, `Time`, `UserId`, and `ProductId`.

---

## 🧹 Text Preprocessing

The following preprocessing steps were applied to the review text:

- Lowercasing all text
- Removing:
  - HTML tags
  - Punctuation
  - Numbers and special characters
  - Stopwords
- Tokenization
- Lemmatization or stemming

---

## ⚙️ Feature Engineering

We transformed the preprocessed text into numerical formats using the following techniques:

- **Bag of Words (BoW)**  
  Count-based word representation capturing word frequency.

- **TF-IDF (Term Frequency-Inverse Document Frequency)**  
  Highlights important words by down-weighting common terms.

- **Word2Vec**  
  Word embeddings that capture semantic meaning (using pretrained or trained vectors).

- **Average Word2Vec**  
  Averaged word embeddings to create a single vector per review.

