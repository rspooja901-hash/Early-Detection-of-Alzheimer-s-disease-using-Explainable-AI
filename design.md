# System Design

## Overview
This system uses Deep Learning and Explainable AI to detect Alzheimer’s disease at an early stage from MRI brain images.

## Architecture
MRI images are collected and preprocessed. A CNN-based deep learning model analyzes the images and classifies disease stages. Explainable AI (LIME/SHAP) highlights affected brain regions for transparency.

## Process Flow
Patient → MRI Scan → AI Analysis → Explainable Output → Doctor Review → Early Diagnosis

## Technologies
- Deep Learning (CNN)
- Explainable AI (LIME / SHAP)
- Python, TensorFlow
