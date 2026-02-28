# 📊 CSL7110 – MinHash and Locality Sensitive Hashing (LSH)

## 🔎 Overview
This project implements scalable similarity detection techniques including:

- Shingling (k-grams)
- Exact Jaccard Similarity
- MinHashing
- Locality Sensitive Hashing (LSH)

The methods are applied to:
1. Small text documents (D1–D4)
2. MovieLens 100k dataset (943 users, 1682 movies)

The objective is to compare exact similarity computation with approximate methods and analyze their performance trade-offs.

---

## 🧠 Concepts Implemented

### 1️⃣ K-Grams & Jaccard Similarity
- Character 2-grams
- Character 3-grams
- Word 2-grams
- Exact similarity computation

### 2️⃣ MinHash
- Signature generation using multiple hash functions
- Similarity estimation
- Accuracy analysis for different signature sizes

### 3️⃣ Locality Sensitive Hashing (LSH)
- Banding technique
- S-curve analysis
- Parameter tuning (r, b)
- False Positive / False Negative evaluation

---

## 🎬 MovieLens 100k Dataset
- 943 users
- 1682 movies
- Ratings ignored
- Similarity computed based on user-movie interactions

Experiments performed for:
- 50 hash functions
- 100 hash functions
- 200 hash functions
- Multiple LSH configurations

---

## 📈 Key Observations

- Increasing number of hash functions improves MinHash accuracy.
- Proper selection of (r, b) values in LSH creates sharp S-curve separation.
- Higher similarity thresholds increase false negatives.
- LSH significantly reduces pairwise comparisons compared to brute-force computation.

---

## 📁 Repository Structure
CSL7110_Minhash_LSH_Assignment.ipynb
README.md
Report.pdf
---

## 👨‍🎓 Author

**Shasank Dixit**  
CSL7110 Assignment – MinHash & LSH  
