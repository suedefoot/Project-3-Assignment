# Advanced Dialogue Summarization Using Transformer Architectures

## Project Overview

This project explores abstractive dialogue summarization using transformer-based encoder-decoder architectures. The implementation uses a BERT encoder and GPT-2 decoder trained on the SAMSum dataset to generate concise summaries of multi-speaker conversations.

The project was developed as part of a graduate-level machine learning and NLP capstone assignment focused on applying modern transformer architectures to real-world conversational summarization tasks.

---

## Objectives

- Build an end-to-end dialogue summarization pipeline
- Explore transformer-based encoder-decoder architectures
- Perform exploratory data analysis on conversational datasets
- Train and evaluate summarization models using Hugging Face Transformers
- Analyze summarization quality using quantitative and qualitative metrics
- Demonstrate reproducible machine learning engineering workflows

---

## Dataset

### SAMSum Dataset
The project uses the SAMSum corpus, a dataset containing human-written summaries of messenger-style conversations.

Dataset features include:
- Multi-speaker dialogue structure
- Informal conversational language
- Human-generated abstractive summaries
- Realistic communication patterns

Source:
https://huggingface.co/datasets/samsum

---

## Model Architecture

The implementation uses:

- **Encoder:** BERT (`bert-base-uncased`)
- **Decoder:** GPT-2 (`gpt2`)
- **Framework:** Hugging Face Transformers
- **Training Strategy:** Encoder-decoder fine-tuning

Additional optimizations include:
- Gradient clipping
- Learning rate scheduling
- Validation checkpointing
- Early stopping
- Representative stratified sampling

---

## Project Structure

```text
Project 3/
│
├── README.md
├── .gitignore
│
└── assignments/
    ├── Advanced_Dialogue_Summarization.ipynb
    ├── requirements.txt
    ├── project_pitch.pdf
    ├── slide_deck.pdf
    └── generated_artifacts/
