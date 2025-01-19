# Multimodal Emotion Analysis
Course Project | [Sep’24 - Nov’24]
Guide: Prof. Pushpak P. Bhattacharya
Department of Computer Science & Engineering | IIT Bombay


# Project Overview
This project focuses on analyzing the interplay of emotions, text, and images in social media communication. Using a multi-modal dataset of annotated Reddit posts, the goal was to understand user behavior through the integration of textual and visual modalities.

Key objectives include:

- Predicting emotions and image-text relationships in social media posts.
- Analyzing stimuli behind specific emotional responses.
- Exploring the effectiveness of multimodal fusion for improved classification.

# Dataset
The project utilizes a multi-modal dataset derived from Reddit posts, annotated for:

- Emotions (e.g., happiness, anger, sadness, etc.).
- Image-Text Links (to capture the relationship between text and visuals).
- Stimuli (the triggering aspect leading to emotional responses).


# Methodology
# Models Used
- RoBERTa: A pre-trained transformer-based model for text classification.
- ResNet-50: A deep learning model for image feature extraction.

# Process Flow
- Text Analysis: Extracted and processed textual features using RoBERTa.
- Image Analysis: Processed visual features using ResNet-50.
- Multimodal Fusion: Combined textual and visual embeddings to evaluate the interplay of text and images.
- Classification Tasks: Built models for:
 -  Emotion classification.
 -  Image-text link classification.
 -  Stimulus identification.

# Evaluation
Assessed the effectiveness of the multimodal approach using standard classification metrics (e.g., accuracy, F1-score, precision, recall).
Compared performance with unimodal approaches to highlight the benefit of fusion

# Results
The multimodal fusion approach improved classification performance in:

- Emotion prediction.
- Stimulus classification.
- Image-text relationship identification.
