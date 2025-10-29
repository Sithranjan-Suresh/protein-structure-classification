# Protein Structure Classification 🧬  
UTD Biotech Club – Mini Project Workshop (Fall 2025)

## Overview
This project aims to train ML models to classify protein structures (enzyme, membrane protein, etc.) using structural and experimental metadata.  
It’s part of a 5-week workshop focused on learning data preprocessing, feature engineering, model training, and hyperparameter tuning.

## Progress Log
### Week 1 – Data Cleaning & Visualization
- Loaded dataset and inspected columns using pandas
- Handled missing values
- Created histograms for residue count, resolution, and publication year trends
- Visualized correlations using a heatmap
- Learned why features like resolution and residue count matter in protein crystallography

### Week 2 – Feature Encoding & Normalization
- Differentiated between categorical and numerical features
- Encoded categorical variables using OneHot and LabelEncoding:
  - `experimentalTechnique`
  - `macromoleculeType`
  - `crystallizationMethod`
- Normalized numeric features (`residueCount`, `resolution`, `molecularWeight`)
- Built pairplots of numeric features colored by protein classification
- Gained hands-on experience preparing data for ML model training
- 
### Upcoming Weeks 
- **Week 3:** Model training and evaluation  
- **Week 4:** Hyperparameter tuning and pipeline building  
- **Week 5:** Final presentation and app demo  

## Tech Stack
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Google Colab

## Author
**Sithranjan Suresh**  
Computer Science @ UTD | Cybersecurity & AI Enthusiast
