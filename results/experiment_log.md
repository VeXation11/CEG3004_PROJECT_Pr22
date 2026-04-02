# Experiment Log

| Experiment | Features | Model | Macro-F1 | Notes |
|-----------|----------|-------|----------|------|
| 1 | MFCC stats | Logistic Regression | baseline | baseline performance |
| 2 | MFCC + spectral features | ExtraTrees | ~0.53 | improved but unstable |
| 3 | Full DSP features + pooling | SVM (RBF) | ~0.574 | best result |

## Observations
- Adding spectral features improved performance significantly
- Robust pooling improved stability
- SVM performed better than tree-based models for this feature set
