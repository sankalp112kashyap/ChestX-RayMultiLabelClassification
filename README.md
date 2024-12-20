# Catheter Position Classification in Chest X-Rays using ResNext50

Deep learning model for automated classification of catheter and tube positions in chest X-rays, achieving 93% accuracy across 11 position categories.

## Overview

This project implements a ResNext50-based deep learning model to classify the positions of medical devices (ETT, NGT, CVC, Swan Ganz Catheter) in chest X-rays as Normal, Borderline, or Abnormal. The solution incorporates novel anatomical masking techniques and robust data preprocessing to enhance model performance.

## Project Structure

- `notebooks/`: Jupyter notebooks for model development and analysis
- `src/`: Source code for the project
- `configs/`: Configuration files
- `requirements.txt`: Project dependencies

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ranzcr-catheter-classification.git
cd ranzcr-catheter-classification