#  Student Performance Prediction

This project uses machine learning to predict whether a student will pass or fail based on various factors such as attendance, study habits, and parental support. A Random Forest Classifier is used to perform the classification, and evaluation is done using confusion matrix, accuracy, precision, and recall.

---

##  Dataset

The dataset includes features like:
- Absences
- Weekly Study Time
- Tutoring
- Parental Support
- Extracurricular Activities
- Sports, Music, Volunteering
- Parental Education
- Age
- GPA (used to derive the target label)

> Target variable: **Pass** (1 = GPA ≥ 2.0, 0 = GPA < 2.0)

---

## Methodology

1. **Data Preprocessing**
   - Created a binary target column (`Pass`) based on GPA.
   - Selected relevant features for prediction.
   - Split data into training (80%) and testing (20%) sets.

2. **Model**
   - Used a **Random Forest Classifier** from scikit-learn.
   - Evaluated using confusion matrix, accuracy, precision, and recall.

---

##  How to Run

1. Upload the dataset
2. Install required libraries:
```bash
pip install pandas seaborn scikit-learn matplotlib

