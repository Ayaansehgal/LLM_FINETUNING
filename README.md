# LLM_FINETUNING
im trying to learn new concepts related to AIML and i stumbled upon Fine Tunning a LLM so these are the projects i worked on this topics
#  LLM Fine-Tuning Projects
This repository is a collection of my fine-tuning experiments with language models (LLMs) for domain-specific tasks using the Hugging Face `transformers` and `trl` libraries.
Each project focuses on a different dataset and use-case, with an emphasis on making LLMs more accessible, lightweight, and purposeful for real-world applications.

---

## 📌 Current Projects
### 1. Indian Legal Q&A Chatbot (DistilGPT2 Fine-Tuning)
#### Overview
This project fine-tunes the lightweight `distilgpt2` model on a dataset of 500 Indian legal questions and answers. The model is trained to generate contextual, chat-style responses to queries related to Indian law, such as:
- Filing an FIR
- Applying for bail
- Marriage laws
- Property rights, etc.
#### Why DistilGPT2?
I originally intended to fine-tune LLaMA 2, but due to hardware and Colab constraints, I pivoted to `distilgpt2` — a smaller, faster model that can be trained on CPU with limited resources.
#### Dataset
The dataset consists of ~500 legal QA pairs, manually curated and formatted into a chat-style prompt like:

