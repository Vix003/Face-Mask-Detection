# Face-Mask-Detection
Overview
This project implements a binary face mask detection system using deep learning. It evaluates three models — Custom CNN, MobileNetV2, and ResNet50 — and combines their predictions with a stacked ensemble model to improve accuracy and robustness.

Datasets
FM12k: ~12,000 labeled images (With Mask / Without Mask)
RMFD: 5,000 masked and 90,000 unmasked images of public figures

Approach
Images resized to 128×128 and normalized.
Models trained with transfer learning (MobileNetV2, ResNet50) and a custom CNN baseline.
Ensemble combines predictions using a shallow neural network meta-learner.
