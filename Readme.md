# Tumor Vessel Risk Score Prediction Model

This repository contains the implementation of an AI-based tumor vessel biomarker for predicting Stereotactic Body Radiation Therapy (SBRT) response in Non-Small Cell Lung Cancer (NSCLC).

## Overview

Our model analyzes 3D tumor vessel images extracted from contrast-enhanced CT scans to predict SBRT response and patient prognosis. The model uses a combination of Vision Transformer (ViT) and LSTM to learn vessel features, and calculates a Vessel Risk Score (VRS) using Mahalanobis distance.

## Key Features
- Vessel and tumor segmentation from CT scans
- Feature extraction using ViT-LSTM architecture
- VRS calculation using Mahalanobis distance
- Treatment response prediction and survival analysis
