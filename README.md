# Transformer-Based Text-Only and Multimodal Sentiment Analysis

This repository contains the implementation code for my dissertation project:

**A Comparative Evaluation of Transformer-Based Text-Only and Multimodal Approaches for Sentiment Analysis**

The project compares text-only and multimodal transformer-based approaches for sentiment analysis using the CMU-MOSEI dataset. The experiments evaluate model performance under 2-class, 3-class, and 7-class sentiment classification settings.

## Project Overview

Sentiment analysis is an important natural language processing task that aims to identify opinions, emotions, and attitudes expressed in human communication. While many sentiment analysis systems rely mainly on textual information, real-world communication often includes additional emotional cues from audio and visual signals.

This project investigates whether multimodal models can improve sentiment classification performance compared with text-only models. It also compares different multimodal fusion strategies and examines the trade-off between model performance and computational complexity.

## Models Included

The notebook includes the following models:

1. Text-only LSTM
2. Text-only Transformer
3. Early Fusion Transformer
4. Late Fusion Transformer
5. Hybrid Fusion Transformer

## Research Focus

The main research focus of this project is to compare:

- Text-only baseline models
- Multimodal fusion strategies
- Text-only Transformer and multimodal Transformer models
- Modality contribution using ablation experiments
- Model complexity and performance trade-offs

## Dataset

This project uses the **CMU-MOSEI** dataset for multimodal sentiment analysis.

The dataset file is not included in this repository because it is large. The dataset can be downloaded from the MultiBench GitHub repository:

https://github.com/pliang279/MultiBench

MultiBench supports several multimodal datasets, including CMU-MOSEI for affective computing tasks. It also provides processed datasets and data-loading examples for multimodal learning experiments.

After downloading the dataset, place the required CMU-MOSEI sentiment data file in your Google Drive or local working directory.

Example dataset file name:

```text
mosei_senti_data.pkl
