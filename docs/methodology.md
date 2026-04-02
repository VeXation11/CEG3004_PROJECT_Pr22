# Methodology

## Preprocessing
Audio is normalized, trimmed, and resized to fixed length to ensure consistency.

## Feature Extraction
Multiple DSP features are extracted to capture:
- frequency content (MFCC, log-mel)
- temporal variation (delta features)
- spectral shape (centroid, bandwidth, rolloff)

## Robustness
Training-time augmentation is applied to simulate:
- noise
- amplitude variation
- band-limited signals

## Model Selection
SVM with RBF kernel was selected due to strong performance on high-dimensional feature vectors.
