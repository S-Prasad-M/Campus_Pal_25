# Campus Pal - QA System for Amrita University

## Team Members
- **Shree Prasad M - CH.EN.U4AIE22050**
- **Tharun Kaarthik G K- CH.EN.U4AIE22062**

## Repository Structure
```
Campus-Pal/
│-- Solution/
│   │-- Level-1/
│   │   ├── (Photos of proof)
│   │-- Level-2/
│   │   ├── (Photos of proof)
│   │-- Level-3/
│   │   ├── (Photos of proof)
```

## Objective
Campus Pal is an AI-driven Question Answering (QA) system designed to provide quick and accurate responses to queries related to Amrita University.

## Model Used
We employ **T5ForConditionalGeneration**, a transformer-based sequence-to-sequence model, to generate accurate and contextually relevant answers from structured and unstructured university data.

Key features of T5ForConditionalGeneration:
- Pre-trained on large-scale datasets and fine-tuned for specific tasks
- Capable of understanding and generating human-like text
- Supports multiple NLP tasks like summarization, translation, and QA
- Uses an encoder-decoder architecture optimized for conditional text generation

## Implementation Overview
1. **Data Collection**: Using the given JSON file.
2. **Fine-tuning**: Training T5 on domain-specific data related to Amrita University.
3. **Testing**: Using the given sets of questions of different levels and getting appropriate answers


