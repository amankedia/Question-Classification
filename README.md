# Question-Classification
Classifying questions from UIUC's CogComp QC Dataset

# Classifying Questions into Coarse (6 classes) and Fine (50 classes) classes.

# Approach
1. Text Exploration
2. Text Cleaning
3. Obtaing POS Tags, Identifying Named Entities, Lemmas, Syntactic Dependency Relations and Orthographic Features.
4. Using the obtained properties as Features.
5. Using a Linear SVM model on the engineered features.

# Results
* 87.8% accuracy on Coarse classes.
* 80.7% accuracy on Fine classes.
