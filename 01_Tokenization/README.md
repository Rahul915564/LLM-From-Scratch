# 🔤 Tokenization – LLM From Scratch

## 📌 Overview

Tokenization is one of the fundamental steps in building Large Language Models (LLMs). It converts raw text into smaller units called tokens, which can be processed by neural networks.

This module explores different tokenization techniques and implements them using Python from scratch.

## 🎯 Learning Objectives

- Understand the fundamentals of tokenization.
- Implement character-level tokenization.
- Implement word-level tokenization.
- Build vocabulary and token-to-ID mappings.
- Understand encoding and decoding.
- Learn Byte Pair Encoding (BPE).
- Understand how modern LLMs process text.

## 📚 Topics Covered

### 1. Character-Level Tokenization
- Splitting text into individual characters.
- Creating character vocabulary.
- Converting characters into numerical IDs.

### 2. Word-Level Tokenization
- Splitting sentences into words.
- Identifying unique words.
- Building word-level vocabulary.

### 3. Token-to-ID Mapping
- Creating vocabulary dictionaries.
- Mapping tokens to numerical IDs.
- Converting text into numerical sequences.

### 4. Encoding and Decoding
- Text-to-token conversion.
- Token-to-ID encoding.
- ID-to-token decoding.
- Reconstructing original text.

### 5. Byte Pair Encoding (BPE)
- Understanding subword tokenization.
- Calculating pair frequencies.
- Merging frequent character pairs.
- Building a subword vocabulary.
- Training and testing a basic BPE tokenizer.

## 🛠️ Technologies Used

- Python 3
- Google Colab
- Jupyter Notebook
- Basic Python Data Structures

## 📂 Project Structure

```text
01_Tokenization/
│
├── README.md
└── LLM_Phase1_.ipynb
```

## 🚀 How to Run

1. Open the notebook.
2. Click **Open in Colab** or download it.
3. Run the cells sequentially.
4. Experiment with different input sentences.
5. Observe tokenization, encoding and decoding outputs.

## 💡 Key Learning Outcomes

After completing this module, you will understand:

- How raw text is converted into tokens.
- Why token IDs are required for neural networks.
- How vocabulary construction works.
- How subword tokenization reduces vocabulary limitations.
- How BPE learns frequent token combinations.

## 🔬 Practical Implementation

All implementations are developed from scratch using Python to understand the internal working of tokenizers rather than relying entirely on pre-built libraries.

## 📈 Next Module

**02 – Embeddings**

Understanding how token IDs are transformed into dense vector representations that neural networks can learn from.

---

Part of my learning journey: **Building Large Language Models from Scratch.**
