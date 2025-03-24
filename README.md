# Equitable-AI-for-Dermatology

## Project Overview
The Break Through Tech AI Program is partaking in a Kaggle competition to further apply machine learning concepts we learned over the summer. 
- Objective: classify 21 different skin conditions across diverse skin tones from a subset of the FitzPatrick17k dataset with our model
- Significance: to use code to prevent the harm that AI perpetuate to misrepresented groups

## Data Exploration
- Dataset Description: the subset of FitzPatrick17k dataset contains 4,500 images that is labeled with:
  - a unique md5hash identifier
  - a corresponding skin condition
  - Fitzpatrick skin tone scale values (both self-reported and assigned by Centaur Labs)
- Data Preprocessing: applied resizing, normalization, rotations, and weighted sampling and augmentation
- EDA (Exploratory Data Analysis) Visualizations:
  1) Distribution of Skin Conditions: A bar chart showing the number of images per skin condition to visualize class imbalance.
  2) Fitzpatrick Skin Tone Distribution: A histogram showcasing representation across different skin tones.
  3) Sample Images Across Classes: A grid displaying example images from various conditions to understand visual patterns.
