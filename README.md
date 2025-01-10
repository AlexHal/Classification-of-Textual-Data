# Classification of Textual Data

## Project Overview
This project implements **Naive Bayes** and **BERT** models for emotion classification on text data. It compares traditional and modern NLP techniques for detecting emotions such as anger, joy, and sadness.

Additionally, we used **BertViz** to visualize attention mechanisms in BERT, providing insights into how the model processes text for emotion detection.

## Key Highlights
- Built a Naive Bayes model from scratch using the bag-of-words approach.
- Fine-tuned a pre-trained BERT model for emotion classification.
- Visualized attention layers in BERT using BertViz.
- Compared performance in terms of accuracy and F1 score.

## Technologies Used
- **Hugging Face Transformers**: Pre-trained BERT model.
- **BertViz**: Visualized BERT's attention layers.
- **PyTorch**: Fine-tuning and evaluation.
- **Python**: Implemented Naive Bayes model and preprocessing.

## Dataset
- **Emotion Dataset**: English Twitter messages with six basic emotions (anger, fear, joy, love, sadness, and surprise).

## Results
- **Naive Bayes**:
  - Achieved moderate accuracy but struggled with linguistic context.
- **BERT**:
  - Demonstrated superior performance due to contextual understanding.
  - Pretraining significantly improved accuracy and F1 scores.
- **BertViz**:
  - Revealed how BERT attends to specific words, showcasing its contextual understanding.

## Visualizations
- **Attention Layers**: BertViz visualizations highlight how BERT processes and attends to key parts of input text during classification.

