# CS6910-Course-work
This repository contains a comprehensive collection of deep learning assignments completed as part of the "CS6910: Fundamentals of Deep Learning" course at IIT Madras. The assignments cover a broad spectrum of neural network architectures and tasks, ranging from foundational feedforward networks to advanced models like Transformers and BERT. Projects are organized by dataset and task type for clarity and ease of navigation.

1. Image Classification Tasks
Dataset 1 & 2: Image Classification

Optimization Methods Comparison (Dataset 1):

Multi-layer Feedforward Neural Network (MLFFNN) with two hidden layers (20 and 10 nodes, tanh activation).

Comparison of optimization algorithms: Delta rule, Generalized delta rule, AdaGrad, RMSProp, and Adam.

Evaluation includes training error plots, confusion matrices, and convergence analysis.

Normalization Methods Comparison (Dataset 2):

MLFFNN with two hidden layers (20 and 10 nodes, tanh activation).

Comparison of normalization techniques: None, Layer Normalization, Batch Normalization.

Evaluation includes training error plots, confusion matrices, and convergence analysis.

Autoencoder Pre-training (Dataset 3):

Stacked autoencoder-based pre-training for a deep feedforward neural network (DFNN).

Performance comparison between standard DFNN and autoencoder-pretrained DFNN using confusion matrices.

Feature-based Classification:

MLFFNN using deep CNN features as input.

(a) Features from VGGNet

(b) Features from GoogLeNet

Custom CNN Architectures:

CNN with two convolutional (CL1, CL2) and two pooling layers (PL1, PL2).

Uses 3x3 kernels, mean pooling, and increasing feature maps.

2. Natural Language Processing (NLP) Tasks
Dataset: Sentiment Analysis

RNN for Sentiment Analysis:

Single hidden layer RNN with 25 nodes and 200-dimensional GloVe embeddings.

Fine-tuning BERT:

Fine-tuning the BERT model for sentiment classification.

Evaluation on test dataset.

Dataset: Machine Translation (English to Indian Language)

Sequence-to-Sequence Models:

RNN/LSTM-based translation with GloVe for English and IndicBERT for Indian languages.

Transformer-based translation with the same embeddings.

Performance reported using BLEU@k scores (k = 1, 2, 3, 4).

3. Sequence Modeling and Generation Tasks
Parts-of-Speech Tagging:

Single hidden layer RNN (25 nodes) for POS tagging.

Image Captioning:

VGGNet encoder + RNN decoder (50 nodes, single hidden layer).

VGGNet encoder + LSTM decoder (50 nodes, single hidden layer).

Uses 200-dimensional GloVe embeddings.

Performance evaluated with BLEU@k scores.

Organization
Assignments are grouped by dataset and task type, with each directory containing:

Source code and scripts

README files with instructions and results

Plots and confusion matrices

Evaluation metrics (accuracy, BLEU scores, etc.)

Summary
This repository demonstrates the implementation and analysis of a wide range of deep learning models, optimization strategies, and evaluation techniques across image and language tasks. It serves as a portfolio of practical skills in modern deep learning, showcasing both foundational understanding and hands-on proficiency with state-of-the-art architectures.
