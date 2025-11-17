# Protein Structure Classification 🧬

UTD Biotech Club – Mini Project Workshop (Fall 2025)

## Overview

This project focuses on training machine learning models to classify protein structures (e.g., enzymes, membrane proteins) using structural and experimental metadata. It was completed as part of a 5‑week workshop hosted by the UTD Biotech Club, covering data cleaning, feature engineering, model building, tuning, and deployment.

## Progress Log

### Week 1 – Data Cleaning & Visualization

* Loaded and explored the dataset using pandas
* Handled missing values and inspected data integrity
* Created histograms for residue count, resolution, and publication year
* Plotted correlation heatmaps
* Learned the importance of resolution, residue count, and other structural features in crystallography

### Week 2 – Feature Encoding & Normalization

* Distinguished between numerical and categorical features
* Applied OneHotEncoding and LabelEncoding to:

  * `experimentalTechnique`
  * `macromoleculeType`
  * `crystallizationMethod`
* Normalized numerical features such as `residueCount`, `resolution`, and `molecularWeight`
* Built pairplots to visualize numeric relationships by protein classification

### Week 3 – Model Training & Evaluation

* Performed train/test split for proper model evaluation
* Trained multiple classifiers:

  * Logistic Regression
  * Decision Trees
  * Random Forests
* Evaluated models using accuracy, precision, recall, and confusion matrices
* Identified features contributing most to prediction performance

### Week 4 – Applying Concepts to Kidney Disease Prediction

* Switched datasets to the **Kidney Disease Prediction Dataset**
* Applied all preprocessing steps learned in previous weeks:

  * Cleaning, handling missing values, encoding, and normalization
* Trained classification models on the new dataset
* Compared performance of models on biomedical/clinical data
* Built an ML pipeline to streamline preprocessing → model training
* Created a prediction function that accepts patient metadata and outputs disease prediction

### Week 5 – Final Presentation & Wrap-Up – Final Presentation & Wrap‑Up

* Demonstrated the final tuned model
* Showcased visualizations, feature importance, and prediction function
* Presented insights and workflow to club members

## Tech Stack

* Python (pandas, numpy, scikit‑learn)
* Visualization: matplotlib, seaborn
* Google Colab

## Project Structure

```
week1_data_cleaning_visualization/
week2_feature_encoding_normalization/
week3_classification_models_and_evaluation/
week4_kidney_disease_prediction/
```

## Author

**Sithranjan Suresh**
Computer Science @ UTD | Cybersecurity & AI Enthusiast
