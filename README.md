AI-Powered Code Understanding and Contextual Aware Suggestions
Project Overview

This project implements an AI-powered code intelligence system that integrates code documentation generation, contextual code suggestions, and automated bug detection into a single interface. The project investigates the gap between traditional evaluation metrics and real-world semantic usefulness of code language models.

Problem Statement

Many state-of-the-art code language models achieve high BLEU and ROUGE scores but often fail to produce semantically correct or practically useful outputs in real software development scenarios. This limits their reliability for real-world use.

Objectives
Evaluate the effectiveness of popular code language models in real-world scenarios
Analyze limitations of BLEU and ROUGE for code intelligence tasks
Build a unified system combining documentation, suggestions, and bug detection
Compare metric-based evaluation with human semantic evaluation
Features
Automated code documentation generation
Context-aware code suggestions
Deep learning–based bug detection (CNN + LSTM)
Unified interactive interface using Gradio
System Architecture
Transformer-based models for documentation generation and contextual suggestions
CNN + LSTM hybrid architecture for bug detection
Gradio-based UI integrating all components
Models Used
StarCoder2-7B (inference-only)
CodeT5-small, CodeT5-base
CodeT5p-220M, CodeT5p-770M
CodeGPT-small
Datasets
CodeSearchNet – Used for documentation generation and contextual suggestions
PyTraceBugs – Used for bug detection and classification
Evaluation Methodology
BLEU and ROUGE for documentation and suggestion tasks
Accuracy, Precision, Recall, and F1-score for bug detection
Human evaluation to assess semantic correctness and practical usefulness
Results Summary
Fine-tuned CodeT5 models achieved high BLEU/ROUGE but poor real-world performance
StarCoder2-7B demonstrated stronger semantic understanding despite lower metric scores
CNN + LSTM bug detection model achieved high accuracy and reliability
Tech Stack
Python
PyTorch
Keras
Hugging Face Transformers
Gradio

Limitations
Fine-tuning performed on limited datasets due to computational constraints
BLEU and ROUGE do not capture semantic or functional correctness
Future Work
Lightweight fine-tuning of larger models using LoRA / QLoRA
Use of semantic and execution-based evaluation metrics
Retrieval-Augmented Generation (RAG) for improved contextual suggestions
Author

Venkata Hanish Talluri

License

This project is intended for academic and research purposes.
