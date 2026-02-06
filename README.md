Project Workflow

Overview

This project performs subject-specific evaluation of Motor Imagery (MI) EEG paradigms using hybrid feature selection and ranking techniques. The workflow below summarizes the complete pipeline followed in this project.

Workflow Steps

1️⃣ Data Preparation

Load EEG data into the Colab environment
Clean and organize the dataset
Structure data for feature extraction and modeling


2️⃣ Feature Extraction

EEG signals are transformed into meaningful numerical features such as:

Statistical features
Frequency-domain features
Signal-based representations
These features form the input for model evaluation.


3️⃣ Hybrid Feature Selection

To improve performance and reduce dimensionality:

Successive Halving strategy used for efficient selection
SVR-based ranking applied to evaluate feature importance
Top-performing features retained



4️⃣ Model Evaluation

Selected features used for classification experiments
Performance measured using F1 Score
Evaluation performed across multiple approaches and feature sets



5️⃣ Result Analysis

Results organized into structured DataFrames

Comparison performed across:

Features
Approaches
Subjects



6️⃣ Visualization

Boxplots generated to compare F1-score distributions
Visual interpretation used to understand performance trends


Tools & Technologies

Python
Google Colab
NumPy
Pandas
Matplotlib / Seaborn
Scikit-learn
Execution Flow Summary

Data Loading ⬇ Feature Extraction ⬇ Feature Selection & Ranking ⬇ Model Evaluation ⬇ Performance Visualization
