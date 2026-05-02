# Person-re-identification-under-different-lighting-conditions.
This thesis focuses on Cross-Modality Person Re-Identification (ReID) using RGB and Infrared (IR) images for surveillance and security applications. The goal is to develop a deep learning-based system capable of identifying the same person across different camera modalities (visible and infrared spectrum), especially under varying lighting conditions.

This work is particularly useful for 24/7 surveillance systems, where RGB cameras fail in low-light or night conditions and IR cameras become essential.

Dataset:
The project uses benchmark datasets such as:

RegDB Dataset (RGB–IR paired dataset)

Dataset includes:

-RGB images (daytime)
-IR images (night-time / thermal
<br>
METHODOLOGY:
<br>
The system follows a deep learning pipeline:

Data Preprocessing:
-Image resizing
-Normalization
-Data augmentation
Feature Extraction:
-CNN-based backbone (e.g., ResNet)
Feature Alignment:
-Cross-modality feature learning
-Metric learning / loss functions
Matching & Retrieval:
-Euclidean / cosine similarity
-Ranking-based evaluation
