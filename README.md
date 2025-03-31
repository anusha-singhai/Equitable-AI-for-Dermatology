# Equitable-AI-for-Dermatology

---

### **👥 Team Members**

| Amy Zhang | 
| Joy Cheng |
| Kaley Chung |
| Anusha Singhai |
| Sunwoong Jang |

---

## **🎯 Project Highlights**

* The Break Through Tech AI Program is partaking in a Kaggle competition to further apply machine learning concepts we learned over the summer.
* Achieved an F1 score of 0.25 and a ranking of 44/74 on the final Kaggle Leaderboard
* Implemented data preprocessing methods such as resizing, normalization, rotations, and weighted sampling and augmentation to optimize results within compute constraints

🔗 [Equitable AI for Dermatology | Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)

---

## **👩🏽‍💻 Setup & Execution**


* To clone the repository:
* Install Git (if not already installed).

Clone the Repository:

Open a terminal or command prompt and run:
git clone <repository-url>

Navigate into the Repository:
cd repo

Install the appropriate dependencies and you should be ready to run the notebook.

---

## **🏗️ Project Overview**

The Break Through Tech AI Program is partaking in a Kaggle competition to further apply machine learning concepts we learned over the summer. 
- Objective: classify 21 different skin conditions across diverse skin tones from a subset of the FitzPatrick17k dataset with our model
- Significance: to use code to prevent the harm that AI perpetuate to misrepresented groups

---

## **📊 Data Exploration**

- Dataset Description: the subset of FitzPatrick17k dataset contains 4,500 images that is labeled with:
  - a unique md5hash identifier
  - a corresponding skin condition
  - Fitzpatrick skin tone scale values (both self-reported and assigned by Centaur Labs)
- Data Preprocessing: applied resizing, normalization, rotations, and weighted sampling and augmentation
- EDA (Exploratory Data Analysis) Visualizations:
  1) Distribution of Skin Conditions: A bar chart showing the number of images per skin condition to visualize class imbalance.
  2) Fitzpatrick Skin Tone Distribution: A histogram showcasing representation across different skin tones.
  3) Sample Images Across Classes: A grid displaying example images from various conditions to understand visual patterns.

---

## **📈 Results & Key Findings**

* Our model had a score of about 0.25, a bit lower on the Kaggle leaderboard. Although our model performed relatively fairly across different skin tones, the model itself could likely be fine-tuned to be more accurate overall. 

---

## **🖼️ Impact Narrative**

**AJL challenge:**

As Dr. Randi mentioned in her challenge overview, “Through poetry, art, and storytelling, you can reach others who might not know enough to understand what’s happening with the machine learning model or data visualizations, but might still be heavily impacted by this kind of work.”
As you answer the questions below, consider using not only text, but also illustrations, annotated visualizations, poetry, or other creative techniques to make your work accessible to a wider audience.
Check out [this guide](https://drive.google.com/file/d/1kYKaVNR\_l7Abx2kebs3AdDi6TlPviC3q/view) from the Algorithmic Justice League for inspiration!

1. What steps did you take to address [model fairness](https://haas.berkeley.edu/wp-content/uploads/What-is-fairness_-EGAL2.pdf)? (e.g., leveraging data augmentation techniques to account for training dataset imbalances; using a validation set to assess model performance across different skin tones)

We worked to understand any biases or imbalances in the training dataset through data preprocessing and data visualization techniques, including   
  1) Distribution of Skin Conditions: A bar chart showing the number of images per skin condition to visualize class imbalance.
  2) Fitzpatrick Skin Tone Distribution: A histogram showcasing representation across different skin tones.
  3) Sample Images Across Classes: A grid displaying example images from various conditions to understand visual patterns.
All of these were used to determine and visualize imbalances in the dataset in order to minimize our model performingly unfairly 
3. What broader impact could your work have?
Biases in dermatology for underrepresented groups are still prevalent. It's important to understand that as we develop new technology like machine learning models to identify skin conditions, they may have been trained on imbalanced data sets. By recognizing, identifying, and thus minimizing this imbalance, we can work towards eliminating these biases towards underrepresented groups and skin colors in dermatology.

---

## **🚀 Next Steps & Future Improvements**

* With more time and resources, we could have tried several different approaches, comparing and contrasting them in order to improve the accuracy of our model.

---

---

