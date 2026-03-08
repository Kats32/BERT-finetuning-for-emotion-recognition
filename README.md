# BERT-finetuning-for-emotion-recognition
Emotion classification using BERT-goemotion transformer model built with Hugging Face Transformers and dataset, PyTorch and Scikit-learn for evaluation.

## Project Overview
This project utilizes transformer model to recognize human emotions in texts.
The model is finetuned on labeled emotion dataset to classify text into multiple emotional categories.

The goal of this project is to explore working mechanism of a transformer along with it's capability in capturing contextual emotional signals in natural language.

## Model

This project uses a finetuned version of BERT specifically to detect emotions in text - GoEmotions BERT model.

Architecture:
Input text → Tokenizer → BERT encoder → Classification head → Emotion recognition
