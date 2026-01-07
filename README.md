# ZakeyTeam-arabic-qa-system-arabert
 an AI powered Arabic Question Answering system built by fine tuning the AraBERT model on the Arabic SQuAD dataset. , Developed as part of the ZakyBootcamp AI track
---
# Arabic Question Answering System with AraBERT
**Fine-Tuning Transformer Models for Arabic NLP**

## Overview
This project focuses on building a sophisticated Question Answering (QA) system specifically for the Arabic language. By fine-tuning the **AraBERT** model on the **Arabic SQuAD** dataset, the system can extract precise answers from a given context. This project demonstrates advanced skills in Deep Learning, Transformer architectures, and Natural Language Processing (NLP).

![Project Demo](PASTE_YOUR_GIF_HERE)

## Technical Stack
*   **Model Architecture:** AraBERT (State-of-the-art Arabic Language Model).
*   **Frameworks:** PyTorch & Hugging Face Transformers.
*   **Dataset:** Arabic SQuAD (Stanford Question Answering Dataset translated/adapted for Arabic).
*   **Development Environment:** Google Colab with GPU acceleration.
*   **Tools:** Python, Datasets Library, Accelerate.

## Project Pipeline
1.  **Data Preprocessing:** Tokenizing Arabic text and aligning answer spans (start/end positions) with BERT tokens.
2.  **Model Fine-Tuning:** Training AraBERT for "Span Extraction" tasks to identify answer locations within a context.
3.  **Evaluation Metrics:** Measuring performance using Exact Match (EM) and F1-Score.
4.  **Inference Interface:** A web interface/script where users provide a context and a question to receive an instantaneous answer.

## Key Features
*   **Context-Aware Processing:** Capable of understanding complex Arabic grammatical structures.
*   **High Precision:** Optimized via fine-tuning to handle the nuances of the Arabic language.
*   **Interactive Demo:** A ready-to-use interface for testing various context-question pairs.

## Installation and Execution
1.  Open the `AraBERT_QA.ipynb` file in Google Colab.
2.  Install the necessary AI libraries:
    ```bash
    pip install transformers datasets accelerate
    ```
3.  Run the notebook cells to load the pre-trained weights and start the inference engine.

## Developer
**Mahmoud Sammour**  
*October 2025 - January 2026*  
*ZakyBootcamp AI Track*

---
*This project was completed with a score of 22/20, recognized for exceptional model accuracy and comprehensive technical reporting.*
