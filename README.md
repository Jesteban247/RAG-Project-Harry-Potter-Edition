# 🧙‍♂️ **RAG Project: Harry Potter Edition**

Welcome to the **RAG Project**! In this project, we're building a **Retrieval-Augmented Generation (RAG) pipeline** using **Harry Potter: The Complete Collection** 🧹📜. The goal is to allow users to ask questions about the book, and the pipeline retrieves relevant information from the text and generates responses using state-of-the-art machine learning models. ⚡

## 🧠 **Overview**

This project implements a RAG pipeline from scratch, with some help from powerful libraries and models. Here's what it does:
1. **Retrieve Information**: It uses an **embedding model** to search and retrieve relevant chunks of text from the Harry Potter book.
2. **Generate Responses**: It leverages a **Large Language Model (LLM)** to answer user queries based on the retrieved text.

### ⚙️ **Pipeline Components**
- **Embeddings Model**: [**sentence-transformers/all-mpnet-base-v2**](https://huggingface.co/sentence-transformers/all-mpnet-base-v2) – This model transforms the text into dense vectors that capture the semantic meaning of the content, enabling fast and efficient retrieval of relevant sections.
- **LLM**: [**google/gemma-2-2b-it**](https://huggingface.co/google/gemma-2-2b-it) – This large language model generates natural language responses by combining the retrieved information with its own language understanding abilities.

Together, these components form a robust **RAG pipeline** that mimics human-like comprehension and response generation. The pipeline is designed to answer any question based on the **Harry Potter** books in an interactive way!

## 🛠️ **How to Use**
Run the notebook (Remeber use GPU) to start querying the book and watch the magic unfold! ✨

## 🎥 **Video Walkthrough**

Check out this video for a complete walkthrough of the project:  


https://github.com/user-attachments/assets/af0a7264-9d9d-47e7-a4d1-fd55ab3c0c68


## 🎥 **Acknowledgments**

This project is inspired by [Daniel Bourke](https://www.youtube.com/watch?v=qN_2fnOPY-M&t=513s)'s excellent video tutorial on RAG pipelines. Huge thanks to Daniel for providing valuable insights and inspiration! 🙌

---

This version includes the specific models you're using for embeddings and the LLM. Feel free to adjust the video link when it's ready!
