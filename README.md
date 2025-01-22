
# Mammo_GENAI

## Overview

Welcome to the **Mammo_GENAI** repository. This project explores the integration of **Generative AI (GENAI)** and **computer vision** for advanced **mammogram analysis**. It aims to leverage synthetic data generation, abnormality classification, and lesion inpainting techniques to improve the accuracy and efficiency of breast cancer diagnosis. This repository contains a series of Jupyter notebooks and utilities designed for various tasks in mammogram image analysis, including:

- **Abnormality Classification** to identify and classify anomalies in mammograms
- **Lesion Inpainting** for generating realistic lesions in synthetic data
- **Data Preprocessing & Utility Scripts** for converting medical images (e.g., DICOM to PNG)
- **Inference Notebooks** for running models and generating predictions

This project is built with the objective to explore **Hybrid Generative AI** techniques for improving the diagnostic process in breast cancer detection.

## Contents

The repository includes the following directories and files:

### 1. **Dreambooth**
- **`dreambooth_mammo_lesion_inpainting.ipynb`**: Generating synthetic lesion images using Dreambooth for lesion inpainting.
- **`dreambooth_mammo_lora_ft.ipynb`**: Fine-tuning Dreambooth for mammogram lesion generation using LoRA (Low-Rank Adaptation).
- **`dreambooth_mammo_pt.ipynb`**: Dreambooth model fine-tuning for mammogram lesion generation.
- **`dreambooth_mammo.ipynb`**: General-purpose Dreambooth model for mammogram analysis.

### 2. **Abnormality Classification**
- **`abnormality_classification_with_synthetic_data.ipynb`**: Abnormality classification using synthetic data.
- **`abnormality_model_classification.ipynb`**: Abnormality classification using a real-world model.
- **`abnormality_classification_without_synthetic_data.ipynb`**: Abnormality classification excluding synthetic data.

### 3. **Image Processing Utilities**
- **`DCM_to_PNG.ipynb`**: Utility for converting DICOM medical images to PNG format.

### 4. **Data Analysis**
- **`emory_mammo_eda.ipynb`**: Exploratory data analysis (EDA) on the Emory mammogram dataset.
- **`VinDR_Mammogram_EDA.ipynb`**: Exploratory data analysis (EDA) on the VinDr dataset.

### 5. **Inference**
- **`Inference.ipynb`**: A notebook for performing inference using trained models for object detection, classification, and lesion inpainting.

### Requirements

- Python 3.10

## Results & Discussion

The results from various notebooks will allow you to evaluate different models and techniques for mammogram image analysis. Key findings include:

- **Abnormality Classification**: Analyzing the role of synthetic data in identifying abnormalities and improving model performance for breast cancer detection.
- **Lesion Inpainting**: Demonstrating the ability of Generative AI models to generate realistic lesions in synthetic datasets, which can be used to enhance model training and improve diagnosis.

## Contributions

We welcome contributions to improve the models and expand the project. If you wish to contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

