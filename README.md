# Reflective Writing LLM and ML Comparison
## Overview
This repository contains the code and resources for the Master’s thesis “Analysis of Reflective Writing: Comparing Machine Learning and Large Language Model Approaches.” The research explores the effectiveness of traditional machine learning models against large language models (LLMs), such as LLaMA-3 in classifying levels of reflective writing. Using a codebook developed by the Human-Centered Computing (HCC) Research Group, the study aims to:
- Determine whether traditional machine learning models can match or outperform a fine-tuned LLaMA-3 model.
- Analyze differences in classification performance, feature importance, and alignment with the reflection-level codebook across models.

The repository includes:
- All code used for data preprocessing, training, and evaluation
- Implementations of various traditional machine learning models including Logistic Regression, Support Vector Machines (SVM), Naive Bayes, Random Forest, SVM Ordinal Regression, SVM Pairwise Constraints, and Ordinal Forest
- Visualizations and results of feature importance and model performance

## Repository Structure
- **README.md**: Provides an overview and description of the repository.
- **exploratory_data_analysis.ipynb**: Jupyter notebook for exploring the original dataset.
- **logistic_regression.ipynb**: Jupyter notebook for Logistic Regression model.
- **naive_bayes_classifier.ipynb**: Jupyter notebook for Naive Bayes model.
- **ordinal_forest.ipynb**: Jupyter notebook for Ordinal Forest model.
- **random_forest.ipynb**: Jupyter notebook for Random Forest model.
- **support_vector_machine.ipynb**: Jupyter notebook for Support Vector Machine model.
- **svm_ordinal_regression.ipynb**: Jupyter notebook for SVM with ordinal regression model.
- **svm_pairwise_constraints.ipynb**: Jupyter notebook for SVM with pairwise constraint model.
- **Coded_Segments.csv**: dataset used across the models.

## Dataset
The dataset consists of 237 coded text segments extracted from reflective writing assignments submitted by 12 anonymized students in a Human-Centered Data Science course. Each segment is labeled according to a structured reflection-level codebook ranging from Level 1 (Descriptive) to Level 4 (Critical Reflection). These pre-labeled segments are stored in a single CSV file and serve as the basis for training and evaluating the classification models in this study.

## Results
Traditional machine learning models such as Logistic Regression and Support Vector Machines outperformed a fine-tuned LLaMA-3 model in classifying levels of reflective writing. Feature importance analysis revealed strong alignment between model behavior and theoretically defined reflection levels, offering insights into linguistic patterns across reflection depth.

## Acknowledgments
This research was conducted under the supervision of Prof. Dr. Claudia Müller-Birn at Freie Universität Berlin, Institute of Computer Science, Human-Centered Computing (HCC) Research Group.

## Contact
For questions or feedback, please contact Se Yeon Kim at seyeon.c.kim@gmail.com.
