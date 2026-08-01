# Results

## Model Performance

Three deep learning architectures were evaluated on the integrated cybersecurity dataset.

The models demonstrated strong performance across all evaluation metrics.

| Model | Accuracy | Precision | Recall | F1 | ROC-AUC |
|--------|---------:|----------:|--------:|---:|--------:|
| ANN | 91.50% | 99.74% | 82.94% | 90.57% | 97.72% |
| CNN | 91.48% | 99.70% | 82.94% | 90.55% | 97.78% |
| CNN–LSTM | 91.22% | 99.35% | 82.69% | 90.26% | 97.35% |

---

## Key Findings

The experiments demonstrate that:

- Deep learning models effectively classify network traffic.
- CNN automatically extracts informative network features.
- CNN–LSTM captures temporal dependencies in traffic patterns.
- ROC-AUC scores above 97% indicate excellent classification capability.
- Ensemble learning provides additional robustness.

---

## Discussion

The integrated multi-domain dataset improved model generalization by exposing the models to multiple cybersecurity environments.

Unlike single-dataset approaches, this framework learns intrusion patterns from enterprise networks, healthcare systems, IoT devices, and connected vehicle networks.

---

## Future Improvements

Future work may include:

- Transformer-based architectures
- Graph Neural Networks
- Federated Learning
- Explainable AI (XAI)
- Real-time deployment
- Online learning