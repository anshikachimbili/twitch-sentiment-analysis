# Multimodal Twitch Sentiment Analysis

## Overview
This project predicts Twitch chat sentiment by combining video and audio data from stream clips. It uses embeddings from video (V-JEPA) and audio (Whisper) to train a model that predicts common Twitch emotes.

## Pipeline
1. Extract video embeddings using V-JEPA
2. Extract audio embeddings using Whisper
3. Combine embeddings into a single feature vector
4. Train a neural network to predict emote distributions

## Files
- `embedding_extraction.ipynb`: Extracts video and audio embeddings
- `training.ipynb`: Trains the multimodal model and evaluates performance

## My Contribution
This was a team project. I contributed to working with embeddings and training the model, and gained experience with multimodal machine learning pipelines.

## Notes
Due to dataset size, the full data is not included. File paths may need to be adjusted to run the notebooks.
