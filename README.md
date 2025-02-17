# Accent Recognition Project
CS 582 – Spring 2025

Team Members:
Tai Truong (Team Leader & Scribe)
James Johnson (Organization)
Kyle Kucharski (Data Manager)
Wissam Almasri (Data & Translation)

Project Overview
This project focuses on developing an Accent Recognition System that classifies spoken speech into different accents, including American, British, and Vietnamese. The system will analyze speech features and apply machine learning techniques to distinguish accents based on their unique characteristics.

Goals:
Process speech data from Common Voice + L2-ARCTIC datasets.
Extract MFCCs, Pitch, Formants, and Prosody from audio files.
Train a machine learning model to classify accents.
Evaluate the model’s performance and optimize results.

Repository Structure
This repository contains all project files, datasets, and scripts.
data/          # Speech datasets (Common Voice + L2-ARCTIC)
scripts/       # Python scripts for preprocessing & feature extraction
notebooks/     # Jupyter Notebooks for testing & model training
docs/          # Reports & project documentation
README.md      # Project description & setup guide

Project Workflow
1. Data Collection & Preprocessing (Weeks 1-2)
Download & clean Common Voice + L2-ARCTIC datasets.
Convert all files to 16kHz WAV format.
2. Feature Extraction (Weeks 3-4)
Extract MFCCs, Pitch, and Formants from speech data.
Visualize feature differences across accents.
3. Model Training (Weeks 5-6)
Train baseline classifiers (SVM, Random Forest).
Implement deep learning models (LSTM, CNN, Wav2Vec).
4. Testing & Optimization (Weeks 7-8)
Evaluate model performance using precision, recall, and confusion matrices.
Finalize results & prepare presentation.

