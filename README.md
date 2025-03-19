# Fine-tuning SAM and MicroSAM for Microscopy Image Segmentation

## Overview
This project focuses on fine-tuning **Segment Anything Model (SAM)** and **MicroSAM** for microscopy image segmentation. The repository provides a structured approach to utilizing pretrained SAM, fine-tuning SAM on a custom labeled dataset, applying watershed-based segmentation to post-process fine-tuned SAM results, and implementing MicroSAM as an alternative to compare segmentation performance on a custom image dataset.

## Files
The following files are included in this repository:

1. **`pretrained_SAM.ipynb`** - demonstrates the segmentaiton performance of **pretrained SAM** for microscopy image. 
2. **`finetuned_SAM.ipynb`** - details the process of **fine-tuning SAM model** on custom microscopy images to improve segmentation performance.
3. **`watershed.ipynb`** - implements **watershed-based segmentation**, to converts the probability map from the result of fine-tuned SAM to multiple masks segmentation.
4. **`MicroSAM.ipynb`** - applied **MicroSAM**, an optimized version of SAM for microscopy image segmentation.

