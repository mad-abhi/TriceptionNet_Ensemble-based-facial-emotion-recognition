# Facial Emotion Recognition with Ensemble Deep Learning Models

This project implements a facial emotion recognition system using the FER 2013 dataset. The system employs an ensemble of three powerful deep learning models: InceptionResNetV2, EfficientNetB0, and ResNet50, combined using a Multi-Layer Perceptron (MLP) for the final prediction.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Architecture](#architecture)
- [Results](#results)

## Introduction
Facial emotion recognition (FER) is a crucial task in human-computer interaction, enhancing applications ranging from sentiment analysis to mental health monitoring. This project leverages an ensemble learning approach combining InceptionResNetV2, EfficientNetB0, and ResNet50 models to boost emotion classification performance.

## Dataset
The FER 2013 dataset is used in this project. It consists of grayscale images of faces, each sized at 48x48 pixels, categorized into the following emotion classes:
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

## Architecture
The project incorporates three deep learning models:
1. **InceptionResNetV2**: A hybrid architecture merging the strengths of Inception modules and residual connections.
2. **EfficientNetB0**: A lightweight, efficient model that balances accuracy and computational cost.
3. **ResNet50**: A residual network known for its effective deep feature extraction.

The outputs from these models are combined and passed through an MLP for the final classification.

## Results
Detailed performance metrics and confusion matrices will be generated after training. The combined ensemble typically yields higher accuracy and robustness than individual models.
