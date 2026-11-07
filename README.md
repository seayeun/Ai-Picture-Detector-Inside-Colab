# AI Picture Detector

<p align="center">
  <strong>Detect AI-Generated Images Using Deep Learning</strong>
</p>

<p align="center">
  A Google Colab-based image classification project powered by PyTorch and Hugging Face Transformers.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Google-Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</p>

---

## Overview

**AI Picture Detector** is a Python-based image classification project designed to identify whether an uploaded image is likely to be AI-generated or camera-created.

The project uses a pre-trained deep learning model from Hugging Face to analyze images and generate classification scores. It provides an interactive workflow through Google Colab, allowing users to upload an image, visualize it, inspect the model's predictions, and interpret the results.

Rather than training a model from scratch, this project leverages an existing image classification model for inference.

## Features

- **AI Image Detection** – Classifies uploaded images using a pre-trained deep learning model.
- **Interactive Image Upload** – Upload images directly through Google Colab.
- **Image Visualization** – Displays the uploaded image before analysis.
- **Prediction Scores** – Provides classification labels and their corresponding confidence scores.
- **Result Interpretation** – Groups model predictions into AI-related and real-image-related categories.
- **GPU Acceleration** – Automatically uses CUDA when an available GPU is detected.
- **Tabular Results** – Displays classification output using Pandas DataFrames.

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| PyTorch | Deep learning framework |
| Hugging Face Transformers | Pre-trained image classification pipeline |
| Organika/sdxl-detector | AI image detection model |
| Pillow (PIL) | Image loading and processing |
| Pandas | Prediction data handling |
| Matplotlib | Image visualization |
| Google Colab | Cloud-based execution environment |


### Detection Model

The project uses:

`Organika/sdxl-detector`

The model is loaded through the Hugging Face `pipeline()` API using the `image
