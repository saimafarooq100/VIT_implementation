Dermoscopic Lesion Classification Using Vision Transformers
ViT-B/16 vs MobileNetV3-Large on ISIC Archive 2019 —
Dataset: ISIC Archive 2019 — 25,331 dermoscopic images, 8 classes
Models: ViT-B/16 (primary) vs MobileNetV3-Large (baseline)
Metrics: Accuracy, Precision, Recall, F1 (macro + per-class), Balanced Accuracy, AUC-ROC, Confusion Matrix
Runs in: Jupyter Notebook (local) — Python 3.8+ with GPU recommended

Setup steps:
Run Cell 1 to install packages
Set DATA_DIR in Cell 3 to your local ISIC 2019 folder
Run all cells top to bottom — Kernel → Restart & Run All
Dataset download: https://www.kaggle.com/datasets/andrewmvd/isic-2019
