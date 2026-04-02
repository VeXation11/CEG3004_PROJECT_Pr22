# Experiment Log

| Experiment | Preprocessing | Features | Model | Macro-F1 | Notes |
|-----------|---------------|----------|-------|----------|------|
| 1 | Basic normalization | Baseline MFCC stats | Logistic Regression | 0.xxx | Baseline result |
| 2 | Trim + normalize + fixed 5s | MFCC + delta + delta2 | ExtraTrees | 0.53 | Better than baseline but unstable |
| 3 | Trim + normalize + fixed 5s | Log-mel + MFCC + spectral + robust pooling | SVM (RBF) | 0.574 | Best validation result |
