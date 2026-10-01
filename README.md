# 🗑️ Garbage Image Classification

An image classification pipeline that identifies 10 categories of waste from images using transfer learning and deployment-ready model formats.

## ⚙️ What I Built

- Prepared and validated **12,259 images**, retaining **12,252 valid samples** across 10 waste categories.
- Explored class balance and standardized **2,407 different image resolutions** through a consistent preprocessing pipeline.
- Addressed uneven class representation with **balanced class weights** and strengthened generalization with image augmentation.
- Built an **EfficientNetV2S** transfer-learning classifier with staged feature extraction and fine-tuning.
- Added reproducible training controls: fixed seeds, checkpointing, early stopping, and learning-rate scheduling.
- Evaluated performance with accuracy, Top-3 accuracy, per-class precision/recall/F1, and a confusion matrix.
- Exported the trained model as **TensorFlow SavedModel**, **TensorFlow.js**, and **TensorFlow Lite**, then verified inference on sample images.

## 🛠️ Tech Stack

**Python · TensorFlow\Keras · EfficientNetV2S · NumPy · Pandas · scikit-learn · Matplotlib · KaggleHub · Jupyter Notebook**

## 🤖 Result

- **94.89% test accuracy**
- **99.40% Top-3 accuracy**
- **0.94 macro F1**
- **20.96 MB TensorFlow Lite model**
- Verified inference across the 10 target categories.
