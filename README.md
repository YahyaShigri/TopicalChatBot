# Design and Development of Topical Chatbot

## Learning Objectives

- Understand the fundamentals of Transformer-based encoder-decoder architecture for conversational chatbots.
- Learn how to use TensorFlow/PyTorch/Huggingface.
- Learn how to use Google Colab.
- Learn how to train and fine-tune a Transformer.

## Overview

A topical chatbot is a specialized AI designed for conversations about a specific subject, unlike general chatbots. These chatbots focus on a single topic, such as medicine or finance, and are trained to understand and discuss that area using relevant conversation datasets. They provide accurate and helpful information within their domain, enhancing user engagement and knowledge in that subject. However, they may struggle with topics beyond their training and lack broader conversational abilities.

## Dataset

The dataset used for this project is the Topical Chat dataset from Amazon, which contains over 8,000 conversations and over 184,000 messages. Each message has a conversation ID, indicating which conversation it belongs to, and a sentiment label representing the sender's emotion. The dataset includes 8 sentiments: Angry, Curious to Dive Deeper, Disguised, Fearful, Happy, Sad, and Surprised.

The dataset can be used for machine learning to simulate conversations, create chatbots, or for data visualization, such as analyzing word usage for different emotions. You can download the dataset from the following link:
[Topical Chat Dataset](https://github.com/alexa/Topical-Chat)

Further details about the dataset can also be found on the provided link.

## Project Stages

### Preprocessing

Apply necessary text processing techniques suitable for this task on the dataset.

### Training

The dataset is already split into various sets. Use deep learning frameworks such as TensorFlow, PyTorch, or Huggingface to train a Transformer model on the annotated dataset. You can create a custom model or use a pre-trained network, either fine-tuned or as a feature extractor.

### Evaluation

Evaluate the model's performance on the evaluation set using objective and subjective metrics:

1. Response Accuracy
2. Precision and Recall
3. F1 Score
4. User Satisfaction (e.g., Net Promoter Score)
5. Engagement (e.g., session duration, turn length)
6. Completion Rate
7. Fallback Rate
8. Churn Rate
9. Human Handoff Rate
10. Sentiment Analysis
11. Task Completion Rate

### Testing

Test the model on a separate test set of conversations not used during training to assess its generalization capability.

