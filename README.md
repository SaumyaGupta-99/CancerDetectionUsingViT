# Lung Cancer Detection from Chest CT Scans — Vision Transformer

Vision-Transformer based image classifier to detect and distinguish adenocarcinoma, large (lung) cell carcinoma, squamous cell carcinoma, and normal (non-cancer) from chest CT images.

---

# Overview

Cancer detection from medical images is a highly promising application of AI, offering critical support to scientists and clinicians for early and reliable diagnosis. This project trains and evaluates a Vision Transformer (ViT) model to classify chest CT scans into four classes:

- Normal (non-cancer)
- Adenocarcinoma
- Large cell carcinoma
- Squamous cell carcinoma

The model leverages transformer-based image representation learning to improve diagnostic precision and help clinical decision-making in early-stage lung cancer detection.

---

# Key Results

- **Overall test accuracy:** **88%**
- **Overall F1 (cancer classes average):** ~**0.84–0.85**

Classification metrics (summary):

| Class                   | Precision | Recall | F1-score |
|------------------------:|:---------:|:------:|:--------:|
| Normal                 | 0.98      | 1.00   | 0.99     |
| Adenocarcinoma         | 0.81      | 0.87   | 0.84     |
| Large cell carcinoma   | 0.93      | 0.79   | 0.85     |
| Squamous cell carcinoma| 0.84      | 0.86   | 0.85     |

Interpretation: the model is very effective at recognizing normal samples, and achieves balanced performance across cancer subtypes despite class imbalance. Some classes show trade-offs (e.g., higher precision but lower recall) indicating areas for further improvement.

---
